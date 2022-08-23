# markdown-syntax
## Syntax of markdown writing 

Markdown works in any browser even if you use a simple notepad. But there are certain tools that can help enhance your productivity by providing a real time view (of markdown and rich text) side by side.

The following are some of the tools that support working with markdown:

VSCode, 
Atom, 
Haroopad, 
Sublime text, and 
MarkPad.  Syntax of markdown language are as follows 

<!-- Headings -->
# This is heading 1
## This is heading 2
### This is heading 3
### This is heading 4
#### This is heading 5

<!-- Italics -->
*this text is italics*

_italic_

<!-- Bold -->
**bold**

<!-- Strike Through-->
~~strike~~

<!-- Horizontal Line -->

--- 
___

## Block quotes

<!-- Block quote -->
> this is a block

## Links
<!--  links -->
[This is a link](inserlink.com)

[This is a link with tooltip](inserlink.com "tooltip")

## Lists

<!-- Unordered List -->
* item1
    * item2

<!--Ordered List-->

1. first item
2. second item

## Inline code block
<!-- inline code block-->
`<p></p>`

## Images
<!--Images-->

![An image](image.png)


<!-- github md-->

## Code Blocks
### Bash code block

<!-- Bash script block -->

```bash
    npm install
    
```
### JS code block

<!-- JS Block-->

```javascript
function add(num1, num2){

}

```
### Python code block

<!-- Python block-->

```python
print("Hi there")
```

## Task list
<!-- task list -->
* [x] done
* [ ] not done

## Tables
<!-- tables -->
<!-- Note that :---: means center aligned -->
<!-- Note that ---: means right aligned -->
<!-- Note that :--- means left aligned -->

| Column 1 | Column 2 | Column 3 |
| :---: | :--- | ---: |
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3 |

## Diff
<!-- Diff -->
```diff
- This line is removed.
+ This line is added.
```

## Collapsible content
   <details>
          <summary>Click to see more!</summary>
          
            ## More awesoms tips!

            - item 1 
            - item 2
        </details>
