# Adding Images
To add an image into the page you need to use an < img >
< img src="images/lemon-posset.jpg" alt="Lemon Posset" >
- height This specifies the height of the image in pixels.
- width This specifies the width of the image in pixels.

< figure > Images often come with captions. HTML5 has introduced a new < figure > element to contain images and their caption
so that the two are associated. 

The < figcaption > element has been added to HTML5 in order to allow web page authors to add a caption to an image.
You should save images at the size you will be using them on the web page and in the appropriate format.

# color property
The color property allows youto specify the color of text insidean element. You can specify any color in CSS in one of three ways:
rgb values , hex codes ,color names 

# background-color
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names 

- When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

# Specifying Typefaces
 
- The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the
name of the typeface you want to use.

- The font-size property enables you to specify a size for the font.
- @font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if
it is not on the user's machine.

- The font-weight property allows you to create bold text. There are two values that this property commonly takes: normal , bold
- If you want to create italic text, you can use the font-style property. There are three values this property can take: normal , italic,oblique

- The text-transform property is used to change the case of text giving it one of the following values: uppercase , lowercase , capitalize 

- The text-decoration property allows you to specify the following values:none ,underline ,overline ,line-through,blink

- The line-height property sets the height of an entire line of text

- The text-align property allows you to control the alignment of text

* there are two pseudoclasses that allow you to set different styles for links that have and have not yet been visited.
:link
This allows you to set styles for links that have not yet been visited. 

:visited 
This allows you to set styles for links that have been clicked on. 

:hover
This is applied when a user hovers over an element with a pointing device such as a mouse. This has commonly been used to change the appearance of links and buttons when a user
places their cursor over the

:active
This is applied when an element is being activated by a user; for example, when a button is being pressed or a link being clicked.


***************************************************************************
# JPEG vs PNG vs GIF

- Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

- Compression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression. This is not the case in lossy compression i.e. data loss in lossy compression is irreversible. Lossy compression algorithms always have a superior compression ratio (the ratio of size of compressed image to original image) as compared to lossless compression

- JPEG is a lossy compression
- PNG is a lossless image format using DEFLATE compression.
- GIF is also a lossless image format

## Transparency
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.

- JPEG images don’t support transparency and are hence not usable for such cases.
- PNG images support transparency
- GIF images support transparency 
