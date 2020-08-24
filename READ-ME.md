2020-08-22 "Note about Font Awesome Icons"
    -fa-images, fa-calendar-alt, and fa-handshake are currently regular weight icons, the light weight icons are available only to PRO subscribers.  Ligh weight appears to be the best match for the design given.  I have chosen for this project to use the regular weight icons, as I do not have the PRO subscription yet. -AC


2020-08-22 "Note about vertically centering element without Flexbox"
    -in order to match the design of the "articles" section, I decided I needed to vertically center my "article-info" div, which was tricky because both it and its parent changed sizes rapidly.
    -I came up with a method that:
    1. sets the "article-info" to absolute and its parent to relative
    2. I position the child's top:50% to move it DOWN whereby its top edge is now vertically centered
    3. I readjust the child UP by half its own height to place it's vertical center on its former top edge position, which now vertically centers the entire element against the parent. I used transform:traslate(-50%) to achieve this adjustment IN REFERENCE TO ITS OWN HEIGHT.
    4. LINK to my work in codepen on this issue: https://codepen.io/ac_lemens/pen/gOrgpep -AC
    
2020-08-23 "Note about variable font size calculation"
    -here is my formula for calculating font size that can adapt to the screen size in expected and controlled ways:

        font-size = initial font size + (100vw - initial screen width)*(goal font size - intial font size / goal screen size - initial screen size)

    -can also be used to create variable margins,padding,line height, or image widths
    -AC

2020-08-23 "Note about using span.nobreak"
    -I have found a way to use the white-space property to help control word breaks in the contact area of the "stay-updated" section.
    -Set white-space to nowrap on a span to contain the words you want to prevent breaking prematurely.  Using this as a general style similar to wrapper
    -AC

2020-08-23 "Note about menu font-awesome icon"
- I have chosen the SOLID bars from font-awesome as they are free, and I do not have access yet to the pro options.  I am aware that the design best matches the LIGHT bars from font-awesome, and would be changed to them in the real world, where I'm making money to pay for this account
-AC

2020-08-23 "Note about asset image-6@2x.png"
- This image in our assets folder does not match the design image, and cannot be adjusted to match the photo contents.
-AC



    