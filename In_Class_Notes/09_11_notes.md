# Notes for class on Monday 09/11/23

## HTML Files
- Declare the doctype for the file
- Declare the language within the HTML tag lang='en'
- Head and Body tags live inside the HTML tag
    - Head tag is the metadata as well as any script that is included 
    - charset = "utf-8" tells the computer what the characters and fonts to load and expect without this there may be malformed characters
    - viewport metatag is required for responsive rendering and requires the content = divice width and initial scale of 1
    - the title tag is the name of the document and you should always have a title. Its also the first thing you see as a google search result and its also the title that you see in the browser tab
    - name = "description" content="this is a description tag and will show up as the text under the title in a google search"
    - name = "keywords"  content = "html, css, tutorial" basically hashtags for google to help pull up related content
    - name = "author" content = "Your name here"
    - All metadata is invisible until a google search and meta data is basically data about the file and all goes in the head tag
- All the stuff you see on the screen goes inside the body tag
    - Without the css the files are just the standard design 
    - There should only ever be one h1 per page 
    - **Think Heirarchy**
    - There is h1 through h6 for headings 
    - <em> is the emphasis tag and its the italise 
    - <strong> is the bold 
    - always remember to close your tags 
    - There are some tags that are self closing like br, hr and img
        - hr is horizontal rule 
        - br is the break 
    - You can change the way that the bullets and ordered list items look is with css later 123 and bullet points is the default 
    - Nav bars are unordered lists 
    - Lists are nestable 
    - Linking to external pages and websites as well as other areas by id on our page 
        - a href="www.linklinklink.com" target="_blank"
        - target is opening to a new page or the same page _blank is new page and self is the same window 
        - the text in between the tags is the description text for the link 
        - anchor tags are inline so to have them on new lines you can use a br tag or you can put the links in some sort of unordered link 
        - Buttons like "jump to recipe" is just a link within the page to the id of a location 
            - You can have the same class all over the place but each id must be unique 
    - Loading images from the browser using the img tag
        - The size will automatically load at whatever size it is and while you **can** change it in html you really shouldnt 
- Google developer tools are our friends :) Please use the inspect option on chrome 

## HTML Forms 

- W3 schools is the best for troubleshooting anything dealing with HTML CSS and Javascript 
- Forms require an action, name, target, and method
    - The method is either get or post 
        - When you use the get method you can see all of the information within the browser querety link so its probably not the best for when the form is collecting things like passwords 
    - You can put anything you want inside the form 
    - Field sets are just groups in like fancy box and basically anything you put in the legend will be the title of the box
    - You want to name every field inside of your form that way you can grab the input of the set
    - You can limit the input's character length and add labels with attributes 
    - Lables are important for accessibility and mobility on the site 
    - Everything has a type except for text areas and dropdowns 
    - The name in the form and the for in the label must be the same in order for them to be connected 
    - Text areas 
        - resizable 
        - cols is how many characters wide and rows is how many characters tall 
    - Check boxes allow the user to select more than one value at a time
    - Radio boxes only allow you to select one value at a time 
    - The text after an input is just simply a label for the user
    - Selected attribute gives the default answer in a dropdown
    - Disabled is an attribute that can be used to disable a button and it can be conditional if you want the submit to only be available if the inputs are all filled out 



