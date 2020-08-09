# code-refractor

An exercise in code refactoring, the task was to amend the html and css files of a website in order to make it function properly and also to leave the code in a friendlier state for future developers by leaving comments and organizing the code so that elements appear in the code as they appear on the web page.

# Changes That Were Made

-Changed the title in the head of the html so that a concise title of the website appears in the tab of the page in the browser, the title was changed so that the page could be found more easily by search engines.

-Made the links at the top of the page function correctly.

-The page was made up of div's and so I turned each div element into more semantically meaningful elements such as header, nav, figure, main, aside and footer.

-The div's were all given class names that were referenced in the style.css file. I removed all the class names and made the style.css file reference the semantic elements of the page for easier viewing.

-Alot of the classes in style.css contained the same information for the same type of elements in index.html and so I consolidated the classes and turned them into element references.

-The main image of the page did not have an alt attribute and the image url was referenced in the style.cc file. I deleted the reference to the image file in style.css and created an img element in the new figure element and referenced the image url there and added an alt attribute.

-The original html and css files had no comments and so I added comments to the code that indicate where the different sections and elements of the page begin and end. I also added comments to style.css to show which parts of the page the different the css code affects.

-The code in the original html and css files were not wuite in the correct order as displayed on the page and so I re-arrange the code in the html and css files.