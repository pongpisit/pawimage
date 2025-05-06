# pawimage

Cloudflare Image Transformation Demo

This demo webpage showcases Cloudflare's image transformation capabilities using URL parameters. It demonstrates various image transformations, including resizing, adjusting quality, adding blur, brightness, contrast, flipping, rotating, sharpening, and saturation adjustments.

Live Demo

Access the live demo by opening the provided HTML file in your web browser.

Image Source

All transformations use the following source image:

https://pawimage.pongpisit.com/src/alfa.jpg

Available Transformations

Resize: Change image dimensions using the width parameter.

Quality: Adjust the image quality to optimize file size and performance.

Blur: Apply a blur effect to the image.

Brightness: Modify the brightness level.

Contrast: Adjust the contrast intensity.

Flip: Flip the image horizontally or vertically.

Rotate: Rotate the image by 90, 180, or 270 degrees.

Sharpen: Enhance image sharpness.

Saturation: Change image saturation, including grayscale conversion.

How It Works

Cloudflare image transformations are applied directly via specially-formatted URLs. The general structure is:

/cdn-cgi/image/<OPTIONS>/<SOURCE-IMAGE>

Example:

/cdn-cgi/image/width=200/https://pawimage.pongpisit.com/src/alfa.jpg

Requirements

A domain proxied by Cloudflare with Image Transformations enabled.

Documentation

For detailed information, refer to the official Cloudflare Images Documentation.
https://developers.cloudflare.com/images/transform-images/transform-via-url/
