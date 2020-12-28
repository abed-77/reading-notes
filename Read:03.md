# lists in html

unorderd-lists in html is usually conducted as following:

    <ul>
        <li></li> <<!-- List Item 1 -->>
        <li></li> <<!-- List Item 2 -->>
    </ul>

and for ordered-list as  following:

    <ol>
        <li></li> <<!-- List Item 1 -->>
        <li></li> <<!-- List Item 2 -->>
    </ol>

there is also a definiton list:

    <dl>
        <dt></dt>  <<!-- Term 1-->>
        <dd></dd>   <<!-- Term 1 definition -->>

        <dt></dt>  <<!-- Term 2-->>
        <dd></dd>   <<!-- Term 2 definition -->>
    </dl>

# Boxes using CSS 

CSS treats each HTML element as if it has its own box.You can use CSS to control the dimensions of a box.You can also control the borders, margin and padding for each box with CSS.

example of styling a box regading border-width

    border-top-width : thin;
    border-right-width : medium;
    border-bottom-width : thick;
    border-left-width : 5px;
or short handed

    border-width: 7px;

example of styling a box regading border-style

     {border-style: solid;}
     {border-style: dotted;}
     {border-style: dashed;}
     {border-style: double;}
     {border-style: groove;}
     {border-style: ridge;}
     {border-style: inset;}
     {border-style: outset;}

The padding property allows
you to specify how much space
should appear between the
content of an element and its
border, like;

    padding-top: 10px;
    padding-right: 5px;
    padding-bottom: 3px;
    padding-left: 1px;
or short handed 

    padding: 10px 5px 3px 1px;


The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems.

    margin-top: 1px; 
    margin-right: 2px;
    margin-bottom: 3px;
    margin-left: 1px;

or short handed

    margin: 1px 2px 3px 4px;

