```
							__________               __                 
							\______   \__ __   ____ |  | __ ___________ 
							 |       _/  |  \_/ ___\|  |/ // __ \_  __ \
							 |    |   \  |  /\  \___|    <\  ___/|  | \/
							 |____|_  /____/  \___  >__|_ \\___  >__|   
									\/            \/     \/    \/    
									
									
```
# objects.media
@stubbornella’s media object implemented in Rucker style

The Media object module is RuckerCSS implementation of [Nicole Sullivan](https://twitter.com/stubbornella)’s <cite>media object</cite>.

## Installation

Import the object's file in the corresponding layer

## Usage

Basic usage of the Media object:

    <div data-obj="media">
        <img src="/path/to/image.png" alt="" data-obj="media__img" />
        <div data-obj="media__body">
            <p>Text content goes here.</p>
        </div>
    </div>

## Options

Other, optional attributes can supplement the base media one:

* `[media--stkd]`: sticked - remove the space between the image and body.
* `[media--{modifier(xs,sm,md,lg,hg)}]`: alter the spacing between the image and
  body.
* `[media--rev]`: reverse the horizontal rendered order of the image- and
  text-content. Place the image to the right side.
