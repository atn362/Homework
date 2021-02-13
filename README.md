# Homework modifications for the Horiseon Homepage

I embarked on this task, in order to streamline some aspects of the code of this website, as well as reduce the redundancies that i found present in the css file.
The reason for doing this is to make the code as easy to read as possible.  The layout was much easier to understand, when I grouped many of the css elements together.
I was able to do this by assigning all class with the same values, to the same css code.  In doing so, it substantially shortened the length of the file, making it easier to comprehend and ammend. 
Most of the time and work was spent on stream lining the css files. Changes I made to the html include assigning the search-engine-optimization link an ID along with a class.  This way, the website relocated you to the topic once pressed.  Also assigned the site a title in the head of the html code, so that Horiseon Homepage was displayed in the internet tab, once you visited the site.  This was done by inserting a <title></title> command with the pages name inserted between the title tags. I think this gives the site a more professional appearance.  Lastly, I assigned the box, surrounding the search links, a fixed position. This allows for the links to be displayed no matter where you were to scroll on the site.  Again, i believe this gives the site a more professional appearance and makes it handy, having to not always scroll to the top. I enjoyed assignment, although I found it a bit intimidating at first.
What needed to be changed:
1. I made sure that all hyperlinks where properly linked to the desired id and class in order for them to relate you on the page properly, and to the desired paragraph.  I noticed initially, that the search engine hyperlink was not functioning properly.  This was due to the code being incomplete.  It was initially give the source for the proper class, yet not the id.  Once I input the source id, it was linked properly and redirected accordingly.
2. While looking over the css file, I notice that there were many redundancies which we unnecessary and made the code much more long handed than needed.  I noticed a number of elements shared the same properties and values.  After deciphering which ones shared identical properties, I strung the likened classes and ids together so there was only one line of elements that shared the same properties and values.  This cut the entire length of the css code down by about a third, and guaranties all classes and ids will share a uniform aesthetic once launched in a browser.
3. Utilized the alt description of images, in accordance to ARIA standards.  No image prior shared any alternative description prior.  This will certainly make the accessibility of this site to the seeing impaired far greater.  With alt descriptions give, screen readers are able to give verbal descriptions of images to blind and seeing impaired people. 
4. Tried my best to simplify the code by adding a proper footer, since the element and values were present in the css, yet not in the html file itself.  This gives a more professional appearance and makes the code easier to change in the future.
