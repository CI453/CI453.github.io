<!doctype html><!--HTML5 doctype declaration -->

<html lang="en"><!--default language of the document content -->


    <head><meta http-equiv="Content-Type" content="text/html; charset=utf-8">
		<!--character encoding for the document (Unicode) -->
		<title>  Learning Journal template</title><!--web page title -->
		
		<meta name="viewport" content="width=device-width, initial-scale=1">
		
		<link href="css/normalize.css" rel="stylesheet">
		<link href="css/stylesheet.css" rel="stylesheet">
		
		
		
	</head>
	
	
	


<body>
    

    
    <a id="top"></a>
        <!-- This is code used from https://www.w3schools.com/howto/default.asp -->
     	<div class="topnav"> 
  <a class="active" href="#home">Learning Journal</a>
  <a href="tutorial.html"> Tutorial</a>
  <a href="contact.html"> Contact me</a>
</div>




<div class="dropdown" style="float:right;">
    
  <button class="dropbtn">Week Selection </button>
  
  <div class="dropdown-content">
  <a href="#w1">Week 1</a>
  <a href="#w2">Week 2</a>
  <a href="#w3">Week 3</a>
  <a href="#w4">Week 4</a>
  <a href="#w5">Week 5</a>
  <a href="#w6">Week 6</a>
  <a href="#w7">Week 7</a>
  <a href="#w8">Week 8</a>
  <a href="#w9">Week 9</a>
  </div>
</div>

    
    	<div id="wrapper">
   
     
 
<!--Markup all web page content inside the 'body' tags -->

	<!--The 'wrapper' contains all the page content-->
	
    <header class = "banner"><!--The main heading for the page -->
		<h1> Semester 1 Learning Journal</h1>
		<h2> Assessed Coursework</h2>
	</header>
	
	
	<figure>
<img src="images/wallpaper.jpg" alt = ""/> 


</figure>
      
      <table>
  <tr>
    <th>Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
  </tr>
  <tr>
    <td>9:00-10:00</td>
    <td>Cyber Security (Lecture) (CI404)</td>
    <td>Free Period</td>
  </tr>
  <tr>
    <td>10:00-11:00</td>
    <td>Cyber Security (Lecture) (CI404)</td>
    <td>Programming for business (Lecture) (CI418)</td>
</tr>
  <tr>
       <td>11:00-12:00</td>
    <td>Free period</td>
    <td>Programming for business (Lab) (CI418)</td> 
    </tr>
  <tr>
       <td>12:00-13:00</td>
    <td>Free period</td>
    <td>Free period</td> 
    </tr>
  <tr>
       <td>13:00-14:00</td>
    <td>Free period</td>
    <td>Web Development (Lecture) (CI435)</td> 
       </tr>
  <tr>
       <td>14:00-15:00</td>
    <td>Working in Computing Industry (Lecture) (CI453)</td>
    <td>Cyber Security (Lab) (CI404)</td> 
       </tr>
  <tr>
       <td>15:00-16:00</td>
    <td>Databases/Computing Technologies (Lecture) (CI402/CI405)</td>
    <td>Cyber Security (Lab) (CI404) </td> 
       </tr>
  <tr>
       <td>16:00-17:00</td>
    <td>Databases (Lab) (CI402)</td>
    <td>Web Development (Lab) (CI435) </td> 
  
</table>
        

        	<h2>Weekly Posts</h2>
        	
        	
        	<a id="w9"></a>

<header>
			<h3>Week 9 - CSS3 Responsive Layout </h3>
				<p>Published on <time datetime="2019-11-25">November 25, 2019</time></p>
