## Cascading

1. If there is a tag h1 and has a class say point so while defining it in the css style sheet just remember that we have to include . in it
    ex - <h1 class= "hey">HELLO</h1>
         CSS - .hey{
            color:red;
         }

### Always style using classes and avoid using tags for styling

#### Specificity -- 
    It is the hierarchy of the classes.
     
####   !important >> ID >> Class >> Tag

Dont't combine ID with anything else.

1. Hover class 
        Use .hover to define the hover class

## Box Model

1. display inline - center of the text, inline won't follow dimension 

2. inline box - inline with dimensions

3. Properties - height , width, margin, padding, border

*{
    box-sizing: border-box;

}
 use the above for setting the whole page in border-box

### Flex
