*******
Options
*******

.. toctree::
   :hidden:
   :glob:

   *


.. highlight:: javascript

The Galleria options covers most of the gallery customizations you will need for each implementation. 
Below you will find a summary of all options available. Click on a option title for more explanations and examples.

These options are the standard options that you can use for all themes. However, themes can add new options and set/modify default values on their own. Please check each theme documentation for full coverage. Custom options for each theme starts with an underscore.


Using options
=============

Galleria options are defined using a flat object during initialization.::

    $('#galleria').galleria({
        preload: 3,
        transition: 'fade',
        imageCrop: true
    });


List of options
===============

- :doc:`autoplay` Sets Galleria to play slidehow when initialized.

- :doc:`carousel` Toggle the creation of a carousel.

- :doc:`carouselFollow` Defines if the carousel should follow the image.

- :doc:`carouselSpeed` Carousel animation speed in milliseconds.

- :doc:`carouselSteps` Defines how many "steps" the carousel should take on
  each nav click.

- :doc:`clicknext` Helper for adding a click event on the entire stage to move
  forward.

- :doc:`dataConfig` Defines how Galleria should parse the HTML. Useful for adding custom HTML captions.

- :doc:`dataSelector` Defines the selector Galleria should look for in the
  source.

- :doc:`dataSource` Defines the Galleria data, or the HTML source where the
  data is found.

- :doc:`debug` Set this to false to prevent debug messages.

- :doc:`easing` Defines the easing mode globally.

- :doc:`extend` Add custom functionality to the gallery.

- :doc:`height` Manually set a gallery height.

- :doc:`idleTime` Defines how long delay before Galleria goes into idle mode.

- :doc:`idleSpeed` Defines the animation speed in milliseconds when entering/exiting idle mode.

- :doc:`imageCrop` Defines how Galleria will crop the image.

- :doc:`imageMargin` Sets a margin between the image and the stage.

- :doc:`imagePan` Toggles the image pan effect.

- :doc:`imagePanSmoothness` Defines how smooth ( and CPU consuming ) the pan
  effect should be.

- :doc:`imagePosition` Positions the image.

- :doc:`keepSource` Lets you keep the source elements.

- :doc:`lightbox` Helper for attaching a lightbox when the user clicks on an image.

- :doc:`lightboxFadeSpeed` Defines how fast the lightbox should fade.

- :doc:`lightboxTransitionSpeed` Defines how fast the lightbox should animate.

- :doc:`maxScaleRatio` Defines how much Galleria is allowed to scale.

- :doc:`minScaleRatio` Defines how much Galleria must scale.

- :doc:`overlayOpacity` Sets how transparent the overlay should be.

- :doc:`overlayBackground` Defines the background color of the overlay.

- :doc:`pauseOnInteraction` Toggles if Galleria should stop playing if the
  user navigates.

- :doc:`popupLinks` Open Image links in new windows.

- :doc:`preload` Defines how much Galleria should preload.

- :doc:`queue` Defines if Galleria should queue the slideshow.

- :doc:`show` Lets you start the slideshow at any image index.

- :doc:`showInfo` Toggles the caption.

- :doc:`showCounter` Toggles the counter.

- :doc:`showImagenav` Toggles the image navigation arrows.

- :doc:`thumbCrop` Same as image_crop for thumbnails.

- :doc:`thumbFit` Lets you fit thumbnails according to width.

- :doc:`thumbMargin` Same as :doc:`imageMargin` for thumbnails.

- :doc:`thumbQuality` Defines if and how IE should use bicubic image rendering
  for thumbnails

- :doc:`thumbnails` Sets how and if thumbnails should be created.

- :doc:`transition` Defines what transition to use.

- :doc:`transitionInitial` Sets a different transition on the the first image.

- :doc:`transitionSpeed` Defines the speed of the transition.

- :doc:`width` Manually set a gallery width.