</header>
			
		
			    
			<article>
			    
			    <p> In the final tutorial, Week 9, we are taught how to implement a form into our website in order to receive feedback from our users, much like every profressional website does.
			        </p>

            	<div class="fltlt">
   		
   		
    		<img src="images/Form1.PNG" alt="">
		</div>
    		<p>As you can see in this image here, I had to create a new from in the contact page html. For each piece of data that I wanted, I had to create a new label for, as you can see by 'Name', 'Email address' and 'Website URL'. As well as this, I had to ensure that the wbesite recognised the users input as text.</p>

		<p class="clear"></p>
		
		
		
		  <div class="fltrt">
   		
   		
    		<img src="images/Form2.PNG" width = "600" alt="">
		</div>
    		<p>After creating the form I moved on to the next step which was creating a 'textarea', a place in which users can leave any extra comments/thoughts they may have. This was relatively simple as you just simply declare where exactly you want the textarea, in this case, below the detail submission form.</p>
    		
    		<blockquote>
		    <p> On top of this I also edited the CSS of the from to ensure it was in the same style as the rest of my website, hence the colour of the borders/text etc.</p>
		    </blockquote>

		<p class="clear"></p>
		
		
		
        <div class="fltlt">
   		
   		
    		<img src="images/Form3.PNG" height = "350" width = "600" alt="">
		</div>
    		<p> The last thing I added to the contact page was something called a Radio Group, which consists of two or more buttons, of which the user can only pick one to input. To ensure the buttons work, it is essential they are both associated with a group in which the name values are identical. In this case it is a simple case of the user ticking yes or no.</p>
    		
    		<blockquote>
		    <p> As you can see in the image to the left, I changed the CSS of the 'submit'/'send' buttons in order to ensure they stand out as much as possible to the user. I have also ensure the borders around each section are clear so the user can clearly see what information they are inputting.</p>
		    </blockquote>

		<p class="clear"></p>

		
		

			</article>
			
		<a id="w8"></a>


<header>
			<h3>Week 8 - CSS3 Responsive Layout </h3>
				<p>Published on <time datetime="2019-11-18">November 18, 2019</time></p>
			</header>


<article>
    <p> Like week 7, week 8 focuses on certain aspects of CSS that would be better learnt when starting from a fresh template, as well as the fact it could change the whole website drastically so it would best to understand it from a fresh perspective, as opposed to trying to implement it immediately into the website.</p>
    
    <blockquote>
        
<ol>
    <li>Flexbox layout:
  	<ul>
    		<li> The CSS flexbox layout is used to give images flexible 'cardlike' properties. When using the correct CSS code the 'cards' would be laid out in a set number of flexbox columns. This format would be useful for displaying a tutorial page as it would allow the steps to be laid out in a neat, ordered fashion that would aid the understanding of the reader.</li>

	</ul>
    </li>
    
    
    
    <li>Multi-Column Layout:
  	     <ul>
    		<li>The multi-column layout is fairly self explanatory in the sense that it displays the information in a column on a small screen but with a wider display it transforms that single column into multiple columns to make the information easier to read.</li>
  	    </ul>
   </li>
</ol>
   
        
        </blockquote>
    
    
</article>

<a id="w7"></a>

<header>
			<h3>Week 7 -Flexible Media </h3>
				<p>Published on <time datetime="2019-11-11">November 11, 2019</time></p>
			</header>

<article>
    
    <p> In order to get a better grasp on what is being taught within week 7 we were instructed to make a separate html document in order to test what we were learning without causing damage to our actual project.</p>
    
    <blockquote>
    
    <ol>

            
        <li>
            <p> To begin with, I embedded an image of my choosing into the test page with a set height and width to see how it behaved when the viewport was resized and as expected, it did not change size in accordance with the size of the window.</p>
             </li>
             
             
      <li>
            <p>The next step was to make the embedded image flexible, starting by removing the set height and width values. This was done by altering the code that embeds the image so that it changes the properties of the image as well, this code can be seen here:</p>
            
             <figure>
                <img src="images/embedFlex.PNG" alt = ""/> 
                <figcaption><br />
                </figcaption>
                </figure>
                
                <p> After saving the changes the provided by this code, the embedded image now resizes to scale with the browser as opposed to staying the same size, as seen below: </p>
                
               <iframe src="https://giphy.com/embed/WOHzSNIZsCO9tXyBa7" width="480" height="270" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/WOHzSNIZsCO9tXyBa7">via GIPHY</a></p>
            
     </li>
     
