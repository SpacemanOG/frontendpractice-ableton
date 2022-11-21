#Things I understand better now:

1) CSS normalize
2) box-sizing: border-box;

##This is how the code looks like:
`*,
::before,
::after {
    margin: 0;
    padding: 0;    
    -webkit-box-sizing: inherit;
    -moz-box-sizing: inherit;
    box-sizing: inherit;
}

html {    
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}`

[Source](https://css-tricks.com/box-sizing/)