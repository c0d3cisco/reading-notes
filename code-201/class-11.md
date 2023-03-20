# Audio, Video, Images

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
Early implementation used things such as Flash and Silverlight. There were security issues and concern with these serveries and they were phased out and replaced with HTML functionality.  
2. Describe the use of the `src` and `controls` attributes in the `<video>` element.
The `src` attribute works the same as source attribute as the image element; it gives path to the media file.<br>
The `controls` attribute give control of the video to the user. You `controls` is the default browser's control features or you can code your own using JavaScript 
3. Why is it important to have fallback content inside the `<video>` element?<br>
Video elements in nature will transmit more data than most. For this reason, the likelihood of it running into an issue is high. Fallback content will display in case the video cannot be loaded.
4. Write a very short story where `<audio>` and `<video>` are characters.<br>
Mr. Video was a complex actor with multiple lawyers, he was a shining star everyone could see and had a great stage presence because of loud he could be. Audio Jr, Mr.Video's underwriter, did not have the skill to shine bright and be seen by everyone, but it was much easier for him to travel places and be heard.

## A Complete Guide To Grid

1. How does Grid layout differ from Flex?<br>
Flex is one directional. Everything in flex will push by default to a specific side of the container. Grid is two directional. They both have their times where individually, each will be suited better for certain layout goals.
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.<br>
**Grid container** - Grid container are the element that will be assigned to house the internal grid elements. This is the outer most element which the attribute `display: grid` will be applied to.<br>
**Grid item** - These are the direct children elements of the Grid container. These are also work like container elements but for the individual items you want to group and associate into a grid area.<br>
**Grid line** - Grid lines are the boundaries that separate the grid cells. Grid cells can be sized by row/columns and multiple cells can be coupled together house the displayed items.<br>

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?<br>
Because different media files can differ in properties that affect image resolution, different devices will load certain files better. Screen resolution can point to the type of device being used to load the image and can display certain images that are optimized for visualizes per device.
2. Define the following **<img>** attributes `srcset` and `sizes`. Write an example of how they are used.<br>
The `srcset` and `sizes` attributes help the browser be more flexible when displaying images on different resolution sizes. `scrset` is used for letting the browser know which elements are available for rendering. Size attribute provides the condition that must be met to switch between the source sets in `srcset`.
3. How is `srcset` more helpful for responsive images than CSS or JavaScript?<br>
Because `srcset` is an HTML attribute of the media element, which allows for the browser to handle the selection process, keeping your CSS and JavaScript lighter.

## Things I want to know more about
