# Final Project

## Introduction

Welcome to the final project! In this project, you will demonstrate your ability to write media queries for both screen sizes and accessibility. This project involves creating a responsive website that adapts to different screen sizes and user preferences.

## Instructions

### Replace Images
- Replace all the images provided in the `<img>` tags with your own images.
- Ensure each `<img>` tag has appropriate `alt` text.

### Add Content
- Replace the content inside the first and second `<p>` tags with your own content that describes the contents of your site and any additional information you'd like to include.

### Retain "Jump to the Top" Link
- Do not remove the `<a href="#top">Jump to the Top</a>` link at the bottom of the page.

### Modify CSS Grid
- Edit the `style.css` file to set the `.grid` class to use a one-column grid layout with a 10-pixel gap between rows and columns.

### Write Media Queries

1. **Tablet View (772px)**
   - Add a media query in the `style.css` file that triggers at 772px.
   - Change the `.grid` class to use a two-column grid layout.
   - Set the border radius on the `<figure>` elements to create a circular shape.
   - Ensure the last `<figure>` element takes up both columns.

2. **Large Screen View (992px)**
   - Add a media query in the `style.css` file that triggers at 992px.
   - Change every third `<figure>` element to take up both columns.
   - Remove the border radius from all `<figure>` elements.

3. **Prefers Reduced Motion**
   - Add a media query in the `style.css` file that detects if the user prefers reduced motion.
   - Remove the smooth scrolling behavior for the "Jump to the Top" link when this preference is detected.

4. **Prefers Color Scheme (Dark Mode)**
   - Add a media query in the `style.css` file that detects if the user prefers a dark color scheme.
   - Change the background color of the `<figure>` elements to a dark color.
   - Change the font color of the `<figcaption>` elements to a lighter color.
   - Change the border color of the `<figure>` elements to black.

## Validation

1. **W3C Validator**
   - Run your code through the [W3C Validator](https://validator.w3.org/) to check for errors and fix any issues.

2. **Wave Validator**
   - Use the [Wave Validator](https://wave.webaim.org/) to check for color contrast errors and fix any issues.

## Peer Review

- Review different styling choices made by your peers and practice changing settings on your computer. Use these resources for help:
  - [Change your Mac display’s Color Scheme](https://support.apple.com/guide/mac-help/change-your-mac-displays-color-scheme-mchlp2591/mac)
  - [Change colors in Windows](https://support.microsoft.com/en-us/help/4027874/windows-10-change-your-desktop-background-and-colors)
  - [Turning on prefers-reduced-motion](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion)

## Conclusion

By following these instructions and implementing the necessary media queries and adjustments, you will create a responsive website that adapts to different screen sizes and user preferences. This project also emphasizes the importance of transitioning to digital solutions to achieve carbon neutrality.
