# CSS Style Guidelines

## General

* four (4) space indents

* Naming: use hyphen delimited classes and in lowercase (e.g. `.foo-bar`, not `.foo_bar` or `.fooBar`)

* maximum nesting: three levels deep

* list related properties together

* always start a new line for each selector and declaration

## Simple Example
```sass
.foo
    .bar
        .you-are-here,
        .fb-icon,
        .twitter-icon
            // no more indent here!
            weight: 100px
            height: 100px
            
            margin: 10px
            padding: 10px
            
            background-color: #000
            color: #fff
```



