# miprimerapaginaweb.github.io
mi primera pagina web practical work ii



here is a detailed dev log:
COMMITS BEFORE DECEMBER:
    -Hello world has been added
    -Page cyan background has been added
COMMIT 4th Dec. 
    -Menu added
    -Icons added for Menu
    -Main page description added
    -All page files have been created
    -All page files have been linked

    -Contact page floating boxes have been added
    -Global Red button designed and applied to "send your messenge"

    -About me page

COMMIT 5th Dec:
    -about me text written and implemented images
    -designed an html page that is now scrollable following the design and style of its 2 unscrollable predecessors.
    -about me page has been fully completed


    CHALLENGES:
    when implementing the icons on the menu, i had trouble doing so because some would just not load even though i included their paths correctly (as <i class="fa-brands fa-windows"></i>). after a lot of testing and errors, i figured that only icons that werent somehow protected would load. So, if an icons path had "fa-brands", "fa-solid" or any other attribute before its name it wouldnt load correctly. knowing this I only implemented icons following the simple structure (<i class="fas fa-file">). 

    I also had a lot of problems appliyng margins, paddings and structuring the page overall. All of this was fixed by a lot of testing until it looked good. However, I did have special problems implementing my first image to the project, this was the one of me at the beach. I had a lot of problems placing it in the middle because when I did, for no reason it would go really small. A long time later i figured it was becasue there was a big left margin applied to a container above it, so, when sent to the middle, the image would shrink in order to fit the margin. 

    Since i had a very specific way I wanted the menu buttons in my head, another challenge was implementing that. It was quite a headache as well making the buttons change color when the mouse was above because they would change their postion no reason whatsoever. I later realized it also had to do with the margin applied to them forcing them to squish from on line into two.


    As a conclusion it can be said that I have learned how to deal with margin problems and other common issues when designing your first web page. I also gained a solid understanding of how .html and .css files work
    
    and design a basic web page overall.

HERE IS A PROJECT STRUCTURE
/project-root
|-- index.html
|-- styles.css
|-- images/
|   |-- image1.jpg
|   |-- image2.png
|-- README.md