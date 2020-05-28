<!-- Is my methodology important? Am i over sharing? -->
This code refactor aimed to clean up the source code and improve accessibility. Web accessibility finds itself at the crossroads of web content, user agents, and authoring tools. These components inter-relate and support each other, and as websites become more sophisticated so too do accessibility concerns. My essential principles were to address image alt attributes, keyboard accessibility, text to speech and vise versa, and formatting for multiple devices.  

Luckily here, this web page is quite simple. The links only refer to further down the page, and our keyboard commands can navigate that for us. So mouse input concerns are covered. There is no audio so no need to concerns ourselves with such things, and as long as our h tags and p tags are set properly text to speech will work. Our images however are all missing alt tags. For all but the .hero image that is an easy fix, I simply used their descriptive file names as alt text as they seemed appropraite. For the .hero I added a title attribute, as the image is not represented directly in the html. According to the W3C, the title attribute serves much of the same purpose as the alt attribute. 

Another major concern is accessibility accross devices. Our links may not be large enough for mobile phone users, but again the site doesn't lose functionality from that. However, I did add a meta name "viewport" to control scaling.

Moving on from accessibility concerns, the html follows a logical structure but is not neatly formatted. I added spacing between lines and fixed indendation to make the code more legible. I added a title to the page "Horiseon Solutions", an abbrevation of "Horiseon Social Solutions Services" found at the footer, which fits neatly on a tab.

<!-- 
to do
To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Is this a true statement? Cause I said it --- and as long as our h tags and p tags are set properly text to speech will work


make sure its ok to use title for the image .hero
should i be more specific (e.g. i used double spacing to improve legibility)? less?

Did not cover these directly in the README. 

Headers are in order, but they also are reused within div sections, is that best practice?

WHEN I view the heading attributes
THEN they fall in sequential order


Sure I find semantic HTML elements, what does this even mean?

 WHEN I view the source code
THEN I find semantic HTML elements

I think its logical. It starts at the top, then goes down past the main picture .hero  to the content with the sidebar benefits after that just before the footer. Seems independ of style an positioning, but I didn't really do anything about it

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

-->

