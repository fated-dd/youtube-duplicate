# YouTube Duplicate from SuperSimpleDev

This is a duplicate YouTube page for [HTML & CSS Full Course - Beginner to Pro](https://www.youtube.com/watch?v=G3e-cpL7ofc)

<br/>

![Preview of the Duplicate Page](/static/README/Preview.jpg)

## Main features of the duplication:

• __Video Grid__

• **Header**

• **Sidebar**

• **Tooltips for hovering on author's pfp and search icon**


## Techniques used:

1. nested Layouts Technique

2. Display: block, inline-block, grid, flex

3. Position: fixed, relative, absolute

4. Responsive Design

## Additional Features:

1. The Sidebar will expand if the page is >= 1200px wide

```css
@media (min-width:1200px) {
    .sidebar-div{
        width: 200px;
        padding-left: 15px;
        align-items:start;
        justify-content:top;
        row-gap: 20px;
    }

    .sidebar-link{
        display: flex;
        flex-direction: row;
        align-items: center;
        column-gap: 20px;
        text-align: left;
        font-size: 15px;
    }

    .sidebar-icon{
        width: 30px;
    }

    body{
        padding-left: 230px;
    }
}
```

## Offical Course Materials:

[HTML and CSS Course Materials](https://github.com/SuperSimpleDev/html-css-course)