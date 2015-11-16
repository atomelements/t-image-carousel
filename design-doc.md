The image carousel is a simple element used for sliding a series of images. It makes use of [swipe](https://github.com/thebird/Swipe). No width needs to be specified for this element; it takes the width of its container. Dots are shown near the bottom to give an indication about navigation in the carousel.

## Data Needed

**1. Height**
* Used to define the height of the carousel.
* Shown as an input field in the property panel.
* Possible range of values(in pixels): 300 to 900.
* Default value(in pixels): 400.

**2. Data Arrays**
* These are the actual input to the carousel for displaying. There is an array per image to display.
* Each array contains 3 strings. The first is for the image url. Second is for the image title. Third is for the image subtitle. Titles and subtitles are optional.
* A minimum of two images need to be present for the carousel to be meaningful. Currently no maximum number of images is defined, but showing more than 5 images using the carousel is not recommended. 

## Properties

**1. Transition Speed**
* Used to define how fast one image changes into the other.
* Shown as an input field in the property panel.
* Possible range of values(in milliseconds): (?)
* Default value(in milliseconds): 300 

**2. Display Time**
* Used to define how long an image stays on screen before changing to the next one.
* Shown as an input field in the property panel.
* Possible range of values(in milliseconds): (?).
* Default value(in milliseconds): 3000 

**3. Auto-forwarding**
* Used to define whether images transition automatically from one to the next.
* Shown as a checkbox in the property panel.
* Default Value: Checked.

**4. Disable Navigation**
* Disables scrolling the carousel by users. If this setting is activated, then arrows on the sides of the carousel don't appear.
* Shown as a checkbox in the property panel.
* Default Value: Unchecked.

**5. Loop**
* Used to configure whether the images in the carousel loop infinitely or stop after all images have been displayed once.
* Shown as a checkbox in the property panel.
* Default Value: Checked.

**6. Show Labels**
* Used to configure whether titles and subtitles for the images are to be displayed or not.
* Shown as a checkbox in the property panel.
* Default Value: Unchecked.

## Some usability references
* [Designing Effective Carousels: Create a Fanciful Amusement, Not a House of Horrors](http://www.nngroup.com/articles/designing-effective-carousels/)
* [Don’t Use Automatic Image Sliders or Carousels, Ignore the Fad](http://conversionxl.com/dont-use-automatic-image-sliders-or-carousels-ignore-the-fad/)
* [8 UX Requirements for Designing a User-Friendly Homepage Carousel](http://baymard.com/blog/homepage-carousel)
