## Tables

| heading1 | heading2 |
| -------- | -------- |
| 11       | 12       |

| heading1 | heading2 |
| --- | --- |
| 11 | 12 |
| 21 | 22 |

## Tables alignment 

| heading1 | heading2 | heading3 |
| :--- | :---: | ---: |
| left | center | right |
| **bold** | _italic_ | ~~strike~~ |

## Collapsed section

<details><summary>Get details</summary>

### This section is hidden until you press "Get details"

You can include any markdown block here for view!

</details>


## Links

### External links

Welcome to [CloudAffaire](https://cloudaffaire.com)

This will autolink https://cloudaffaire.com

This will not autolink `https://cloudaffaire.com`

### Selection links

Here is a link to [code snippet](https://github.com/CloudAffaire/Markdown#-code-snippet-) covered earlier.

### Relative links

Here is a [link](doc/author.md) to another markdown file!


## Images

### Internal Image

![image not found](images/cloudaffaire.png "CloudAffaire")

### External Image

![image not found](https://cloudaffaire.com/wp-content/uploads/2018/09/LOGO11.png "CloudAffaire")

### Anchor Image

[![image not found](images/cloudaffaire.png "CloudAffaire")](https://cloudaffaire.com)

### Resized Image

<img src="images/cloudaffaire.png" alt="image not found" width="200" height="200"/>

## Ordered List

1. First item
2. Second item
    1. First sub item
    2. Second sub item
        1. First sub sub item
3. Third item
4. Fourth item

## Unordered List

- First item
- Second item
    - First sub item
    - Second sub item
        - First sub sub item
- Third item
- Fourth item

## Task List

- [x] First item
- [ ] Second item
    - [ ] First sub item
    - [x] Second sub item
        - [x] First sub sub item
- [ ] Third item
- [ ] Fourth item

Use `echo Hello World!` command to print in shell

Use below code to print in java
```
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

Same java code with syntax highlight
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

This is a short paragraph (p)

This is a long paragraph where we have not given a line break as a result, it will be rendered into a single block in your readme.md file. If you want to write a long paragraph block, do not break that into multiple paragraphs.

This is a long paragraph where we have given a line break.

As a result, it will be rendered into multiple blocks in your readme.md file.

<!--- And this block will not get rendered, not visible in readme.md and used as comment --->

# This is Heading1 (H1)

## This is Heading2 (H2)

### This is Heading3 (H3)

#### This is Heading4 (H4)

##### This is Heading5 (H5)

###### This is Heading6 (H6)

This is a plain text

This is a **bold** text

This is an _italic_ text

This is a ~~strike through~~ text

This is a `code` block

**This is _italic_ within bold text**

**This is ~~strike through~~ within bold text**

 _This is ~~strike through~~ within italic text_ 

***This is bold and italic text***

**~~This is bold and strike through text~~**

_~~This is italic and strike through text~~_

> This is a quote block
>
>> This is a quote block within quote block
