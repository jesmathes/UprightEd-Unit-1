- Hello HTML!

- Objective
Learn about how to create your first HTML page.

– Learning
   In this lab, we    wil be learning    thebasics of HTM.    We will be focsing    on HTML semntic    tags and lin tags.    We will also    utilize Emmet    Abbreviations:    shortcut key    combinations that    autofill content for us. 
   
– Topics:

HTML
HTML semantic tags
HTML <a href> tag links
VSCode Emmet Abbreviations


- Achieving
In this lab, we will create a basic website using HTML. It will have a layout, placeholder content, and multiple pages connected by <a href> links.

- Your work will result in:

A website created with HTML.
A website laid out utilizing semantic div tags.
A website that has placeholder content.
A website that has multiple pages navigable by <a href> links.

- Procedure
Using the ! HTML Emet Abbreviation
 Inside of index.html, type ! and press Tab.
 This should create an empty HTML template for you to use.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
    
</body>
</html>
<!-- done -->


- Creating our HTML Layout:

Your tags to create this layout will live inside of the <body> tag pair. This is true for every website you build.

Your <title> tag should contain the name of the page. (Home, in this case).
In our website, we will need the following semantic div tags: <header>, <nav>, and <main>. Be sure to include their closing tag.

- Filling out placeholder content:

 <header> Should contain a title for the page.

 <nav>Should contain at least three<a href>s that will navigate to other pages on the site. Leave them blank for now.

 <main> Should contain placeholder text and <img>s.

To generate placeholder text in VSCode, type   lorem100 and push Enter. This will generate  100 words of placeholder text. You can change   100 to be whatever amount of words you want.   lorem5000 is also valid.

To access placeholder images, here are a few   options to try: Lorem Flickr, Placekitten.   Lorem Picsum.


- Creating multiple pages

 In the same directory as index.html, create another file named about.html

 In about.html, use the emet abbreviation again to generate the necessary HTML boiler plate.

 Inside of <body>, put in a <p> tag to inform us of which page we are on (About, in this case.)

 Create two more pages in the exact fashion you created about.html. These are your unique invention and should have unique names.

 Don't forget to change the <title> tag content to reflect which page the user is on.

- Linking to our new pages

 Back in index.html, return to the <a href>s in <nav>.
 For the first <a href>, point the link to /about.html. 
 Name this link "About".
 Fill out the other two <a href>s so that they correspond to the two additional pages that you created.


- Review
The software should:

Have a Home page the user lands on.

The home page should contain the <header>, <nav>, and <main> semantic divs filled out with placeholder content.

Have multiple pages that can all be navigated to via the links in <nav>.


- Going Further

Add <a href>s to your additional pages that allow the user to navigate back to the Home page.



Add different placeholder content to your additional pages. 

Utilize different semantic tags than those initially given.

Style your <a href>s to appear as buttons rather than links. 

You can research inline styles to do this. 
This will be bringing in CSS.

Style all of your semantic tags utilizing inline styles.


    <h1>Inline Element Examples </h1>
        <div class="inline-elements">
        <span>Span</span>
        <a href="#">anchor tags</a>
        <i>italics</i>
        <em>emphasis</em>
        <b>bold</b>
        <strong>strong</strong>
        <img src="#" alt="img tag">
        <button>buttons</button>
    </div>
