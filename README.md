Horiseon code refactor


Methodology

This code refactor aimed to clean up the source code and improve accessibility. Web accessibility finds itself at the crossroads of web content, user agents, and authoring tools. These components inter-relate and support each other, and as websites become more sophisticated so too do accessibility concerns. My essential principles were to reorganize the html and add semantic elements, asign image alt attributes, offer keyboard accessibility, text to speech and vise versa. 

My first step was to reformat the HTML for legibility purposes, once that was complete I replaced all div sections with more appropriate semantic and created a concise title. There were 5 main div sections using class tags: header, hero, benefits, content, and footer. Header and footer were simply renamed without the div, the other three were a bit more involved. I think I might have left hero as it was, but in following along with the rest of the html I decided to make it a figure to keep the img in the html (the figure may not be necessary but for organizatoinal reasons I've kept it). The content section became main and the benefits aside, and the children div became section.

Once that was done, simplifying the CSS became possible, as the number of classes and ids was greatly reduced. The final product matches the original in the browser, except that the semantic elements now function to accessibility standards.


Collaborators

Tim Winters





