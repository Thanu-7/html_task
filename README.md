# 14. Create a Webpage with Inline and Block Elements. Demonstrate understanding of <span> vs <div> and other elements.

## HTML code
```
<!DOCTYPE HTML>
 <html lang="en">
    <head>
        <title>HTML TASK</title>

        <style>
            body{
                background-color: rgb(225, 179, 239);
            }
            h1
            {
                text-align: center;
                color: black;
                background-color: rgb(131, 87, 192);
            }
            .container
            {
                display: flex;
            }
            .container>div
            {
                border: 2px;
                width : 33% ;
            }
            
        </style>
    </head>
    <body>
        <h1>Block vs Inline Elements</h1>
        <p>This is paragraph is created using a paragraph tag. A paragraph tag is a block element.<br>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rem soluta tempora repellat praesentium illum ab dolor ipsum alias est aliquid, odio, error fugit quos nemo, veniam blanditiis vitae libero porro! Saepe rerum incidunt porro facere voluptatem, perspiciatis tempora eius, perferendis quas, deleniti fugiat? Excepturi vitae ex quod et, doloribus impedit?
        </p>

        <p>In this paragraph i am using a span tag.<span style="color: white; background-color: rgb(31, 209, 49);">A Span tag is an inline element which Wraps small chunks inside other elements and is used commonly for styling purposes. </span></p>

        <div style="border: 2px solid; background-color: pink;" >
            A div tag is a block element.<br>The div element is often used to group sections of a web page together.
            
        </div><br>

        <div class="container">
            <div style="background-color: aqua;">
                Block 1
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis eveniet vero debitis sunt aliquid vel quidem eum reiciendis molestias illo, expedita nesciunt enim placeat perferendis laboriosam non corporis nihil, eius officiis nisi veniam a! Quod itaque exercitationem molestiae unde amet, ipsa blanditiis sunt quam, ut nihil quos aliquam voluptates? Odio?
                </p>
            </div>
            <div style="background-color: rgb(68, 205, 93);">
                Block 2
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis eveniet vero debitis sunt aliquid vel quidem eum reiciendis molestias illo, expedita nesciunt enim placeat perferendis laboriosam non corporis nihil, eius officiis nisi veniam a! Quod itaque exercitationem molestiae unde amet, ipsa blanditiis sunt quam, ut nihil quos aliquam voluptates? Odio?
                </p>
            </div>
            <div style="background-color: rgb(229, 237, 115);">
                Block 3
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis eveniet vero debitis sunt aliquid vel quidem eum reiciendis molestias illo, expedita nesciunt enim placeat perferendis laboriosam non corporis nihil, eius officiis nisi veniam a! Quod itaque exercitationem molestiae unde amet, ipsa blanditiis sunt quam, ut nihil quos aliquam voluptates? Odio?
                </p>
            </div>
        </div><br>
        <img src="c:\Users\admin\Desktop\velandev\html task\wallper-google.jpg" alt="Unable to load the image" style="width: 700px; height: 350px; display: block; margin: 0 auto;" >
        <p><b>This i a blod text. </b><i>This is an italic text. </i><mark>This text is highlighted. </mark><u>This text is underlined. </u><sup>This is superscripted.</sup><sub>this is subscripted.</sub></p>
        <a href="https://www.w3schools.com/html" target="_blank">Click here to learn more about html</a>

    </body>
 </html>
```
## OUTPUT WEB PAGE
![image](https://github.com/user-attachments/assets/f4ab5bd2-fd9a-4127-8136-7ebd58fc88ab)
