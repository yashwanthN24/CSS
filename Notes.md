##

h1{

    color : rgba(255 , 0 , 0 , 0);
    color : transparent ;

    <!-- Both are same  -->

}

body{
color : rgb(255 , 266 , 0);
}

p{
color : currentColor;  
}

## CSS Units

Absolute units : px (reflect the actual size )

Relative units : relative to some other thing

1. % (percentage)

- 100% = 16px (Remember) (As 16px is default font-size of html element)
- 1px = 6.25%
- so 54px = 337.5%

2. em
   depends on parent font-size
   1em = 16px

3. rem - depends on the foot size of the root
   root element is html its has default font-size = 16px
   1rem = 16px

explorer . => will open explorer folder there

to create custom font-family

@font-face{
font-family : "yashfont";
src: url('./fontFortune.otf');
}

CSS box-sizing is a property that controls how the total width and height of an element are calculated, including its content , padding , and border . It has two possible values

content-box (default)

- padding , border gets added to given width and height of elements

Width = Content + Padding + Border + Margin

border-box

- width and height provided remain final and constant nothing gets added

- width = value you provided (margin , padding , border adjust to sum up to your provided with )

Important Configuration before you start styling anything place this at the top

\*{
padding:0;
margin :0;
box-sizing:border-box;
}

html, body{
width:100%;
height:100%
}
