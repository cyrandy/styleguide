# CSS Style Guidelines

## General

* four (4) space indents

* Naming: use hyphen delimited classes (e.g. `.foo-bar`, not `.foo_bar` or `.fooBar`)

* maximum nesting: three levels deep

* list related properties together

* always start a new line for each selector and declaration

## Simple Example
```
.foo {
    .bar {
        .you-are-here,
        .fb-icon,
        .twitter-icon {
            weight: 100px
            height: 100px
            
            margin: 10px
            padding: 10px
            
            background-color: #000
            color: #fff
        }
    }
}
```



