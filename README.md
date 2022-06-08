# CustomFonts
How to add custom fonts to your web-site 

this project shows how to upload your own fonts. 
instractions:
1.open a floder name fonts in your project.
2.transfer your font type .tff (can be also a different extansion) to the fonts llibrary.
3.copy & paste the html & css files.
4.please note: in the style.css in the header of the code, 
you can see that i'm using @font-face to import my custom fonts. you can see below some explanations
@font-face {
    font-family: 'handwriting1';                    //give your own name to the font - this will be the name you gonna locate it later in h1 & h2 tags.
    src: url(fonts/adelia.ttf) format("truetype");   // give the path to the folder fonts in your prject.
  }

5.implement the fonts:
 h1 {
    font-size: 6em;
    font-family:'handwriting1',sans-serif;         // the first option is the handwriting1 , and the second one is default sans-serif , this will replace the custom    }                                                     font if in any reason it will not be avaliable to display - so this will be the backup.
    
 
