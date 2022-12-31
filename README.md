SASS - explore

###### variable declaring and using
- $header-bgcolor: colorName;
- $para-fontsize:size;
- header{
    Background: $header-bgcolor;}


###### Using SASS Variables we can store 
- string  
- numbers
- colors
- booleans
- lists
- nulls


###### @mixin and @include 
- A mixin : a group of CSS declarations that can be reused throughout the style sheet.
- Ex: create Mixin: 
- @mixin para-style {
    font-size:16px;
    text-align:justify;}
- use mixin: 
- #about-me p{
    @include para-style;}

    
###### Use @for in SASS loop
- 2 ways -> start through end (includes end number), start to end (does not include end number)
- ex: @for $i from 1 through 12{
    //do something}

- @for and @while available 

###### https://github.com/anisul-Islam/sass-tutorials-code
###### https://sass-lang.com/ , (codecademy , w3scl)
###### 
###### 
###### 
###### 
###### 
###### 
###### 
###### 
###### 