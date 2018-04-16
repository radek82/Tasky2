# Task 1
<html>
<head>
</head>
<body>
<header>
<nav role="navigation" aria-labelledby="breadcrumbmenu">
<ol>
	<li> <a href=""> Dashboard</a></li> 
	<li> <a href=""> Main </a></li> 
	<li> <a href="" class="active"> Dashboard</a></li> 
</ol>
</nav>
<div class="search-container" role="search">
  <form action="">
    <input type="text" name="search">
    <button type="submit">Search</button>
  </form>
</div>
</header>
<nav role="navigation" aria-labelledby="mainmenu">
  <a href="">Welcome</a> |
  <a href="">History</a> |
  <a href="">Options</a> |
  <a href="">Admin</a>
</nav>

<h1>Wiki</h1>
<nav role="navigation" aria-labelledby="submenu">
<ol>
	<li> <a href=""> Page Op</a></li> 
	<li> <a href=""> Browse Space</a></li> 
	<li> <a href=""> Add content</a></li> 
</ol>
</nav>
<main>
<article>
<h2>Welcome</h2>
<p>
Quisque velit nisi, pretium ut lacinia in, elementum id enim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur aliquet quam id dui posuere blandit. Sed porttitor lectus nibh. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur non nulla sit amet nisl tempus convallis quis ac lectus. Curabitur non nulla sit amet nisl tempus convallis quis ac lectus. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Nulla porttitor accumsan tincidunt.
</p>
<figure>
  <img src="https://www.w3schools.com/howto/img_paris.jpg" alt="" width="304" height="228">
  
</figure>

</article>
<section>
Show children | View History etc
</section>
<aside>
Comments <a href""> add commen
</aside>
</main>
<footer role="footer">
</footer>
</body>

</html>

#Task 3
/** Aspx file **/

Seperate javscript
Seperate css
Bundle? 
Should the JS and Css even be referenced in this file?
GetLanguageString("/applicationform/requiredfield") -> make one method/property?
Visible='<%# Int32.Parse(PropertyService.GetStringProperty(CurrentPage, "NumberOfFileUploads")) > 0 %>'> -> Backend Logic?


/** Aspx.cs **/
Naming convention? btnShowFileUpload_Click - Btn_SubmitForm_Click
Spilt up logic into different services/helpers/logic classes.
Hardcoded data (i.e. ContactPerson)!!! -> move to CurrentPage or xml or db
(string s in addresses) what is s? -> Bad readability of code!

Naming of properties and parameters
string applicationSender = Txt_Email.Text;
BuildMail(applicationSender
protected MailMessage BuildMail(string toAddresses

BuildEmailContent -> dynamically load the controller and get the string from it with html. No need to write html in CB.


Cannot figure it out with multiple upload controls?
