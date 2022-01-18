# web_HTML
==========
Daily exercise, finish all tasks today 

Exercise One &ndash; Linking to external pages
----------

Using your IDE, explore the ```ictgradschool/web/lab02/ex01``` folder.

In each of the three HTML files that can be found in the directory, there are a number of unformatted URLs in the text. Modify these such that they are shown as clickable hyperlinks that link to the indicated URL, with the text of the hyperlink indicating the page or page section they are linking to, and the title attribute of the anchor describing the linked page.

In addition, identify 10 words that you are unfamiliar with in the text, and link those words to the appropriate [Cambridge Dictionary](https://dictionary.cambridge.org/) entry.

Exercise Two &ndash; Including local images
----------

Using your IDE, open the ```ictgradschool/web/lab02/ex02``` folder, then create a new HTML file called ```banknotes.html``` within it. In the body of this document, include the four images from the ```ictgradschool/web/lab02/ex02``` folder using the ```<img>``` tag.

Manipulate the images that you have included in the page so that they have the same width on the page.

Exercise Three &ndash; Including remote images
----------

Make a copy of the files in the ```ictgradschool/web/lab02/ex01``` folder and place them in the ```ictgradschool/web/lab02/ex03``` folder. You may need to create this folder yourself.

For each of the three HTML files that can be found in the directory, locate an image __not__ from Wikipedia that relates to the content of the file. Insert these images into the appropriate documents, linking the images directly to the source (Do not download the images to your computer).

Modify your images such that if they are clicked, the browser will open the homepage of the website the image was obtained from.

Exercise Four &ndash; Using multimedia
----------

Make a copy of the files in the ```ictgradschool/web/lab02/ex03``` folder and place them in the ```ictgradschool/web/lab02/ex04``` folder. You may need to create this folder yourself. 
 
Open the ```potassium.html``` file and insert a ```<video>``` element at the bottom of the "Potassium" section of the document. Inside this element, add a ```<source>``` element linking to <https://upload.wikimedia.org/wikipedia/commons/4/43/Potassium_water_20.theora.ogv>, and another within the same ```<video>``` element linking to <http://download.blender.org/peach/bigbuckbunny_movies/BigBuckBunny_320x180.mp4>. When adding your ```<source>``` elements, remember to set the type attributes to the appropriate MIME type.

Ensure that your video can be played in at least one browser, and that you can start and stop the video at will.

Open this file in both Internet Explorer and Google Chrome.
- Which video/s play in Internet Explorer?
- Which video/s play in Google Chrome?
- What happens if you switch the position of the ```<source>``` elements within the ```<video>``` tag?

Type your answers to the above questions in the space below.

```

Type your answer here

```

Exercise Five &ndash; Relative URLs
----------

Make a copy of the files in the ```ictgradschool/web/lab02/ex04``` folder and place them in the ```ictgradschool/web/lab02/ex05``` folder. You may need to create this folder yourself. 

Open the ```edmund_hillary.html``` file and insert a ```<video>``` element above the "After Everest" section of the document. Inside this element, add two ```<source>``` elements linking to each of the two ```edmund_hillary_climbs_everest``` files located in the ```ictgradschool/web/lab02/assets``` folder. **DO NOT COPY OR MOVE THESE FILES**. When adding your ```<source>``` elements, remember to set the type attributes to the appropriate MIME type.

Add a message to your ```<video>``` element that will appear if the video can not be displayed that indicates there was a problem with the video playback.

Ensure that your video can be played in at least one browser, and that you can start and stop the video at will.

Exercise Six &ndash; In-page navigation
----------

Make a copy of the files in the ```ictgradschool/web/lab02/ex05``` folder and place them in the ```ictgradschool/web/lab02/ex06``` folder. You may need to create this folder yourself. 

In each of the three HTML files that can be found in the ```ex06``` directory, you will create an index for the document that links to different sections within the document.

Create a list at the end of the first section of each document that contains links to each header element (h1, h2, etc) within the document. When one of these links is clicked, the browser should (try to) scroll down to the linked section. 

**NOTE:** To accomplish this, you will need to set the id attribute on the tags you wish to link to, but remember that ids must be unique.

Further modify your HTML files to add "Return to top" links near each section that returns the browser to the top of the page when clicked.
 

Exercise Seven &ndash; Cross-page navigation
----------

Make a copy of the files in the ```ictgradschool/web/lab02/ex06``` folder and place them in the ```ictgradschool/web/lab02/ex07``` folder. You may need to create this folder yourself. 

When we begin to create a website with multiple pages, it is often desirable to be able to navigate easily between them. To accomplish this, you will create a simple navigation block for each of your webpages. 

Create an unordered list at the top of each document that contains links to each of the HTML pages in the folder. When one of these links is clicked, the browser should open the appropriate page. Ensure that this navigation block is functioning correctly by following the links from each page, confirming that you have arrived on the appropriate page after each click.
 

Exercise Eight &ndash; Reusing navigation
----------

Make another copy of the files in the ```ictgradschool/web/lab02/ex06``` folder and place them in the ```ictgradschool/web/lab02/ex08``` folder. You may need to create this folder yourself. 

Starting again from the ```ex06``` base, you are now going to simplify your navigation block by creating it in a separate file and displaying it in each of the other HTML files. 

Create a new HTML file ```navigation.html``` in the ```ictgradschool/web/lab02/ex08``` folder, then recreate your navigation block in the body of this new file. Now in each of the main HTML files, use an ```iframe``` to embed the ```navigation.html``` file at the top of each page. Tweak the attributes of the iframe until it looks as close as possible to the result seen in exercise seven.
 

Exercise Nine &ndash; Displaying 3rd party pages
----------

Create the ```ictgradschool/web/lab02/ex09``` folder, and create a new HTML file called ```youtube.html``` within it. Open the file and insert 5 paragraphs of lorem ipsum text copied [from here](http://lipsum.com/feed/html) into the body of your document.
 
Locate a video of your choice on YouTube, and embed it into your page between the second and third paragraphs of text. YouTube does its best to make this as easy as possible for you, as they want you to be able to include content in your web pages that helps hook the people visiting your site into then visiting their site: right-click on the video at YouTube to see the options available, or look for the “share” option underneath a video. 

Modify the code given to you by YouTube so that the video cannot be put into fullscreen, and set its dimensions to 1024x768.

Exercise Ten &ndash; Constructing a form
----------

Create the ```ictgradschool/web/lab02/ex10``` folder, and create a new HTML file called ```form.html``` within it. Open the file, and recreate the following form within it.

![](./spec/ex10-screenshot.png)

Ensure you give sensible names and values to all of the inputs. Add the submit button (labelled "Done!" in the screenshot) and the reset button, labelled "Clear".

Exercise Eleven &ndash; Submitting form data
----------

Create the ```ictgradschool/web/lab02/ex11``` folder, and copy the ```form.html``` file from the ```ictgradschool/web/lab02/ex10``` folder.
 
Modify your form so that when the "Submit" button is pressed, the data is submitted to the application located at the <https://trex-sandwich.com/echo/> address.

Preview your form and try submitting it.
- What is shown to you after submitting the page?
- What happens if you change the method of of your form?