<li>     
     <p> Once finishing with the embedded image I moved onto embedding videos into my website, as inlcuding videos I use for independent study would be a valuable addition to my learning journal. This was relatively simple in the sense that YouTube gives the necessary embedding code for whichever  video you are watching, so it is a simple matter of copying it into the html. The video below is an example that specifically relates to this weeks task of embedding, so I thought it would be appropriate to leave it here:  </p>
     
     <iframe width="560" height="315" src="https://www.youtube.com/embed/OOy764mDtiA"  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
     
     </li>
     
   
</ol>
     </blockquote>
    
 
    
</article>



<a id="w6"></a>
<header>
			<h3>Week 6 - Changing the styling of the website's CSS </h3>
				<p>Published on <time datetime="2019-11-04">November 04, 2019</time></p>
			</header>
<article>  
<p> The main objective of this week was to ensure that the website can be displayed correctly/ in an adequate formate, depending on the devicce eing used to view the website.</p>

<blockquote> <p>First of all, I had to ensure the website displayed correctly on mobile devices in both portrait and landscape orientations. The first step of this was to implement a command in the HTML that ensures mobile device browsers behave like regular desktop browsers when displaying this website.</p>
 <p> This, as well as a few minor adjustments to certain pieces of HTML, means that the website adapts to the necessary device conditions in order to ensure the best end user experience.</p>

</blockquote>

<p> One problem I had encountered up until this stage was the resizing of images in certain browsers. For example, images on this website wouldn't change size depending on the window size, resulting in an unpleasant looking page. This was the same when viewing on different devices, especially apparent on mobile devices. </p>

<blockquote>
    This has now been solved as this weeks tutorial taught me how to change the images dimensions based on the size of the browser. This was done by setting a max width for the images in the sites stylesheet, which ensures that every image is affected by it, due to the stylesheet applying to the whole page. As you can see below there is a before and after comparison in which the image resizes itself after the new code is applied.


<div class="row">
  <div class="column">
    <img src="images/miniWindowStretch.PNG" alt = ""/> 
  </div>
  <div class="column">
    <img src="images/miniWindow.PNG" alt = ""/> 
  </div>
  </div>
    		    
</blockquote>

</article>

<a id="w5"></a>


<header>
			<h3>Week 5 - Changing the styling of the website's CSS </h3>
				<p>Published on <time datetime="2019-10-28">October 28, 2019</time></p>
			</header>
			


           
 <article>
    
    
    <p class = "dropcap"> In terms of adding lots of content to the website, week 5 is a bit lackluster, however it explains how to customise the font and the layout of the website based on certain conditions the user may have.<p> 
    
        <blockquote>
        <p>
            For example, some users may not have certain fonts stored on their computer so the websites font will not display correctly to them. This can be solved by using an online font library that is accessible to anyone using a browser, that way the font displays correctly every time </p>
        </blockquote>
   
        </article>




<a id="w4"></a>


<header>
			<h3>Week 4 - Setting up CSS stylesheet </h3>
				<p>Published on <time datetime="2019-10-21">October 21, 2019</time></p>
			</header>
     
 <article>
    
    
    <p class = "dropcap"> In order to establish a foundation for the websites CSS stylesheet, I had to first create another stylesheet called 'normalize.css'. This had too be used because this style sheet makes browsers render all the websites elements more consistently and ensures they in line with modern web design standards.</p>
    <blockquote>
        <p>
            It is CRUCIAL that once completed this style sheet is left alone and is not edited in any way shape or from, which is why a second CSS stylesheet is required for the websites aesthetics.
        </p>
        </blockquote>
    
    <p> After creating the 'normalize.css' stylesheet it's time to create the websites actual stylesheet. This was done by creating a textfile and using the basic CSS template provided by the tutorial.  </p>

    <p> Once this was done the stylesheet had to be linked to every page on the website. This is to ensure the website has a consistent design/theme all thorughout, otherwise each page would look much different.</p>
    
     <blockquote>
        <p>
            This is done by going to the head section of each web page and linking the stylesheet to each one, as shown in the image below:
        </p>
        

           

