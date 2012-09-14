# ImageDeuce - A PHP class for image comparison

ImageDeuce is a php implementation of the perceptual hashing algorithm (http://phash.org) which stores a fingerprint of an image as a hash and allows
comparing the similarity of images by comparing the hashes. I've added the ability to also test if an image is a rotated or flipped version of another.

## Examples:

```php
<?php
$I = ImageDeuce::Instance();
```