---
title: Background Properties
bookToc: true
---

# Background properties
***

There are several ways to fill a background:

- [Color fill](#color-fill-and-opacity)
- [Gradient](#gradient)
- [Background image](#background-image)
- [Fullscreen video background](#full-screen-video-background)
- [Color overlay](#add-a-color-overlay-to-the-background)
- [Fixed and parallax background image](#fixed-and-parallax-background-image)
- [Repeat an image for all sections](#repeat-an-image-for-all-sections)
- [Remove a background image](#remove-a-background-image)

***

You can apply custom settings for the background of a block, section or page.

**How to edit a section background properties**
***

{{< hint >}}
To edit a section background, you can click the *Background icon* on hover over the section in Preview Area or click the same icon on Settings Panel at the end of the section's title.
{{< /hint >}}

TODO image интерфейс с настройками фона секции

**How to edit a background of multiple sections**
***

Grouping sections helps you to make the same background for all child sections.

{{< hint >}}
To make a group, select some sections while holding the key: **Command** for macOS or **Control** for Windows, and click  the *Group selected button*.

Now you can set a background of the group clicking on the *Image icon* at the end of the group's name. The group background replaces their child sections' backgrounds.
{{< /hint >}}

TODO image интерфейс настройки фона для группы

**How to edit a page background**
***

{{< hint >}}
To adjust a page background, click the *Settings icon* on the top menu and choose the *Visual tab*.
{{< /hint >}}

TODO image интерфейс настройки фона всей страницы

## Color fill and opacity
***

{{< hint >}}
To add a solid color, open background settings of the section (or block) and click the *Color* in Settings Panel. 
Now you can pick the color in the Color Picker.
{{< /hint >}}

{{< hint warning >}}
- Checking the opacity in the Color Picker changes your background color from transparent to solid. To get a solid color, check the opacity at 100%.
- To view the color background, examine that there is no image or video background and the overlay color set at 0%.
{{< /hint >}}
TODO image интерфейс значения настроек с полупрозрачностью и в превью видна полупрозрачность

You can make the same steps to apply a color to the whole page on the Page Settings in the *Visual tab*.

## Gradient
***

Increase the visual appeal with the use of gradients.

{{< hint >}}
To add a color gradient, open the section (or block) properties on Settings Panel and press the *Plus icon* to add new color.
{{< /hint >}}

TODO animation

{{< hint warning >}}
- It's possible to add up to 4 colors to the linear gradient.
- Adjust the colors opacity to make a solid or transparent gradient background.
{{< /hint >}}

## Background image
***

### Add a background to a section or block
***

{{< hint >}}
To insert a background image to the section (or block), click the *Background icon* on hover the section in Preview Area (or use the same icon on Settings Panel at the end of the section's title) and upload the image using the *Upload Image button* or enter the link to the image resource.
{{< /hint >}}

TODO animation

{{< hint >}}
Now you can upload an image in two ways:

- using the Upload Image button,
- entering a link to the image resource file in the Image field.
{{< /hint >}}

TODO image интерфейс с указателями как загружать картинку

Set the position of the background image:

- **Left** - moves an image horizontally.
- **Top** - moves an image vertically.

{{< hint warning >}}
To center an image, click the round icon at the center of the preview image area in Settings Panel.
{{< /hint >}}
TODO animation

Configure the display of the image:

- **Normal** - displays the original image.
- **Tile vertically** - uses an image and repeat it vertically.
- **Tile horizontally** - uses an image and repeat it horizontally.
- **Tile both** - uses an image and repeats it multiple times both vertically and horizontally.
- **Cover** - displays the image at the full width of the section. This mode increases or decrease the width of the picture to fit the width of the browser window. To set the image vertical position, adjust the Top parameter value.
- **Stretch** - displays the image at the full height of the section. This mode may affect image quality because this mode increases or decrease the height of the picture to fit the height of the section. To set the image horizontal position, adjust the Left parameter value.

### Add a background to the page
***

You can use an image as a background for the whole page. 

{{< hint >}}
Click the *Settings icon* on the top menu and choose the *Visual tab*.

Now you can upload an image in three ways and click *Save*.

- using the Upload Image button,
- entering a link to the image resource file in the Image field,
- drag and drop an image to the Image upload button or to the specific position on the page in Preview Area.

TODO image интерфейс с указателями как загружать картинку
{{< /hint >}}

Set the position of the background image:

- **X** - moves an image horizontally.
- **Y** - moves an image vertically.

## Full-screen video background
***

You can use a video background instead of image to a section or page.

{{< hint >}}
Open the section's background Properties to check **Use video as background** and upload a video file or enter the link to the resource file.
{{< /hint >}}

TODO image интерфейс настроки для секции с видео в качестве фона

{{< hint >}}
To add a video background to the page, open the Page Settings and upload a video file or enter the link to the resource file in the *Visual tab*.
{{< /hint >}}

TODO image интерфейс настроки для всей страницы с видео в качестве фона

## Add a color overlay to the background
***

Apply a color over an image or video to make a background more contrast for foreground elements. It also helps to make a text more readable on the image or video.

{{< hint >}}
To add a color filter over the image or video for the section, you can adjust the Overlay Color in Settings Panel and increase or decrease its opacity level.
{{< /hint >}}

TODO animation

## Fixed and parallax background image
***

Fixed and parallax effects are design techniques:

- when using a fixed background image, the image will remain static, while the content will move over the image as your scroll down the page.
- when using a parallax background image, both the image and the content will move as your scroll down the page, but at different speeds.

{{< hint >}}
To add a fixed background to the page:

- [Add a background to the page.](#add-a-background-to-the-page)
- Enable the *Fixed while scrolling* and click *Save*.
{{< /hint >}}

TODO анимация с фиксированным фоном на всей странице

{{< hint >}}
To add a fixed background to the page:

- [Add a background to the section.](#add-a-background-to-a-section-or-block)
- Enable the Parallax on background in Settings Panel.
- Open your landing page in the Preview mode to see the parallax effect clicking the *Preview icon* at the top menu.
{{< /hint >}}

TODO интерфейс с настройкой Parallax on background

## Repeat an image for all sections
***

You can upload a background image and repeat it for all sections on the page.

TODO image пример одинакового фона для всех секций

{{< hint >}}
- [Add a background to the page.](#add-a-background-to-the-page)
- Enable the *Background fill* and click *Save*.
{{< /hint >}}

TODO image интерфейс картинка с настройками фона с параметром Background fill

## Remove a background image
***

{{< hint >}}
To remove a background image from a section (or block) open Settings Panel for and click the *Remove icon*.
{{< /hint >}}

TODO image интерфейс настройки с конкой удаления изображения

***

{{< hint info >}}
**Next steps**
{{< /hint >}}

- [Spacing on the page and adjust size](/docs/size/)
- [Customise the alignment of elements](/docs/align/)
- [Edit a background image and video](/docs/background/)

***

{{< questions >}}{{< questions-text >}}{{< /questions-text >}}{{< /questions >}}