<img src="images/StylesheetLink.png" alt = ""/> 


        </blockquote>
   

<p> From there I had to edit the 'selectors' which are sections within the stylesheet that correlate to certain aspects of the website. By editing the properties within the selectors the websites design can be changed depending on what you choose to edit/implement within the selectors.</p>

    <blockquote>
        <p>
           For example, if you were to edit the 'background-color' property in the body selector, it would change the colour of the pages background depending on the hexadecimal color code you assign to it. In this case I used '#343434' and as you can see, the background colour is grey.
        </p>
        </blockquote>
        

  <P>As you can see throughout the website I have changed the styles of various selectors, such as changing the 'header' selector to ensure all of the titles are of the same colour and font.
        </P>
        
  <P>One of the more significant selectors was the 'wrapper' selector as that enabled me to create a section in the middle of the page for the websites content, as well as providing it with a margin and a border to create a professional looking website. The code for this is as shown below:
        </P>
        
        <figure>
<img src="images/Wrapper.PNG" alt = ""/> 
<figcaption><br />
</figcaption>
</figure>
        
        
        </article>

<a id="w3"></a>


<header>
			<h3>Week 3 - HTML document structure and hypertext (adding more HTML Markup) </h3>
				<p>Published on <time datetime="2019-10-14">October 14, 2019</time></p>
			</header>

<article>
    
    <dl>
  <dt><strong>HTML</strong></dt>
    <dd>Hyper-text markup language - markup language used to structure content</dd>
  <dt><strong>CSS</strong></dt>
    <dd>Cascading stylesheets - used to define presentation of HTML elements</dd>
  <dt><strong>JavaScript</strong></dt>
    <dd>Scripting language for adding interactive behaviour to web pages</dd>
</dl>




<p class = "dropcap"> A goal for Week 3 was to create a more intricate list by making a list within another list, thus making something called a 'Nested List'</p>

<blockquote>
<p>
    For example, a nested list could contain one list of food categories and then, by creating a nested list, you could see examples of those food categories, as shown in the nested list below where each item in the original list has its own accompanying list.
</p>

<ol>
    <li>Fruits
  	<ul>
    		<li>Apple</li>
   	    	<li>Orange</li>
    		<li>Banana</li>
    		<li>Strawberry</li>
	</ul>
    </li>
    <li>Vegetables
  	<ul>
    		<li>Broccoli</li>
    		<li>Carrot</li>
    		<li>Parsnip</li>
    		<li>Lettuce</li>
  	</ul>
   </li>
   <li>Meats
  	<ul>
    		<li>Pork</li>
   	    	<li>Beef</li>
    		<li>Chicken</li>
    		<li>Fish</li>
	</ul>
    </li>
</ol>

</blockquote>
<p> One of the skills Week 3 taught me was how to create a table, alter the layout of the table as well as showing me howw to input data within tables. For my website, I used this to create a table that shows my weekly timetable this semester. This is done by declaring the attributes of the table, such as the border and the desired columns/rows. From there, I was able to add information to my cells by marking up the desired contents and nesting them within the table's rows using the 'tr' tags, as shown in the screenshot below.
</p>

<img src="images/TableScreenshot.JPG" alt = ""/> 

    
    <p> After successfully implementing anchors and lists the next thing to learn was importing images into the website in order to show how I am writing the HTML/ organising the files. <br> This is done by saving images into the aptly named 'image' folder in the websites directory. Once the image is saved into that file I needed to use the code seen below to tell the website where to access the image, as well as give it instructions on how I want to be displayed.</p>


<p>The W3C defines HTML and CSS as follows:</p>

<blockquote>

<p>HTML (the Hypertext Markup Language) and CSS (Cascading Style Sheets) are two of the core technologies for building Web pages. HTML provides the structure of the page, CSS the (visual) layout, for a variety of devices. Along with graphics and scripting, HTML and CSS are the basis of building Web pages...<p>

