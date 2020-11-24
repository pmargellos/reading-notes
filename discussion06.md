[Home](https://pmargellos.github.io/reading-notes)

# Module 06 discussion

## Title: Dynamic web pages with JavaScript

Javascript is written in plain text like other scripting we have learned in previous notes. Same as we have used in CSS and HTML.

The following shows where Javascript fits in the creation of web a dynamic webpage.
HTML is the Content Layer - This the layer where all of the content of the page     
lives.

CSS is the Presentation Layer - CSS is the enhancement to the HTML with rules that state how the HTML content will be presented.

JAVASCRIPT is where changes are made to effect how the page behaves, adding interactivity.

All the above pieces work together by what is called Progressive Enhancement.

1. HTML Only - Starting with the HTML layer we focus on the most important thing about your site and it's content. This is why we learned HTML first.
2. HTML + CSS adding the CSS rules state how the content will be presented in a seperate file.
3. HTML + CSS + JAVASCRIPT - The next thing to learn is javascript. This adds usability and interactivity to the page.

The following code is an example of adding interactiviy to a page that will give you a different greating depending on the time of day. This is all set in motion by the time that is present on your computer.


1. var today = new Date();
2. var hourNow = today.getHours();
3. var greeting;
4. if (hourNow > 18) {
5.    greeting = 'Good evening!';
6. } else if (hourNow > 12) {
7.    greeting = 'Good afternoon!';
8. } else if (hourNow > 0) {
9.   greeting = 'Good morning!';
10. } else {
11.   greeting = 'Welcome!';
12. }
13. document.write('<h3>' + greeting + '</h3>')

