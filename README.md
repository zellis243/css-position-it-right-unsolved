# Position it right

## Introduction

In this activity, you'll have the opportunity to design a comical robot face using various shapes and applying absolute and relative positioning. Feel free to unleash your creativity and use vibrant colors to make the robot face stand out!

Take a look at the provided image of a fancy robot face in `/assets/images/fancy-robot-solved-example.png` for inspiration. You can either replicate the example or let your imagination run wild to create unique shapes and experiment with different colors.

Then, you will be enhancing the design of the legal information page to deliver an exceptional user experience for smooth scrolling through lengthy content. Utilize your expertise in fixed and sticky positioning to ensure that users can easily read and navigate legal documents.

Before you begin, it is recommended to watch the [introductory video](https://www.loom.com/share/3c655c8a97ce4783a4698d7968c03c33?sid=c05fcac8-f559-4de4-9ccd-6f167be3d6bd).

## Learning objectives

This assignment should prove that a student is able to:

- Set proper container spacing utilizing the box model parameters:
  - width
  - height
  - border
  - padding
  - margin
- Utilize absolute and relative CSS Units.
- Create shapes of different colors by utilizing the container parameters and backgrounds:
  - Container dimensions (width and height)
  - border box (width, style, color and radius)
  - background (color, image, gradient)
- Align an element to its parent container content box.
- Position an element:
  - Relative to its default/static position.
  - Absolutely in relation to the entire HTML document.
  - Absolutely in relation to a parent container.
  - Fixed to the dimensions of the viewport.
  - Sticky within a specific container.

## Standard requirements

- [x ] Fork the project to your github account
- [x ] Clone the project to your computer
- [x ] Open the project in VSCode with `code <cloned_repo_folder_name>`
- [ x] This Assignment is NOT tested. You can use all the desired creativity!
- [ ] All the tasks of the "Specific requirements" section MUST be solved
- [ ] The project's file/folder structure should NOT be edited!
- [ ] The index.html file should NOT be edited! The only acceptable change are additional classes added to elements.
- [ ] VSCode IDE MUST have 0 problems listed
- [ ] The code of the index.html and styles.css should pass the W3C validation (Feel free to use either the "w3c web validator" VSCode extension or the "Online w3c Markup Validation Service")
- [ ] The code MUST be formatted with Prettier.
- [ ] Push the changes to the Github repo, when finished.
- [ ] Submit a .txt file with the Github repo url.

## Specific requirements

`For the Robot Face exercise:`

- [x ] Visit the [The shapes of CSS](https://css-tricks.com/the-shapes-of-css/) article for some shapes inspiration.
- [ x] Edit the following files to solve that part of the assignment:
  - [x ] html: `/pages/fancy-robot.html`
  - [ x] css: `/css/fancy-robot.css`
- [ x] The container for the robot face (face shape) should be positioned/aligned following the rules:
  - [ x] It should be horizontally centered to the viewport width and height.
  - [ x] The container should not overlap the header section.
- [x ] Style the shape of the robot face to follow the requirements:
  - [x ] Should be a simple shape (square, circle, oval).
  - [ x] Should have a border of any style, color and width.
  - [ ]x The face parts should NOT touch the border in their static positions.
  - [ x] The corners of the face shape should NOT be a straight (right) angle.
- [ x] Create unique random shapes for the following internal elements of the face:
  - [x ] Left eye
  - [ x] Right eye
  - [ x] Nose
  - [x ] Mouth
  - [ x] Teeth/tooth
  - [ x] **!!!Optional** Add any other part you want.
- [ x] Create unique random shapes for the following external elements of the face:
  - [x ] Hair style
  - [ x] Left ear
  - [ x] Right ear
  - [ x] **!!!Optional** Add any other part you want.
- [ x] Shapes must follow the guidelines:
  - [x ] Each shape must be unique. It is permissible to use the same shape for two paired face elements, but they must have different orientations or directions.
  - [ x] Use the following types of shapes:
    - [x ] At least one square shape
    - [ x] At least one circle shape
    - [ x] At least one rectangle shape
    - [ x] At least one oval shape
    - [x ] Any other shapes of your choice. You can add additional containers to create a combined shape and additional classes inside the current face part.
  - [ x] At least one shape should have a solid background color chosen from the available [HTML colors](https://www.w3schools.com/html/html_colors.asp).
  - [ x] At least one shape should have a gradient background color chosen from the available [UI gradients](https://uigradients.com/).
  - [x ] At least one shape should have a background image that fits the shape and doesn't overflow it, using images from [Lorem Picsum](https://picsum.photos/) or any other images CDN service.
  - [ x] The width and / or height height of at least one shape should be based on the percentage units relative to the dimensions of the face shape.
  - [x ] The width and / or height of at least one shape should be based on relative units relative to the font size.
  - [x ] At least one shape should have an opacity of 50% or be semi-transparent.
- [x ] Position the shapes inside or outside the face shape according to the following guidelines:
  - [x ] In-face elements should be positioned in relation to their static position.
  - [ x] External face shapes should be positioned in relation to the robot container or the face shape.

`For the Legal Page exercise`

- [ x] Watch the [Legal Page INTRO video](https://www.loom.com/share/3c655c8a97ce4783a4698d7968c03c33?sid=b776b29f-cecb-4cc7-8663-7c3f1722f190).
- [ x] Edit the following files to solve that part of the assignment:
  - [ ] html: `/pages/legal-page.html`
  - [ ] css: `/css/legal-page.css`
- [ ] The page heading container should be "pinned" in the top right beneath the header and take the full width of the viewport, regardless of how far the user scrolls down the page content.
- [ ] The footer should be anchored to the bottom of the viewport, ensuring it remains visible even while scrolling.
- [ ] The section label should stay fixed in its parent while the user is scrolling through the current section.
- [ ] The content should not get obscured by any of the containers at the top and bottom of the page.
