
# Welcome to the Read05 page ..

**today we will talk about 3 topics..**

# 1. How to add images to pages In Html?

Images can be easily inserted at any section in an HTML page. To insert image in an HTML page, you should use the <'img'> tags. It is an empty tag, containing only attributes since the closing tag is not required.

Do not forget that you should use the  **(<'img'>)** tag inside **(<'body'>…<'/body'>)** tag. The src attribute is used to add the image **(source)**  URL of the image. The **(alt)** attribute is for adding alternate text, width for adding width, and height for adding the height of the image.

`Example:`

``<img src="/html/images/test.png" alt="Simply Easy Learning" width="200"``

**Three Rules for Creating Images :**

1. Save images in the right format.
2. Save images at the right size.
3. Use the correct resolution.

**Tools to Edit & Save Images..**

- Image Formats: JPEG .

*is a commonly used method of lossy compression for digital images, particularly for those images produced by digital photography. The degree of compression can be adjusted, allowing a selectable tradeoff between storage size and image quality. JPEG typically achieves 10:1 compression with little perceptible loss in image quality*

- Image Formats: GIF .

*Conceptually, GIF files have a fixed-sized graphical area filled by zero or more images. Some GIF files divide the fixed-sized graphical area or blocks into sub-images capable of functioning as animated frames in case of animated GIF. The GIF format uses the pixel depths of 1 to 8 bits to store the bitmap data. RGB colour model and palette data are always used to store the images. Depending upon the version, a fixed-length header (“GIF87a” or “GIF89a”) defines the start of a typical GIF file.*

![image](https://2.bp.blogspot.com/-YMnp4TGhkxI/V8V93Z76nCI/AAAAAAAAP_c/IjZDrss0xKIXFh9w6QU1QRBq8Ma9VfA8QCLcB/s640/1.gif)


# 2. How to specify colors in CSS?

> "Color can really bring your pages to life"

**Three Ways to specify colors in css:**

1. Color Keywords.

*The first and easiest way to specify a color is using one of the 17 predefined color keywords.*

![image](https://images.slideplayer.com/32/10045895/slides/slide_4.jpg)

2. RGB Color Values.

*RGB values are specified for each of the key colors (red, green, blue), using a value between 0 and 255 or a percentage value. A higher value means more of that color. RGB works the opposite of CMYK, in that none of the colors actually equals black and all of the colors equals white.*

**The CSS syntax for using RGB colors:**

``p { color: rgb(0, 0, 0); } /* black */ ``

![image](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/766914ca-7d34-4b62-a21f-0e63a51fcdaa/d7wx5jh-52218a72-2419-4081-8eb9-f9090635c383.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvNzY2OTE0Y2EtN2QzNC00YjYyLWEyMWYtMGU2M2E1MWZjZGFhXC9kN3d4NWpoLTUyMjE4YTcyLTI0MTktNDA4MS04ZWI5LWY5MDkwNjM1YzM4My5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.W3snM2ENmd_GlxLckR5dlh7oNeyVhgMY4pW6hUcZjS8)


3. Hexadecimal Color Values.

*The most common way to specify colors in CSS is to use their hexadecimal (or hex) values. Hex values are actually just a different way to represent RGB values. Instead of using three numbers between 0 and 255, you use six hexadecimal numbers. Hex numbers can be 0-9 and A-F. Hex values are always prefixed with a # symbol.*

``p { color: #000000; }	/* black */``

![img](https://htmlcolors.com/img/hex-color.jpg)


# 3.The properties that allow you to control the appearance of text ..

- Text Color.

``h1 { color: green;}``

- Text Alignment.

``h1 { text-align: center;}``

- Teaxt Decoration.

``h1 { text-decoration: overline;}``

- Text Transformation.

``p.uppercase { text-transform: uppercase;}``

- Text Spacing.

``h1 { letter-spacing: 3px;}``

- Text Shadow.

``h1 { text-shadow: 2px 2px;}``



