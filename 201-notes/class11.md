# Readings: Audio, Video, Images


## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

Online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility 
issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them. 

2. Describe the use of the src and controls attributes in the <video> element.

`src`: In the same way as for the `<img>` element, the `src` (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

`controls`: Use the controls attribute to include the browser's own control interface.

3. Why is it important to have fallback content inside the <video> element?

The fallback content in video tags will be displayed if the browser accessing the page doesn't support the `<video>` element, allowing us to provide a fallback for older browsers.
This content could be things such as a parage or a direct link to the video.

4. Write a very short story where <audio> and <video> are characters.

The `audio` and `video` elements are like siblings. They both contain many of the same attributes but slightly differ from each other since the `video` element provides
a visual and audio does not.


## A Complete Guide To Grid

1. How does Grid layout differ from Flex?

Flex is a one-dimensional layout and Grid's layout is two-dimensional. Grid is defined on the parent element and flex happens on the children. Grid is better at overlapping.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

Grid cointainer: The element on which display: grid is applied. It’s the direct parent of all the grid items. 

Grid item: The children (i.e. direct descendants) of the grid container.

Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. 


## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Its important to make images responsive so the layout of the website can be arranged dependant on the viewport of the device it is being rendered from. If the site is being viewed on a narrower screen, 
the important detail in the center of the image (the people) can still be seen, and the excess is lost off either side.

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

We can use two attributes — `srcset` and `sizes` — to provide several additional source images along with hints to help the browser pick the right one. If using a `srcset` and `size` attributes on a webpage
we can allow the browser to decide which img it will choose to render depending on the size of the viewport.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

`srcset` defines the set of images we will allow the browser to choose between, and what size each image is.

## Things I want to know more about

1. Are there websites like flex froggy for grid?