<footer>

<cite>
<a href="http://www.w3.org/standards/webdesign/htmlcss">W3C standards for web design</a>
</cite>

</footer>



<p>In the first 3 lab tutorials I learned some of the most frequently used HTML tags and how to use them to structure text in a web page.</p>

<p> I also conducted some independent research in order to solidify my knowledge when it comes to implementing hyperlinks, this can be found within the following hyperlink: </p>


<cite>
<a href="https://www.w3schools.com/html/html_links.asp">W3C guide on implementing hyper links</a>
</cite>

</blockquote>

</article>

<a id="w2"></a>

<header>
			<h3>Week 2 - Using web tools such as Lists, Anchors and Email links </h3>
				<p>Published on <time datetime="2019-10-07">October 7, 2019</time></p>
			</header>
			


           
 <article>
    
    
    <p class = "dropcap"> This week was primarily focussed on adding content to the index page that was set up last week. <br>This included adding a list into the first week post which, as seen below, was used to describe the steps taken to develop the websites template.</p>
    
    <p> As well as creating my first list, I also implemented something called an anchor, which allows me to create links within the page itself, thus making it easier to navigate. <br> For example, at the botom of the page is an anchor that allows the user to navigate to the top of the page immediately upon clicking it. </p>
    
    <p> After successfully implementing anchors and lists the next thing to learn was importing images into the website in order to show how I am writing the HTML/ organising the files. <br> This is done by saving images into the aptly named 'image' folder in the websites directory. Once the image is saved into that file I needed to use the code seen below to tell the website where to access the image, as well as give it instructions on how I want to be displayed.</p>
   

<img src="images/ImageHTMLScreenshot.jpg" alt = ""/> 


<p> Once all of this was done I added an email link to the bottom of the page in order to add some authenticity to the website, as most websites have a 'Contact us' section on them.</p>


  <P>Admittedly there were a few issues with attempting to size/resize the images but this was solved fairly easily by simply adjusting the height and width properties of the images in question.
        </P>
        
        </article>



			<header>
			    
			    <a id="w1"></a>
			    
			<h3>Week 1 - Starting off </h3>
				<p>Published on <time datetime="2019-10-01">October 1, 2019</time></p>
			</header>
			
<article>

<p>  The first lab tutorial has shown me how to develop the bare bones of a website. 
In this tutorial I learned about the key components of a website, listed below -


           
   
    


<figure>
<img src="images/FileScreenshot.JPG" alt = ""/> 
<figcaption>View of the folders within the website<br />
</figcaption>
</figure>

<ol>
<li>Seting up a folder for my website on my Brighton Domains workspace</li>

<li>Linking three pages together with a navigation menu using a relative link, dictated by me within each of the pages code. </li>
<li>Using absolute links to link external websites to my page</li>
<li>Use <code>h1</code> and <code>h2</code> tags to change the main heading and the sub titles</li>
<li>Validate HTML using the W3C validator in order to check for errors (should be done as frequently as possible)</li>
</ol>

</article>

        <aside>
        
        	<h2>References</h2>
            
            	<ol>
                    <li>
                    <cite>
                <a href="https://www.w3schools.com/howto/default.asp"> W3C html HOW TO guide</a>
                            
                    </cite>  
                    </li>


                    <li>
                    <cite>
                <a href="https://www.youtube.com/channel/UCzyuZJ8zZ-Lhfnz41DG5qLw"> mmtuts HTML YouTube Guides</a>
                            
                    </cite>  
                    </li>
                </ol>
            
        </aside>    
  
	<footer><!--Footer content -->
	<p><a href="#top">Go to top of page</a></p>
		<small>&copy; 2019, author.</small>
		<a href="mailto:jw1352@brighton.ac.uk">Email Jake Wright</a>
		
	</footer>

	</div><!--Close 'wrapper' div -->
</body><!--Close 'body' -->
</html><!--Close 'html' -->
