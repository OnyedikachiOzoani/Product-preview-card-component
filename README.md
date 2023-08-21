<!-- @format -->

# Solution to Frontend Mentor Product preview card component Challenge

## Design preview for the Product preview card component coding challenge

1. Desktop preview: ![image of the desktop design preview](design/desktop-design.jpg "desktop preview")
2. Mobile preview: ![image of the mobile design preview](design/mobile-design.jpg "mobile preview")

Link to the challenge on Frontend Mentor: [The challenge](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub "view challenge on Frontend Mentor").  
Check out my Frontend Mentor profile: [Frontend Mentor](https://www.frontendmentor.io/profile/OnyedikachiOzoani "view my Frontend Mentor profile")

## Challenge description

The major purpose of the challenge is to build out the product preview card component to look, as much as possible, as the design preview for desktop and mobile respectively.

## Solution description

I've built out the project to look exactly as the design preview.  
For the _mobile design_, I've set it to be visible when the **viewport width is <=375px**.  
For the _desktop design_, I've set it to be visible when the **viewport width is >375px**.

## Basic tools used

-   HTML
-   CSS

### Notable CSS properties used

-   Desktop:

    1. `display: table;`
    2. `display: none;`

-   Mobile:

    1. `display: revert;`
    2. `dislplay: none;`

-   For both:
    1. Flexbox layout: `display: flex;`

## Issues faced when building the project

1. Getting the product image and the product description parts to stack together  
   horizontally whist maintaining the aspect-ratio od the image using `display: table`.
   View my question and its answer on StackOverflow: [Question](https://stackoverflow.com/questions/76793682/css-height-property-not-working-for-display-table).

2. Writing conditions for media query rules for targetting devices within a particular  
   range of viewport widths. What caused my confusion (issue) was chrome using fractional pixels for resizing the viewport width.
   View my question and its answer on StackOverflow: [Question](https://stackoverflow.com/questions/76895485/css-display-none-not-working-for-a-condition-given-in-media-queries).

3. For both the mobile and the desktop design, centering the whole item in the page horizontally and vertically using flexbox layout.

Don't forget to check out my StackOverflow profile: [My StackOverflow profile](https://stackoverflow.com/users/21363556/coding-nerd).

**Thanks for reading and checking out my project**
