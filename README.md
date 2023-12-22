# Position it right

## Introduction

In this activity, you'll have the opportunity to design a comical robot face using various shapes and applying absolute and relative positioning. Feel free to unleash your creativity and use vibrant colors to make the robot face stand out!

Take a look at the provided image of a fancy robot face in /assets/images/fancy-robot-solved-example.png for inspiration. You can either replicate the example or let your imagination run wild to create unique shapes and experiment with different colors.

Then, you will be enhancing the design of the legal information page to deliver an exceptional user experience for smooth scrolling through lengthy content. Utilize your expertise in fixed and sticky positioning to ensure that users can easily read and navigate legal documents.

Before you begin, it is recommended to watch the [introductory video]().

## Learning objectives

This assignment should prove that a student is able to:

- Create a rectangular container with a specified width and height using absolute and relative units of measurement.
- Create a container that expands to fill the full height or width of the viewport.
- Align an element in the center of its parent container horizontally.
- Adjust the spacing within a container by adding padding to resize the width of the content.
- Utilize CSS rules for padding and margin to control the spacing around elements.
- Apply a border to a container with custom thickness, style, and color.
- Set a background for a container with options such as a solid color, gradient, or image.
- Construct various shapes using CSS and SVG tools for shaping.
- Create containers with varying degrees of opacity and/or transparency.
- Position an element:
  - Relative to its default/static position.
  - Absolutely in relation to the entire HTML document.
  - Absolutely in relation to a parent container.
  - Fixed to the dimensions of the viewport.
  - As a sticky element within a specific container.

## Standard requirements

- [ ] Download the zipped project file, and extract it
- [ ] Move the extracted folder into the project's storage and open the project in VSCode using the terminal
- [ ] All the tasks of the "Specific requirements" section MUST be solved
- [ ] The project's file/folder structure should NOT be edited!
- [ ] VSCode IDE MUST have 0 problems listed
- [ ] The code MUST be formatted with Prettier.
- [ ] Compress (zip) the project folder and submit it through the assignment form, when finished.

## Specific requirements

`For the Robot Face exercise:`

- [ ] The container for the robot face should be positioned using ABSOLUTE positioning relative to the html element.
  - [ ] It should be horizontally centered regardless of the viewport width.
  - [ ] The container should not overlap the header section.
- [ ] Style the shape of the robot face according to the following requirements:
  - [ ] It should be a square shape.
  - [ ] Apply a border to the face with a minimum thickness of 10px, any line style, and any color.
  - [ ] Use padding of 30px for the top, 20px for the bottom, 30px for the right, and 22px for the left.
  - [ ] Ensure that the padding and border are considered as part of the face box's width and height, meaning that the content should shrink when the container is resized.
  - [ ] The corners of the face should be rounded.
- [ ] Create unique random shapes for the following internal elements of the face:
  - [ ] Left eye
  - [ ] Right eye
  - [ ] Nose
  - [ ] Mouth
  - [ ] Teeth
- [ ] Create unique random shapes for the following external elements of the face:
  - [ ] Hair style
  - [ ] Left ear
  - [ ] Right ear
- [ ] Shapes must adhere to the following guidelines:
  - [ ] Each shape must be unique. It is permissible to use the same shape for two paired face elements, but they must have different orientations or directions.
  - [ ] At least one shape should have a solid background color chosen from the available [HTML colors](https://www.w3schools.com/html/html_colors.asp).
  - [ ] At least one shape should have a gradient background color chosen from the available [UI gradients](https://uigradients.com/).
  - [ ] At least one shape should have a background image that fits perfectly within the shape, using images from [Lorem Picsum](https://picsum.photos/).
  - [ ] At least one shape should be clipped using a path or created with SVG shaping tools such as a path, polyline, or polygon. Note that manually created SVGs are expected; generated SVGs from any UI tool will not be accepted.
  - [ ] The width and / or height height of at least one shape should be based on the percentage units relative to the dimensions of the face shape.
  - [ ] The width and / or height of at least one shape should be based on relative units relative to the font size.
  - [ ] At least one shape should have an opacity of 50% or be semi-transparent.
- [ ] Position the shapes inside or outside the face shape according to the following guidelines:
  - [ ] In-face elements should be positioned relatively to their static position.
  - [ ] External face shapes should be positioned absolutely in relation to the robot container.

`For the Legal Page exercise`

- [ ] The page heading should remain fixed in its original position, regardless of how far the user scrolls down the page.
- [ ] The section label should stay fixed in its original position while the user is scrolling through the current section.
- [ ] The footer should be anchored to the bottom of the viewport, ensuring it remains visible even while scrolling.
- [ ] The content should not get obscured by any of the containers fixed at the top of the page.
- [ ] The content should not be hidden by the footer.
- [ ] Only fixed and sticky positioning should be used for this purpose.
