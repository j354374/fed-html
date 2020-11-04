:beginner:\
Portfolio Activity - Project Task 1 – Creation of 4-page HTML5 website and Documentation\
Name: Christopher Paul Caston\
Student id: j354374

## Website Audience

The audience is job seekers especially those for whom the income from a job would improve their standard of living. It site is to be used by people who are keen to work but are struggling with standard recruitment processes. The concept is that we flip recruitment so that workers are much more informed and enpowered. We tell them where the work is and where the labour shortages are by data mining the information from publically available sources such as the Australian Bureau of Statistics. The website also gives job seekers a listing of the core skills needed for a job to help them find the work they are suitable for.

## Markup language used

HTML5 has been used and in particular the details and summary element. This presented a challenge as this was not supported by Microsoft Internet Explorer or even their more recent browser called Edge. To enable users of this brower to get the full functionality of our site we have used a Javascript polyfill. This enables us to use the tags on the website and the Javascript file renders them correctly on the IE and Edge browser.

## Website strucutre and wireframe

The structure wireframe has been drawn in Adobe XD with measurements included. Please see "SHT jobs.pdf". Originally the website was built using the grid layout system but there was some trouble controlling the spacing between the navigation bar and main.

## HTML5 elements

The following elements were used in the document and the css style sheet:

header
section
article
nav
main
aside
footer
figure

Many others (previous to HTML5) were used such as td,th, ul, li and span.

## beautifier
The following site was used to "clean" the html and css code to make it easier to read:
https://codebeautify.org/htmlviewer/
however, it created an error of "undefined" at the top of the HTML file when attempting to clean index.html. I repeated this after running the validator and fixing any errors or warnings and the issue resisted.

The HTML code has been kept reasonbly clean and tidy during production so I have decided just to proceed to validation.

## validation

about.html:
![about](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/about-html-validation.png)
contact.html:
![contact](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/contact-html-validation.png)
data.html:
![data](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/data-html-validation.png)
reports.html:
![reports](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/reports-html-validation.png)
index.html:
![index](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/index-html-validation.png)
style-css-validation:
![style](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/style-css-validation.png)


[CSS lint](http://csslint.net) found 0 errors and 39 warnings.\ 
[another html lint](http://www.htmllint.net/) came up with this:
![lint](https://raw.githubusercontent.com/j354374/fed-html/master/project-task1-4page-site/readmefiles/htmllint.png)
And it has been fixed.



## references

An image from an underground mining vehicle was included from wikipedia. Please see:
https://en.wikipedia.org/wiki/Underground_mining_(soft_rock)
https://en.wikipedia.org/wiki/Underground_mining_(soft_rock)#/media/File:VKG_Ojamaa_kaevandus.jpg

Icons provided by Icofont(https://icofont.com/). Background images from SVG Patterns Gallery(https://philiprogers.com/svgpatterns/), SVG Backgrounds (https://www.svgbackgrounds.com/#flat-mountains) and the cloud header was from loading.io. (https://loading.io/background/m-clouds) 

skills.js script was written by mplungjan (online alias) in response to the following [stackoverflow question](https://stackoverflow.com/questions/64661591/use-javascript-to-create-hyperlink-from-html5-details-summary-data-element/64661875#64661875)
please also see the codepen:
https://codepen.io/j354374/pen/WNxyReJ

HTML/CSS tables were written with reference to the following [codepen](https://codepen.io/AllThingsSmitty/pen/MyqmdM) by [Matt Smith)[https://codepen.io/AllThingsSmitty]).
