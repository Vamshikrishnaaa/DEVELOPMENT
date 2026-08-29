`Elements:` 
- tags are part of elements ,ex- <p></p> , <h></h>
- tags used in other tags are called nested tags , ex-<p><b></b></p> 

- Header tags are used for defining a header , there are multiple header tags
like <h1>,<h2> etc depending on their size 

`BOILER PLATE`
Works on a heirarchy of tags which include :-

- <!doctype  html> the start of any html webpage
- ROOT (<html>)
- HEAD (<head>) in this tag we can use to integrate with other thing or in simple this acts like private access specifier in class of oops in cpp , we can store metadata of the webpage , this isnt exactly like that , info inst actually private and can be accessed using webpage inspection
- TITLE (<title>) this is the major thing in SEO of browsers, this is displayed on the tabs row on the upper side of a browser and is very important
- BODY (<body>)

`EMMET (!)`
this is used to generate the boiler plate code easily in html , ! this symbol is used 


` LIST`
- <ul>
    <li>example for unordered list </li>
  </ul>

- <ol type="A">
    <li>example for ordered list </li>
  </ol>

  that type above is called attribute is used to print list using alpha or numeric type , captial alphas or small alphas too 

`ATTRIBUTES`
- are used to add more info to the tag , just like above added a type attribute

 `ANCHOR TAG`
- used to add link to a text 
  <a href="link">texthere </a>
  href means hypertext reference
    - you can either use absolute links (or)
    - we can also use relative links meaning we can access the other page of the same website here (page linking)

`IMAGE ELEMENT`
- one of the only tag which uses single tag and no terminator tag
  <img src="image.png" alt="Random image height="EXAMPLEpx" width="EXAMPLEpx">
  - image.png should exist in the same folder as this html file (or) paste the 
  eact directory of the image instead (or) we can also paste an absolute links
  of a picture directly from web
  - that "random image" is a text to say what picture was here in case image
  fails to load