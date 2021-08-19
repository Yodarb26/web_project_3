Hello Samir! Thanks for the corrections, they look good, the scroll is almost gone! However, I have to reject the work without a review again, because:

    1) Not all files are organized according to BEM principles (blocks are nested in folders at the folder level, elements and modifiers are not nested in blocks, etc.). Please, take a closer look to how your place block is located in the file structure.

    2) The page scrolls horizontally on desktop resolutions. There's a horizontal scroll on 1024 and smaller.
    Five or more text elements have a fixed height. Please, remove height and max-height from all text elements and big content blocks. Sections with a background image (cover) can have min-height assigned.

What else can be corrected before the first iteration:

    3) intro section doesn't look like in the design. Please, check the font parameters (font-size, line-height) for the text elements inside it, and note that according to the design the content should have limited width.

    4) There are some code alignment violations in html. Please, make the necessary indents. If you use VS Code, you can format your code automatically: https://code.visualstudio.com/docs/editor/codebasics#_formatting Or, you can use online formatters like https://webformatter.com/html
    There should be a link in cover section, href value is specified in figma. Please, note that this link should occupy the whole section.-------------> Don't agree as I've used https://webformatter.com/html to formate it before submititng my code 

Please, note that you don't spend an iteration when the project is rejected without a review.



# Project 3: From Portland to Portland

### Overview
* Intro
* Figma
* Images

**Intro**

This is a project about traveling across the US. We've made it so all the elements are displayed correctly on popular screen sizes. We recommend investing more time in completing this project, since it's more difficult than previous ones.

**Figma**

* [Link to the project on Figma](https://www.figma.com/file/AtbNbstbxWPcMqvF061V0R/Sprint-3%3A-From-Portland-to-Portland-%7C-desktop-%2B-mobile?node-id=0%3A1)

**Images**

The way you'll do this at work is by exporting images directly from Figma — we recommend doing that to practice more. Don't forget to optimize them [here](https://tinypng.com/), so your project loads faster. 

**Github**

* [Link to the project on Github] https://github.com/Yodarb26/web_project_3.git


Good luck and have fun!

--------------------------------------------------------------------------------------------------------------------------------------------

This is the 3rd Sprint and get ready for the most challenging so far:


It consists on builiding a webpage based on Figmas's designer visual example and contains:

-Blocks with several sections
-Images
-Custom fonts
-Visual styling 

-It's built with HTML and CSS only
-BEM is the norm for writing code good practice.