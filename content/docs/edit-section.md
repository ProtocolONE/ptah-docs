---
title: Edit section content
bookToc: true
---

# On-page editing
***

The Ptah Builder makes editing pretty intuitive. You can change content and its properties right on the page in Preview Area and everything will be automatically saved.

{{< hint >}}
On hover over a Block or an Element, you can view an icon to set properties at the top-left corner.
{{< /hint >}}

TODO image интерфейс или иллюстрация с этими иконками для секции, блока и элемента
{{< figure src="/images/tmp.png">}}

{{< hint >}}
All of the elements in Preview Area are draggable. If you need to rearrange elements inside of the block, click and hold at the element, then drag and drop the element to the preferred position.
{{< /hint >}}

TODO animation перетаскивание элемента в строке и в столбце

## Adjust block properties
***

[Set up the size and indents.](/docs/size/)

## Add an element to the section
***

{{< hint >}}
To add an element to the section, hover over a block where you want to add a new element and click on the *Add element icon* in Preview Area.
{{< /hint >}}

## Adjust element properties
***

{{< hint >}}
To view and customise an element properties, select the element by click and press the *Edit icon* on Preview Area or just double click on the element.
{{< /hint >}}

### **Text**
***

{{< tabs "elements-base" >}}
{{< tab "TEXT" >}}

[To adjust a page fonts, use the page settings.](/docs/fonts)

**Text properties:**

- **Size** - the font size
- **Line** - the line height (the vertical distance between lines of text)
- **Color** - the text color
- **Link Color** - the color of the link
- **Link Hover Color** - the color of the link on hover
- **Underline** - apply a word underline
- **Underline Hover** - show a word underline on hover
- **Open new window** - use a new browser tab to open a link

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}

{{< tab "ICON WITH TEXT" >}}

[To adjust a page fonts, use the page settings.](/docs/fonts)

**Text and icon properties:**

- **Size** - the font size
- **Line** - the line height (the vertical distance between lines of text)
- **Color** - the text color
- **Visible** - use icon image
- **Icon** - the icons list
- **Icons width** - the icon size
- **Icons color** - the icon color

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< /tabs >}}

### **Buttons**
***

Call-to-action buttons are some of the most significant elements on your landing page. 

A call-to-action button is a piece of text or an image, that tells your audience what you want them to do next. 
For instance, after clicking on the call-to-action button it scroll down to the sign up form section.

{{< hint >}}
To add an action to the button, first of all, select the button in Preview Area and click on the *Link icon* at the top-left corner.

In the opened tooltip select one of the actions:

- **Open URL** - while clicking on the button, user is redirected to the specified web page.
    - Enter the link in the *URL field*.
    - Enable the *Open in new window*, to use a new browser tab to open a link.
    - Click *Done*.
- **Open video popup** - while clicking on the button, the video popup is displayed.
    - Enter the link to the YouTube video resource in the *Video field*.
    - Click *Done*.
- **Scroll into section** - while clicking on the button, the landing page is scrolled to the particular section.
    - Choose which section to scroll to.
    - Select a scroll behaviour: Auto, Instant, Smooth.
    - Click *Done*.
{{< /hint >}}

TODO image интерфейс попап с настройками события для кнопки с выбранными значениями: Action - Scroll into section, Scroll to - FromCenterFantasy, Scroll behavior - Smooth

**Button properties:**

- **Placeholder text** - the placeholder text
- **Size** - the text size
- **Line** - the line height (the vertical distance between lines of text)
- **Text** - the text color
- **Hover** - the text color on hover
- **Button color** - the button color
- **Hover color** - the button color on hover
- **Border radius** - the border radius
- **Border style** - the border color and style: solid, dashed, dotted
- **Border hover** - the border color and style on hover: solid, dashed, dotted
- **Button image** - the button background image
- **Hover image** - the button image on hover
- **Stretch to fit** - display the image at the full height of the button
- **Corner radius** - the button's corners radius
- **Hover animation** - the animation on hover: none, tada, shake, bounce

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}

### **Social networks**
***

Social icons are links to your social accounts. Use the [Ptah integration with Open Graph](/docs/seo/#social-media-links) to set up displaying in social posts.

**Social networks properties:**

- **Icons width** - the social network icon size
- **Icons color** - the social network icon color
- **Background color** - the background color of the icons' element
- **Open links in new window** - use a new browser tab to open a link

The list of social networks' names and links:

- **Facebook**
- **Instagram**
- **Vk**
- **Twitter**
- **YouTube**
- **Discord**
- **Kickstarter**
- **Wechat**

{{< hint >}}
To add a social link, click on the Link icon to the right of the network name. In the opened tooltip enter the network link and click *Close*.
{{< /hint >}}

TODO image интерфейс с попапом с введенной ссылкой на соцсеть

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}

### **Images and Videos**
***

{{< hint >}}
To upload or replace an image, drag and drop the image to the Image upload button or to the specific position on the page in Preview Area.
{{< /hint >}}

TODO анимация с drag-n-drop на кнопку загрузки картинки и на страницу

{{< tabs "elements-images-videos" >}}
{{< tab "IMAGE" >}}
- **Image URL** - the image file or the link to the image resource

    **To upload an image from your computer:** drag and drop an image to the Image upload button or to the specific position on the page in Preview Area.
    
    **To use an external link to the image:** enter the link to the image file
    TODO animation перетаскивание картинки

- **Stretch to fit** - display the image at the full height of the element

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< tab "VIDEO" >}}
- **Video URL** - the video file or the link to the video resource
- **Loop** - put a video on loop
- **Autoplay** - play video on page load
- **Show/hide controls** - display video controls
- **Show/hide related videos** - display related videos at the end

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< /tabs >}}

### **Game parameters**
***

{{< tabs "elements-game" >}}
{{< tab "AVAILABLE PLATFORMS" >}}

- **Icons width** - the platform icon size
- **Icons color** - the social icon color

The list of platforms' names:

- **Windows**
- **Apple**
- **Linux**
- **Steam**
- **GOG Galaxy**

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< tab "AGE RESTRICTIONS" >}}

- **Icons width** - the platform icon size

The list of the age ratings:

- **Age**
- **PEGI** 
- **USK**
- **Steam**

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< /tabs >}}

### **HTML elements**
***

{{< tabs "elements-html" >}}
{{< tab "SPACER" >}}
You can edit a spacer size using the transformation tool.

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< tab "TIMER" >}}
- **Set timer** - the ending date
- **Time zone** - the UTC time zone
- **Labels** - display the labels: Days, Hours, Minutes, Seconds
- **Position** - the labels position
- **Labels language** - the labels language
- **Size** - the font size
- **Line** - the line height (the vertical distance between lines of text)
- **Color** - the text color
- **Background Color** - the background color of the element
- **Tile Color** - the background color of every parts

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< tab "IFRAME" >}}

- **URL** - the link to the external resource

[Learn about spacing and how to edit indents for the element](/docs/size/)

TODO image интерфейс или иллюстрация с настройками какие за что отвечают
{{< figure src="/images/tmp.png">}}
{{< /tab >}}
{{< /tabs >}}

***

{{< hint info >}}
**Next steps**
{{< /hint >}}

- [Spacing on the page and adjust size](/docs/size/)
- [Customise the alignment of elements](/docs/align/)
- [Edit a background image and video](/docs/background/)

***

{{< questions >}}{{< questions-text >}}{{< /questions-text >}}{{< /questions >}}