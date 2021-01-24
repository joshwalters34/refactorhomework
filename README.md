# refactorhomework

changes I made to refactor the code
- gave the site a title
- updated class="header" to a header tag
- updated class="footer" to a footer tag
- changed class of seo to an id since it's one of a kind
- updated the span in the main header to include the color change, rather than create a class.  Also removed the seo class from the css
-  in CSS document I took out "header" before h1 tag
- in CSS document I took out "header" & "h1" before .seo tag
- in CSS document I took out "header" & "div" before ul tag
- in CSS document I took out "header", "div", & "ul" before li tag
- removed the header div section in the css and added the styling to ul and removed teh div tags within the header
- changed the div with class name of hero to an image tag with id of hero, since img tag makes more sense.  And I changed to an id because this is the only image using this style
- added alt description for the images
- cleaned up the image tags for the images in right sidebar
- took out the individual classes for each of the 3 sections under content and created 1 class for all
- did the same thing for the images within each section, they had unique classes and I combined them into 1 class
the changes I made impacted the header, so I changed the header, ul, and li tags to be flex boxes and added a few things to get the look the same.
- in the Benefits section, I created one class for each section and each image since they all 3 share the same attributes
- changed the h3 tags in the benefit section to just be h3, and not mention the benefits class.  ANd I only left 1 there, since they're all the same
- did the same with the h2 tags, except I left the footer h2 tag since it's different
- added anchors to the top menu to take me to the appropriate section on the page

CSS document organizatin
- I went with main styles first
- Then added header and footer
- Then h tags, p tags, and other tags that are the same throught the file
- Lastly I added class and id tags, putting them in an order that matches their order in the html