# Buttons

<font size= "5">
How did I make this button?

1. In HTML file i used the tag "a"\_
2. Then in css file I am reffering to that element.<br />
   <font color="green"> 2.1 </font> Make sure to set display of "a" element to block or inline-block. In my example it does not matter which one will you choose.<br />
   Setting position property on "relative" will be useful for making pulse effect.<br />
   <font color="green">2.2 </font>Make basic styling of that element: bgc, padding...<br />
   <font color="green">2.3 </font>Use pseudoclasses and pseudoelement in orhet to add some movement into that element.<br />
   <font color="green">2.3.1 </font>:hover, :active, ::after<br />
   <font color="green">2.3.2 </font>For :hover use transform:translateY(); property in order to get this button moved while you hover this element.<br />
   In my example while hovering the button is moved a little bit up, and then when it is activated (on user's click) it is moving down.<br />
   <font color="green">2.3.3 </font>For :activ set transform: translateY(); property in order to move the button down.<br />
   <font color="green">2.3.4</font> Get the pulse effect!<br />
   <font color="green">2.3.4.1 </font>You can easily get the pulse effect by using pseudoelement ::after or ::before (it does not really <br />mater which you choose in this example).<br />
   <font color="green">2.3.4.2 </font>Style this element (use the same properties as with "a" element). Set width and height of that.<br /> element to 100% in order for this element to have the same width and height as "a" element.<br />
   <font color="green">2.3.4.3 </font>Use position:absolute and then set left, and top properties to 0. After that pseudoelement a::after should cover "a" element, so set z-index to -1, because you want to active ::after only when the button is hovered<br />
   <font color="green">2.3.4.4 </font>On a::after element set tranistion, and then on a:hover::after use opacity, and this effect will make this pulse effect.
   </font>
