Boney
=============================

Themes based on the Skeleton boilerplate for Pico CMS.

It is essentially the default Pico theme with Skeleton grafted on and the redudant CSS and markup pared away. Skeleton styles were generally kept instead of Pico ones, but then if you're using a minimal boilerplate like Skeleton, you're probably going to change the default styles anyway.

It's probably a bit sloppy, but it lets me skip a chunk of work when building a responsive website on top of PicoCMS. Thought it might be useful to others as well.

The 1280px version extends Skeleton using the column-width calculations found in this [tutorial](http://webdesign.tutsplus.com/tutorials/building-a-responsive-layout-with-skeleton-widescreen--webdesign-7473).

### Installation

1. Clone this repository to a new folder. Move either the "boney" or "boney1280" folder to the Pico themes directory.
2. Open `config.php`, from the root Pico directory, and rename the theme: `$config['theme'] = 'boney';` or `$config['theme'] = 'boney1280';` (depending on which one you want to use).

### About Skeleton

[Skeleton](http://www.getskeleton.com/) is minimalist responsive CSS boilerplate.

### About Pico

[Pico](http://picocms.org/) is a stupidly simple & blazing fast, flat file CMS.
