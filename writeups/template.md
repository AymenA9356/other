# Process Writeup

## Name: Aymen Anse
## Course: SEP10 (Web Design)
## Period: 2
## Concept: HTML elements

### Challange 1:Internal link problem

The first problem I had was to Link to Internal Sections of a Page with Anchor Elements. The plan was to change this HTML code that was to an external link into a internal link `<a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a>`. The first step to change this code was to Change your external link to an internal link by changing the href attribute to `#footer` and the text from cat photos to Jump to Bottom and remove the `target="_blank"` attribute from the anchor tag. After these steps the code I got was this code `<a href="#footer">Jump to Bottom</a>`. The next steps arew to then add an id attribute with a value of footer to the <footer> element at the bottom of the page. The code I got was this `<a footer="footer">Copyright Cat Photo App</footer></a>`. I got an error saying "There should be only one anchor tag on your page. There should be only one footer tag on your page.
The footer tag should have an id attribute set to "footer". I tried another line `<a ="footer">Copyright Cat Photo App</footer></a>`. This line of code has the same error but another one said "The footer tag should have an id attribute set to "footer". After that I figured it out and that the code should be `<footer id="footer">Copyright Cat Photo App</footer>` then I got that lesson correct.


---

NOTE: to see the raw code for this file, click [here](https://raw.githubusercontent.com/hstatsep/other/main/writeups/template.md)
