1.  Here is a sample html file with a submit button. Now modify the style of the paragraph text through javascript code.
    ```
    <!DOCTYPE html>
    <html>
    <head>
    <meta charset=utf-8 />
    <title>JS DOM paragraph style</title>
    </head> 
    <body>
    <p id ='text'>JavaScript Exercises - w3resource</p> 
    <div>
    <button id="jsstyle"
    onclick="js_style()">Style</button>
    </div>
    </body>
    </html>
    ```
    Clicking on the button the font, font size, and color of the paragraph text will be changed.
    
2. Write a JavaScript function to get the values of First and Last name of the following form. 
    ```
        <!DOCTYPE html>
        <html>
        <head>
            <title>Return first and last name from a form - w3resource</title>
        </head>
        <body>
            <form id="form1" onsubmit="getFormvalue()">
            
            First name: 
            <input type="text" name="fname" value="David"><br>
            
            Last name: 
            <input type="text" name="lname" value="Beckham"><br>
            
            <input type="submit" value="Submit">
            
            </form>
        </body>
        </html>
    ```
    > Research on use of preventDefault()
    
  3. Write a JavaScript program to set the background color of a paragraph.
  
  4.  Here is a sample html file with a submit button. Write a JavaScript function to get the value of the href, hreflang, rel, target, and type attributes of the specified link. 
       ```
        <!DOCTYPE html>
        <html>
        <head>
        </head>
        
        <body>
            <p>
                <a id="w3r" type="text/html" hreflang="en-us" rel="nofollow" target="_self" href="https://www.w3resource.com/">w3resource</a>
            </p>
            
            <button onclick="getAttributes()">Click here to get  attributes value</button>
        </body>
        
        </html>
       ```
 5. Write a JavaScript function to add rows to a table.
   
 6. Write a JavaScript program to remove items from a dropdown list.
      ```
        <!DOCTYPE html>
        <html>
        <head>
            <title>Remove items from a dropdown list</title>
        </head>
        <body>
            <form>
                <select id="colorSelect">
                    <option>Red</option>
                    <option>Green</option>
                    <option>White</option>
                    <option>Black</option>
                </select>
                <input type="button" onclick="removecolor()" value="Select and Remove">
            </form>
        </body>
        </html>
      ```
   7. Write a JavaScript program to calculate the volume of a sphere.
   
      ![alt text](https://github.com/muskerteers/dom/blob/master/volume-sphere-html-form.png)
    
   8. Write a JavaScript program to get the width and height of the window
