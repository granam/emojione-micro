#![EmojiOne Logo](http://git.emojione.com/assets/logo.png) EmojiOne
> bringing you [emojione.com](http://emojione.com/) & [emoji.codes](http://emoji.codes/)

*The web's first and only complete open source emoji set. It is 100% free and super easy to integrate.*

# Just an extraction
This library provides only CSS to style EmojiOne and tools in [few languages](./lib) to convert *HTML-to-image-and-back*.

## Workflow
1. convert an [UTF-8 emoji](http://getemoji.com/) 😎 into its [Emoji One](https://emojione.com) image equivalent <img src="https://cdn.jsdelivr.net/emojione/assets/svg/1f60e.svg" width="24"> by one of conversion methods
2. style it with [provided CSS](./assets/css)
3. let download images from [public CDN JSDelivr](http://www.jsdelivr.com/#!emojione) (Emoji One official partner)
4. be happy

## Installation

#### Composer
```
$ composer require granam/emojione-micro
```

##### Note about namespace
The original `Emojione` namespace is used to provide compatibility and made eventual switch to original library easier.

## Where is the original?

This library is just an extraction of large [official library](https://github.com/Ranks/emojione) of version 2.2.7
(original latest version is [![Latest Stable Version](https://poser.pugx.org/emojione/emojione/v/stable)](https://packagist.org/packages/emojione/emojione)).
Whatever you think you need, you will find it there.

## PHP Usage Examples

**[toShort\($str\)](http://git.emojione.com/demos/latest/phptoshort.php)** - _native unicode -> shortnames_

This demo shows you how to take native unicode emoji input, such as that from your mobile device, and translate it to their corresponding shortnames. (we recommend this for database storage)

**[shortnameToImage\($str\)](http://git.emojione.com/demos/latest/phpshortnametoimage.php)** - _shortname -> images_

This demo shows you how to take input containing only shortnames and translate it directly to EmojiOne images. (when displaying the unified input to clients)

**[unicodeToImage\($str\)](http://git.emojione.com/demos/latest/phpunicodetoimage.php)** - _native unicode -> images_

This demo shows you how to take native unicode emoji input, such as that from your mobile device, and translate it directly to EmojiOne images. (would be great for a live editor preview)

**[toImage\($str\)](http://git.emojione.com/demos/latest/phptoimage.php)** - _native unicode + shortnames -> images (mixed input)_

This demo shows you how to take input containing both native unicode emoji and shortnames, and translate it into EmojiOne images for display.

## Licenses

### EmojiOne Artwork

*  Applies to all PNG and SVG files as well as any adaptations made.
*  The following applies to artwork included in EmojiOne GitHub libraries versions < 2.0.0.
  *  License: Creative Commons Attribution-ShareAlike 4.0 International
  *  Human Readable License: http://creativecommons.org/licenses/by-sa/4.0/
  *  Complete Legal Terms: http://creativecommons.org/licenses/by-sa/4.0/legalcode
*  The following applies to artwork included in EmojiOne GitHub libraries versions >= 2.0.0.
  *  License: Creative Commons Attribution 4.0 International
  *  Human Readable License: http://creativecommons.org/licenses/by/4.0/
  *  Complete Legal Terms: http://creativecommons.org/licenses/by/4.0/legalcode


### EmojiOne Non-Artwork

*  Applies to the Javascript, JSON, PHP, CSS, HTML files, and everything else not covered under the artwork license above.
*  License: MIT
*  Complete Legal Terms: http://opensource.org/licenses/MIT
