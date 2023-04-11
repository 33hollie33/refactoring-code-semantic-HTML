# Query: README.md
# ContextLines: 1

## Challenges in this course
This challenge presented with non-semantic HTML  to semantic HTML of the website. However not wanting to change the design or content of the webiste.
The client wanted to make the website more accessible to a wider audience to meet the accessibility standards. 

HTML:
Issues:
*Non-semantic HTML. This lead to the overuse of the 'div' tag. 
*The client wanted to have a codebase that included accessibility standards
*The website does not state the companies name when in a browser
*The links do not work to navigate different sections of the webpage.

Solution:
*Changed the div tags to more semantic tags the tags I used in this code are: nav, main, header, aside, section, footer. This was dependant on the content.
*Added the 'alt' tag to follow the img tag. 
*Changed the title to the companies name so it can appear on the tab banner. This makes it look more professional.
*Added a 'id'class to the img element, allowing the links to function on the website. 

CSS:
Issues:
*The CSS code was not completely compatible with the HTML after adjusting the div tags to semantic HTML tags. Thus, changing the look of the website. 
*The CSS code is long as there has been a unique class given to certain components that have the same styling. This can make the code harder to navigate for other devlopers and is unnessary. 

Solution:
*Changed the div tags in the CSS to the nav tags so it is compatibale and follows through with the design of the website.
*I was able to combine some of the CSS code to make it more conscise and a clean. This makes it easier to navigate for other developers. For examle, I was able to
combine the "img" as it had the same style another example was "online-reputation-management", "online-reputation-management" and "social-media-marketing", they were
previously all in an unique class despite having the same style components. By combining these classes together it makes it easier for other developers to navigate and makes the code look more conscise.  


The previous HTML was in a non-semantic format. By adjusting and using semantic elements of HTML. By changing to semantic HTML it optimises search engines.
This is because screen readers and browsers can interpret semantic HTML more easily. This makes the website more accessible.
In addition it makes the code more clear and conscise, this allows other coders to navigate the code better and makes it more maintainable.
The 'alt' attribute being applied to the img tag provides a text alternative; it describes the appearance of the images,
this allows the content of the website to be more accessible to the visually impaired. This is apart of the accessibility standards.
As expected, when altering some of the 'div' tags in the HTML, it then made it incompaitable with some of the CSS code. Thus changing the design of the website,
which is not what the client wanted. After altering the HTML, the CSS had to be altered to the correct tags. 
The main issues with the CSS code is that it was uncessarily long. There was some unique classes given to certain compnenets. Despite the code working effectively, a main issue
for long CSS code is that the design could break. Another issue is that it makes it more difficult for other devlopers to navigate the code. By combining certain elements 
it has made the code more conscise and easier to navigate. Please refer to the printscreen below. 

![screenshot of website](/assets/images/screencapture-file-Users-holly-Desktop-Bootcamp-student-01-HTML-Git-CSS-02-Challenge-Develop-week-1-refactoring-code-challenge-index-html-2023-04-06-19_46_01.png)