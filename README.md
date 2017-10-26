# Front-end Skills Assessment
The following exercise is aimed at assessing the current skill level of a front-end developer when it comes to the basics (HTML, CSS and DOM manipulation using JavaScript). It is an assessment - not a test. Try to accomplish as much of it as possible within the time limit indicated.


## Objectives
The exercise should demonstrate your level of ability/understanding of the following concepts:

1. Setting up an HTML5 document and including external resources.
2. Writing valid, semantically correct markup.
3. Writing valid, maintainable and reusable CSS.
4. Converting an interface design into a fully responsive web page.
5. Enhancing interactions on a page via DOM manipulation (using either jQuery or vanilla JavaScript).
6. The ability to write clean, modular and well formatted code.
7. Cross-browser/device testing.

## Brief
Implement the interface shown in the supplied design file (see the assets section below for download link). The design consists of desktop, tablet and mobile views for a single web page.

### Cards
The finished product should list several card items on a page with alternating image/text layouts. The image size should be fixed but the card height should grow if the text happens to be a bit longer (see last card in desktop design).

One of the cards should have the prestigious 'Doggo of the Weeko' badge applied over the image.

### Sidebar
Links in the sidebar menu should scroll the page to the relevant card when clicked so that the selected card sits at the top of the viewport.

The sidebar menu should remain fixed on desktop but allow for more menu items to be added without making them hidden below the fold.

On tablet, the sidebar should be hidden off the left side of the page. When the menu button in the footer is clicked/tapped, the menu should transition in from the side and push the main page content over. The menu can be hidden again by clicking/tapping either the menu button or the cross in the top right corner of the sidebar.

On mobile, the sidebar should transition in from the left _over top_ of the page content when the menu button is clicked/tapped. The menu can be closed again using the cross icon in the top right corner. The sidebar should be the same height as the viewport but allow for scrolling if there are too many items to show within the viewport height.

### Header
The header should always be statically positioned and scroll with the page content normally.

### Footer
The footer should be static on desktop but fixed to the bottom of the viewport on tablet/mobile.


## Constraints
1. You do not need to handle the screen being resized after the web page has been loaded (e.g. if the menu is opened on a browser sized to 320px wide and then resized to be full screen you don't need to worry about any oddities this will cause).
2. Final solution should be compatible with IE9+ as well as the latest versions of iOS/Android devices.
3. It's up to you where you set your breakpoints. The final solution should match the design at 320px, 1024px etc but it's up to you how you handle elements at the screen sizes in between.
4. You can use any JavaScript plugins or libraries you like but the page appearance must remain the same as the design and behave as outlined in the brief.
5. You may not use the Bootstrap CSS framework to complete this task. You can use a mini framework to help with things like grids if you need to but the majority of the styling should be bespoke or reused from CSS you've previously written yourself.
6. You may use the internet to help with problem solving but be aware you will be asked to explain your approach so don't copy and paste code unless you have a full understanding of how it works.
7. Thought process must be demonstrated via incremental commits. As you complete a step, commit your changes with a message that describes them.


## Assets
- Photoshop design file can be found in Google Drive: https://drive.google.com/a/mediasuite.co.nz/file/d/0B5UzV9WuJpweYkVSQWtKemU5cVk/view?usp=sharing
- Static images of design can be found in the root of `/design-assets/`
- Content images can be found under `/design-assets/images/`
- Close icon SVG for the sidebar can be found in `/design-assets/icons/`
- Lato Google Font: https://fonts.google.com/specimen/Lato?selection.family=Lato


## Workflow
To begin the assessment, fork this repository and pull down the design assets. Create a new branch and add all files required for your solution under the (initially empty ) `/doggotopia/` directory.

Remember to commit your changes as you go so it's clear how you've gone about tackling the task. For example, you might do a commit once you've got your base HTML/CSS/JS files set up, another commit when you markup the main page structure, one for implementing the header etc.


## Time Allowance
Time management is part of the assessment. With this in mind, aim to complete as much as possible, to the highest standard possible, within 6 hours. Push up everything you've done at the end of this time limit and open a new PR for review.


## Assistance
Unless there is found to be a glaring omission in the information provided here, there will be very little assistance offered during this assessment. Your task is to complete the brief and adhere to the constraints. If something isn't listed in the constraints then consider it ok. If an edge case isn't mentioned in the brief then use your best judgement to make a call on how it should be handled.

If there's something you do want to check then by all means, run it past someone. Just understand that you may not get an answer :)


That's it - have fun!