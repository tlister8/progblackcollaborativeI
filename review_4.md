#Interest of Content
You have 2 decently sized pages talking about Healthcare & Education both of which detail interesting advancements using computers in their respective fields.The use of images and icons thorughout make it visually interesting, and the curved border and shadow underneath are a nice touch. 

Obviously, there are a few points where there is only "Lorem Ipsums", rather than actual content, but overall, it looks really good!

#Consistency and quality of visual presentation
All pages are visually consistent, clean and intuitive. Navigating the website it easy, and everything looks the same. The navigation abr updates to highlight which page you're on, and links highlight to confirm when you're hovering over them. I haven't seen any inconsistencies. 

The only issue I can see is that the main page has a "Page Author" section which, to me, doesn't make sense to be on a main page. I'd suggest changing this to a link to an "Authors" page, which lists all the authors that have contributed, and links to their respective articles.

#Validity of HTML
Your HTML seems to formatted consistently and too a good standard, making it very readable. You have comments clearing outline the different sections. 

You have however repeated your styling as a sort of "header" in every file. I would suggest extracting this out to an external .css file which you link to with a `<link rel="stylesheet" href="dist/style.css">`, rather than having to repeat this every file, and having to change every file whenever you want to make a style change.
The same goes for the navigation bar. Although fine for the current number of pages, it would be better to have this as it's on .html file that you reference at the top of every page.

#Evidence of collaboration
Each page has it's on Author footer, detailing who wrote it, and links to their github / LinkedIn. There is good evidence of collaboration.