# HeaderSicky.js

## Example code
 Make with sass

```javascript

 .header_title{
     top: 0;
     display: flex;
     position: sticky;
     z-index: 100;
     width: 100%;
     height: 10vh;
     transition: all 300ms;
     background: $dark-secondary-color;
     color: lighten($dark-secondary-color, 20%);
     @include box-shadow();
     h1{
         display: flex;
         align-items: center;
         justify-content: center;
         flex-grow: 1;
         color: inherit;
     }
 }
 .header_title_fixed{
     @extend .header_title;
     height: 5vh;
     h1{
         font-size: 1em;
         color: $secondary-text-color;
     }

 }

```
## Use classes

Use the header_title class to define idle state,

Use the header_title_fixed to define activate/scrolled/sticky state
