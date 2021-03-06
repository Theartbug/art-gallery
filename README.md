Objective
===
Make a responsive multipaged art themed website. Use a combination of CSS Grid and Flexbox. Follow the Webpack component and router architecture in vanilla JS. Upload images to Cloudinary and load them with responsive Picture component. Apply subtle animations. Utilize the <picture> <source> elements with srcset attribute to create responsive images.

Steps Taken
===

I chose the theme of Burning man and found multiple high-res images on google. I picked three categories of images (people, night, art). I uploaded these images to cloudinary. I followed the structure of the class demo, and created a picture component that would accept an image object and turn it into html with given options on the object. In each of the pages, I created a for loop that loops over arrays containing image names and alts to create image objects to give to the picture component. I selected image aspect ratios and breakpoints for the pictures to change dynamically. I applied multiple subtle animations, such as to the navigation bar, the hamburger icon, captions on hover, and page change.

Here are some demos of the app:
- [Caption Hover](art_gallery_captionhover_demo.gif)
- [Nav Bar](art_gallery_hamburger_demo.gif)
- [Responsive Images](art_gallery_responsive_demo.gif)
- [Splash Page](art_gallery_splash_demo.gif)


Reflection / Changes
===

This was a wonderful application of multiple concepts; CSS animations, cloudinary responsive images, and CSS grid / flexbox. In the future, it would be interesting to try to apply a lazy loader.
