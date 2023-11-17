# fullstack
HTML---> Hyper Text Markup Language
->Responsible for webpage structure
->building blocks of web page
--> HTML elements are represented by syntax content in between the tags "<>".
<element> heading text </element>
<h1> heading text </h1> ---> Heading Element
<p> text </p>--> Paragraph element
<img src="..." />  ---> Image element
<br/> ---->Line break

Basic HTML Page Structure:

<!DOCTYPE html> ==== HTML VERSION
<html>          ==== ROOT Element
    <head>      ==== INFORMATION ABOUT THE PAGE(META, LINK, TITLE)
	  <title>Documnet</title> === PAGE TITLE
	  ................META, LINK
	</head>
	<body>  === WHAT WILL BE DISPLAYED ON THE PAGE
	.........PAGE CONTENT
	</body>
</html>


Extension:
-->Live server
-->file->Auto save option
-->settings-->wordwrap
-->settings.json --> we can see recent changes
-->Emmet(it is an builtin function)--->when will type something on vs it will give abbreviation
Emmet-> the essential toolkit for web-developer
--><img src=" udemy.png" alt="udemy image ">
---><img src="./images/udemy-red.png" alt="red udemy image">
pexel.com
-->br--->line break
external link:link the web page
<a herf="https://www.udemy.com/"
target="_blank">visit udemy for more information</a>
target-->i will open the link page in separate tab.

Internal link:
we have create one html file for example about.html
inside we need to give index.html file and give go back to homepage in description
then in index.html file we need to add link about.html file.

Link within the page:
for eample if we have big page and we are in bottom of the page and if we need to reach top of the page without
scrolling up, we can link the top line id so that we can reach top of the page once we clicked the link.

<a herf="#top">back to the top</a>

image as a link: now the image working as link
<a herf="https://www.udemy.com/">
<img src="udemy.png" width="100" alt="">
</a>

Empty link:
if we will not mention any link adderss in herf, instead of address just we are mentioning #,
then image will not navigate anywhere.
<a herf="#">
<img src="udemy.png" width="100" alt="">
</a>
