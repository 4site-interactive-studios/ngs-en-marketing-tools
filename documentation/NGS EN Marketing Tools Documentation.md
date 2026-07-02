# Marketing Tools Documentation

## Template
The template is called “4Site Main Email Template” and can be found in the “4Site Templates” folder in the Templates section of Marketing Tools.

The template contains wrapping code and global styling for the email structure and blocks. It does not contain any content. This allows you to use the same template for any email without needing to maintain multiple templates.

There are a few global configuration options available in the template. These allow you to set a global style for the email but can be overwritten in individual blocks using the Rich Text Editor. You can access them in the “Global” tab while building an email.

The options are: 

* Background color  
* Text color  
* Headings color  
* Links color  
* Body font  
* Headings font

**Unfortunately, changes to a template are not applied to Emails that are already built using that template.** If you need to make a change to a template (including altering its Variable Replacements), then you will need to rebuild any email using it from scratch. This includes the Reference Emails.

## Blocks

Blocks are content sections that can be inserted into the template and customized to build out your email. Many of the blocks are very flexible and can fit multiple different use cases and designs by adjusting their settings. You can also use several individual blocks together to build out a larger section with a consistent design.

All blocks have their own unique configuration options as well as standard options that all blocks share. The standard options are:

* Background Color  
* Padding Above  
* Padding Below.

We have built 17 blocks (in no specific order) which can be found in the “4Site Blocks” folder:

* Header Logo Block  
* Text Block  
* Button Block  
* Image With Caption  
* Two Image Columns Block  
* Three Image Columns Block  
* 2 Columns Image and Text Block  
* Signature Block  
* Footer Block  
* Call To Action Block  
* Callout With Image Background  
* Divider  
* Highlighted Text  
* Question Response  
* Side-By-Side Image and Text Block  
* Spacer Block  
* Testimonial Block

Below we go into more detail on each block, its configuration options, and any best practices for using it.

### Header Logo Block

The Header Logo block contains an image with a hyperlink. It is typically used for the image at the top of your email, which may be the NGS logo or an “email header” image.

#### Options

| Name                | Type      | Description                                                                                                                                                 |
|:--------------------|:----------|:------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color    | Select    | The background color of the block. Choose from predefined options of your brand.                                                                            |
| Padding Above       | Text      | The spacing above the block. Use a numerical value in pixels                                                                                                |
| Padding Below       | Text      | The spacing below the block. Use a numerical value in pixels                                                                                                |
| Image URL           | Image URL | The image to be displayed                                                                                                                                   |
| Dark Mode Image Url | Image URL | The image to be displayed when an email client is using dark mode. If you do not have a specific dark mode image, you should put the regular image in here. |
| Image Alt Text      | Text      | The text that will be read by screen readers for this image.                                                                                                |
| Image Width         | Text      | The width of the image. A numerical value in pixels. For full width images, enter 600\. For other images, use the size that looks best.                     |
| Image Link URL      | Link      | The URL that will be opened when the image is clicked.                                                                                                      |

### Text Block

The Text Block contains a Rich Text Editor where you can freely add text and style it using Engaging Networks’ text editor.

#### Options

| Name             | Type             | Description                                                                      |
|:-----------------|:-----------------|:---------------------------------------------------------------------------------|
| Background Color | Select           | The background color of the block. Choose from predefined options of your brand. |
| Padding Above    | Text             | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below    | Text             | The spacing below the block. Use a numerical value in pixels                     |
| Text             | Rich Text editor | Enter and format text for your email.                                            |

### Button Block

The Button Block contains a hyperlink styled as a button. Its sizing, colors, and text can be edited.

#### Options

| Name                      | Type   | Description                                                                                                                                                                          |
|:--------------------------|:-------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color          | Select | The background color of the block. Choose from predefined options of your brand.                                                                                                     |
| Padding Above             | Text   | The spacing above the block. Use a numerical value in pixels                                                                                                                         |
| Padding Below             | Text   | The spacing below the block. Use a numerical value in pixels                                                                                                                         |
| Button Background Color   | Select | The background color of the button. Choose from predefined options of your brand.                                                                                                    |
| Button Border Color       | Select | The border color of the button. Choose from predefined options of your brand.                                                                                                        |
| Button Text Color         | Select | The text color of the button. Choose from predefined options of your brand.                                                                                                          |
| Button Text               | Text   | The text label visible on the button.                                                                                                                                                |
| Button Link URL           | Link   | The page that clicking the button will link to.                                                                                                                                      |
| Button Width              | Text   | The width of the button. This can be a numerical value (in pixels) or the keyword “auto”. Using auto will size the button automatically to fit its text plus any horizontal padding. |
| Button Horizontal Padding | Text   | The left and right padding inside the button (in pixels). Use this to finetune your button style.                                                                                    |
| Button Font Size          | Text   | The size of the text in the button. Use this to finetune your button style.                                                                                                          |

### Image With Caption

The Image With Caption block displays a full-width linked image with an optional right-aligned caption line beneath it.

#### Options

| Name               | Type      | Description                                                                      |
|:-------------------|:----------|:---------------------------------------------------------------------------------|
| Background Color   | Select    | The background color of the block. Choose from predefined options of your brand. |
| Padding Above      | Text      | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below      | Text      | The spacing below the block. Use a numerical value in pixels                     |
| Image URL          | Image URL | The image to be displayed.                                                       |
| Image Alt Text     | Text      | The text that will be read by screen readers for this image.                     |
| Image Link URL     | Link      | The page that the image will link to when clicked.                               |
| Image Width        | Text      | The width of the image (in pixels). Use 600 for full width.                      |
| Image Caption Text | Text      | The text of the caption.                                                         |
| Show Caption?      | Select    | Controls the visibility of the caption. Choose “No” to not display a caption.    |

### Two Image Columns Block

The Two Image Columns block displays a linked image in each of two columns, side by side. On mobile devices, these images will stack.

The width of each column is 235 pixels. It’s recommended to use images 470 pixels wide for optimal display on high resolution devices.

#### Options

| Name                 | Type      | Description                                                                      |
|:---------------------|:----------|:---------------------------------------------------------------------------------|
| Background Color     | Select    | The background color of the block. Choose from predefined options of your brand. |
| Padding Above        | Text      | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below        | Text      | The spacing below the block. Use a numerical value in pixels                     |
| Left Image           | Image URL | The image to be displayed in the left column.                                    |
| Left Image Alt Text  | Text      | The text that will be read by screen readers for the image in the left column    |
| Left Image Link URL  | Link      | The page that the image in the left column will link to when clicked.            |
| Right Image          | Image URL | The image to be displayed in the right column.                                   |
| Right Image Alt Text | Text      | The text that will be read by screen readers for the image in the right column   |
| Right Image Link URL | Link      | The page that the image in the right column will link to when clicked.           |

### Three Image Columns Block

The Three Image Columns block displays a linked image in each of three columns, side by side. On mobile devices, these images will stack.

The width of each column is 150 pixels. It’s recommended to use images 300 pixels wide for optimal display on high resolution devices.

#### Options

| Name                  | Type      | Description                                                                      |
|:----------------------|:----------|:---------------------------------------------------------------------------------|
| Background Color      | Select    | The background color of the block. Choose from predefined options of your brand. |
| Padding Above         | Text      | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below         | Text      | The spacing below the block. Use a numerical value in pixels                     |
| Left Image            | Image URL | The image to be displayed in the left column.                                    |
| Left Image Alt Text   | Text      | The text that will be read by screen readers for the image in the left column    |
| Left Image Link URL   | Link      | The page that the image in the left column will link to when clicked.            |
| Center Image          | Image URL | The image to be displayed in the center column.                                  |
| Center Image Alt Text | Text      | The text that will be read by screen readers for the image in the center column  |
| Center Image Link URL | Link      | The page that the image in the center column will link to when clicked.          |
| Right Image           | Image URL | The image to be displayed in the right column.                                   |
| Right Image Alt Text  | Text      | The text that will be read by screen readers for the image in the right column   |
| Right Image Link URL  | Link      | The page that the image in the right column will link to when clicked.           |

### 2 Columns Image and Text Block

The 2 Columns Image and Text block displays an image above a rich text area in each of two columns, with optional text links below the content in each column.

#### Options

| Name                     | Type             | Description                                                                      |
|:-------------------------|:-----------------|:---------------------------------------------------------------------------------|
| Background Color         | Select           | The background color of the block. Choose from predefined options of your brand. |
| Padding Above            | Text             | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below            | Text             | The spacing below the block. Use a numerical value in pixels                     |
| Left \- Image            | Image URL        | The image to be displayed in the left column.                                    |
| Left \- Image Alt Text   | Text             | The text that will be read by screen readers for the image in the left column    |
| Left \- Image Link URL   | Link             | The page that the image in the left column will link to when clicked.            |
| Left \- Text Content     | Rich Text editor | The text content for the left column.                                            |
| Left \- Show Text Link?  | Select           | Choose whether to show the additional link text below the text content.          |
| Left \- Text Link Label  | Text             | The text label for the additional link                                           |
| Left \- Text Link URL    | Link             | The page URL for the additional link                                             |
| Right \- Image           | Image URL        | The image to be displayed in the right column.                                   |
| Right \- Image Alt Text  | Text             | The text that will be read by screen readers for the image in the right column   |
| Right \- Image Link URL  | Link             | The page that the image in the right column will link to when clicked.           |
| Right \- Text Content    | Rich Text editor | The text content for the right column.                                           |
| Right \- Show Text Link? | Select           | Choose whether to show the additional link text below the text content.          |
| Right \- Text Link Label | Text             | The text label for the additional link                                           |
| Right \- Text Link URL   | Link             | The page URL for the additional link                                             |

### Signature Block

The Signature Block displays a sign-off message, a portrait photograph, a signature image, and additional signature copy.

Inside the “Ω3. 4Site Marketing Tools” folder of the media library, you will find signature images and portrait photographs for more staff members.

#### Options

| Name                      | Type             | Description                                                                                                                                                                                                        |
|:--------------------------|:-----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color          | Select           | The background color of the block. Choose from predefined options of your brand.                                                                                                                                   |
| Padding Above             | Text             | The spacing above the block. Use a numerical value in pixels                                                                                                                                                       |
| Padding Below             | Text             | The spacing below the block. Use a numerical value in pixels                                                                                                                                                       |
| Sign Off Text             | Rich Text editor | The sign off text shown above the signature.                                                                                                                                                                       |
| Photograph                | Image URL        | The portrait photograph images URL.                                                                                                                                                                                |
| Photograph Alt Text       | Text             | The text that will be read by screen readers for the portrait photograph                                                                                                                                           |
| Signature Image           | Image URL        | The image of the signature text.                                                                                                                                                                                   |
| Signature Image Dark Mode | Image URL        | The image of the signature text that will be displayed in dark mode. Currently, this is the same as the regular signature image as these work well in dark mode but in the future you may need different versions. |
| Signature Image Alt Text  | Text             | The text that will be read by screen readers for the signature image                                                                                                                                               |
| Signature Image Width     | Text             | The width of the signature image in pixels. Default 200\. Adjust as appropriate for signature length.                                                                                                              |
| Signature Text            | Rich Text editor | Text displayed beneath the signature image                                                                                                                                                                         |

### Footer Block

The Footer Block contains a logo, navigation links, social media icons, body text, and an optional button, and is typically used at the bottom of an email.

#### Options

| Name                      | Type             | Description                                                                                                                                                                          |
|:--------------------------|:-----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color          | Select           | The background color of the block. Choose from predefined options of your brand.                                                                                                     |
| Padding Above             | Text             | The spacing above the block. Use a numerical value in pixels                                                                                                                         |
| Padding Below             | Text             | The spacing below the block. Use a numerical value in pixels                                                                                                                         |
| Logo                      | Image URL        | Image URL for the logo that appears at the top of the footer                                                                                                                         |
| Logo Alt Text             | Text             | The text that will be read by screen readers for the logo.                                                                                                                           |
| Logo Link URL             | Link             | The page that will be opened when the logo is clicked.                                                                                                                               |
| Logo Width                | Text             | The width of the logo in pixels (default 150\)                                                                                                                                       |
| Link Left                 | Rich Text Editor | Use the text editor to configure the link on the left of this row.                                                                                                                   |
| Link Right                | Rich Text Editor | Use the text editor to configure the link on the right of this row.                                                                                                                  |
| Footer Text               | Rich Text editor | Add your main footer context text here.                                                                                                                                              |
| Button Background Color   | Select           | The background color of the button. Choose from predefined options of your brand.                                                                                                    |
| Button Border Color       | Select           | The border color of the button. Choose from predefined options of your brand.                                                                                                        |
| Button Text Color         | Select           | The text color of the button. Choose from predefined options of your brand.                                                                                                          |
| Button Text               | Text             | The text label visible on the button.                                                                                                                                                |
| Button Link URL           | Link             | The page that clicking the button will link to.                                                                                                                                      |
| Button Width              | Text             | The width of the button. This can be a numerical value (in pixels) or the keyword “auto”. Using auto will size the button automatically to fit its text plus any horizontal padding. |
| Button Horizontal Padding | Text             | The left and right padding inside the button (in pixels). Use this to finetune your button style.                                                                                    |
| Button Font Size          | Text             | The size of the text in the button. Use this to finetune your button style.                                                                                                          |
| Facebook Link URL         | Link             | The link to your Facebook page                                                                                                                                                       |
| Instagram Link URL        | Link             | The link to your Instagram page                                                                                                                                                      |
| YouTube Link URL          | Link             | The link to your YouTube page                                                                                                                                                        |
| LinkedIn Link URL         | Link             | The link to your LinkedIn page                                                                                                                                                       |

### Call To Action Block

The Call To Action block contains a coloured background panel with rich text and a customisable button to drive readers to take a specific action.

#### Options

| Name                      | Type             | Description                                                                                                                                                                          |
|:--------------------------|:-----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color          | Select           | The background color of the block. Choose from predefined options of your brand.                                                                                                     |
| Padding Above             | Text             | The spacing above the block. Use a numerical value in pixels                                                                                                                         |
| Padding Below             | Text             | The spacing below the block. Use a numerical value in pixels                                                                                                                         |
| CTA Background Color      | Select           | Controls the background color of the CTA. This differs from “Background Color” because it does not color the padding above and below the CTA.                                        |
| CTA Text                  | Rich Text editor | Write and style the text of your CTA here.                                                                                                                                           |
| Button Background Color   | Select           | The background color of the button. Choose from predefined options of your brand.                                                                                                    |
| Button Border Color       | Select           | The border color of the button. Choose from predefined options of your brand.                                                                                                        |
| Button Text Color         | Select           | The text color of the button. Choose from predefined options of your brand.                                                                                                          |
| Button Text               | Text             | The text label visible on the button.                                                                                                                                                |
| Button Link URL           | Link             | The page that clicking the button will link to.                                                                                                                                      |
| Button Width              | Text             | The width of the button. This can be a numerical value (in pixels) or the keyword “auto”. Using auto will size the button automatically to fit its text plus any horizontal padding. |
| Button Horizontal Padding | Text             | The left and right padding inside the button (in pixels). Use this to finetune your button style.                                                                                    |
| Button Font Size          | Text             | The size of the text in the button. Use this to finetune your button style.                                                                                                          |

### Callout With Image Background

The Callout With Image Background block displays rich text and a button overlaid on a background image.

It’s possible to use the “Inner Padding Top” and “Inner Padding Bottom” values to adjust the alignment of the content within the callout (as well as the overall height of the callout). For example, the default values of 350 Inner Padding Top and 50 Inner Padding Bottom align the content to the bottom, but you can reverse these to align it to the top or set them equal to align it to the middle. Experiment with them to find what looks good with your background image.

#### Options

| Name                      | Type             | Description                                                                                                                                                                          |
|:--------------------------|:-----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Background Color          | Select           | The background color of the block. Choose from predefined options of your brand.                                                                                                     |
| Padding Above             | Text             | The spacing above the block. Use a numerical value in pixels                                                                                                                         |
| Padding Below             | Text             | The spacing below the block. Use a numerical value in pixels                                                                                                                         |
| Background Image          | Image URL        | Choose an image to be shown as the background of the callout                                                                                                                         |
| Inner Padding Top         | Text             | Enter a numerical value of the number of pixels of padding to add above the content inside the callout.                                                                              |
| Inner Padding Bottom      | Text             | Enter a numerical value of the number of pixels of padding to add below the content inside the callout.                                                                              |
| Text Content              | Rich Text editor | Write and style the text of your callout here. By default any text entered here will be white, but you can overwrite this with the text editor tools.                                |
| Button Background Color   | Select           | The background color of the button. Choose from predefined options of your brand.                                                                                                    |
| Button Border Color       | Select           | The border color of the button. Choose from predefined options of your brand.                                                                                                        |
| Button Text Color         | Select           | The text color of the button. Choose from predefined options of your brand.                                                                                                          |
| Button Text               | Text             | The text label visible on the button.                                                                                                                                                |
| Button Link URL           | Link             | The page that clicking the button will link to.                                                                                                                                      |
| Button Width              | Text             | The width of the button. This can be a numerical value (in pixels) or the keyword “auto”. Using auto will size the button automatically to fit its text plus any horizontal padding. |
| Button Horizontal Padding | Text             | The left and right padding inside the button (in pixels). Use this to finetune your button style.                                                                                    |
| Button Font Size          | Text             | The size of the text in the button. Use this to finetune your button style.                                                                                                          |

### Divider

The Divider block inserts a horizontal rule to visually separate content sections. Its height, width, and color can be edited.

#### Options

| Name             | Type   | Description                                                                      |
|:-----------------|:-------|:---------------------------------------------------------------------------------|
| Background Color | Select | The background color of the block. Choose from predefined options of your brand. |
| Padding Above    | Text   | The spacing above the block. Use a numerical value in pixels                     |
| Padding Below    | Text   | The spacing below the block. Use a numerical value in pixels                     |
| Divider Height   | Text   | The height of the divider line in pixels                                         |
| Divider Width    | Text   | The width of the divider line in pixels. Maximum value is 560\.                  |
| Divider Color    | Select | The color of the divider line. Choose from predefined options of your brand.     |

### Highlighted Text

The Highlighted Text block displays rich text inside a bordered, colored panel to draw attention to key content.

#### Options

| Name                   | Type             | Description                                                                                              |
|:-----------------------|:-----------------|:---------------------------------------------------------------------------------------------------------|
| Background Color       | Select           | The background color of the block. Choose from predefined options of your brand.                         |
| Padding Above          | Text             | The spacing above the block. Use a numerical value in pixels                                             |
| Padding Below          | Text             | The spacing below the block. Use a numerical value in pixels                                             |
| Highlighted Text       | Rich Text editor | Write and style the text of your highlighted text here.                                                  |
| Highlighted Border     | Select           | The color of the left border of the highlighted text area. Choose from predefined options of your brand. |
| Highlighted Background | Select           | The background color of the highlighted text area. Choose from predefined options of your brand.         |

### Question Response

The Question Response block displays a response option with a linked label inside a styled, hoverable container.

When using multiple copies of the block inside an email, the values for the Inner Background Color and Inner Background Color Hover must be the same for all copies of the block for it to work properly.

Check out Engaging Networks’ documentation on [pre-populating form fields](https://knowledge.engagingnetworks.net/youraccount/pre-populating-form-fields) to see how to create URLs where a specific answer to a question on a page is pre-populated. You can use these links with the block for on-page continuity.

#### Options

| Name                         | Type   | Description                                                                                                        |
|:-----------------------------|:-------|:-------------------------------------------------------------------------------------------------------------------|
| Background Color             | Select | The background color of the block. Choose from predefined options of your brand.                                   |
| Padding Above                | Text   | The spacing above the block. Use a numerical value in pixels                                                       |
| Padding Below                | Text   | The spacing below the block. Use a numerical value in pixels                                                       |
| Response Text                | Text   | Enter the text for the response here.                                                                              |
| Response Link                | Link   | Enter the link for the page that selecting this answer will open. You can use a pre-populating link.               |
| Inner Background Color       | Select | The background color of the response section. Must be the same for all copies of the block in the same.            |
| Inner Background Color Hover | Select | The background color when hovering the response section. Must be the same for all copies of the block in the same. |
| Border Color                 | Select | The border color of the response section. Must be the same for all copies of the block in the same.                |

### Side-By-Side Image and Text Block

The Side-By-Side Image and Text block displays an image alongside a rich text area in two columns, with the image position configurable to appear on the left or right.

#### Options

| Name             | Type             | Description                                                                                                |
|:-----------------|:-----------------|:-----------------------------------------------------------------------------------------------------------|
| Background Color | Select           | The background color of the block. Choose from predefined options of your brand.                           |
| Padding Above    | Text             | The spacing above the block. Use a numerical value in pixels                                               |
| Padding Below    | Text             | The spacing below the block. Use a numerical value in pixels                                               |
| Image Position   | Select           | Use this to flip the arrangement of the columns.                                                           |
| Image            | Image URL        | The image to display. Recommend dimensions 440x580. Height can be different, based on your content height. |
| Image Alt Text   | Text             | The text that will be read by screenreaders for this image.                                                |
| Image Link URL   | Link             | The page that clicking the image will link to.                                                             |
| Text Content     | Rich Text editor | Enter and style the text content for this block.                                                           |
| Show Text Link?  | Select           | Choose whether or not to show the extra styled hyperlink beneath the text                                  |
| Text Link Label  | Text             | Hyperlink text label.                                                                                      |
| Text Link URL    | Link             | Enter the page the link text should link to.                                                               |

### Spacer Block

The Spacer Block inserts a blank vertical space of configurable height and background color between other blocks.

Use this block to finetune spacing in your email when required.

#### Options

| Name                    | Type   | Description                                                                               |
|:------------------------|:-------|:------------------------------------------------------------------------------------------|
| Spacer Height           | Text   | The height of the spacer in pixels.                                                       |
| Spacer Background Color | Select | The background color of the spacer section. Choose from predefined options of your brand. |

### Testimonial Block

The Testimonial Block displays a quote and author name inside a styled bordered container. The quotation marks image inside the testimonial can be swapped.

#### Options

| Name                         | Type      | Description                                                                                      |
|:-----------------------------|:----------|:-------------------------------------------------------------------------------------------------|
| Background Color             | Select    | The background color of the block. Choose from predefined options of your brand.                 |
| Padding Above                | Text      | The spacing above the block. Use a numerical value in pixels                                     |
| Padding Below                | Text      | The spacing below the block. Use a numerical value in pixels                                     |
| Testimonial Text             | Text      | Enter the text of your testimonial                                                               |
| Testimonial Author           | Text      | Enter the name of the testimonial author                                                         |
| Testimonial Border Color     | Select    | The color of the bottom border of the testimonial. Choose from predefined options of your brand. |
| Testimonial Background Color | Select    | The background color of the testimonial. Choose from predefined options of your brand.           |
| Testimonial Text Color       | Select    | The text color of the testimonial. Choose from predefined options of your brand.                 |
| Testimonial Image            | Image URL | The image shown above the testimonial text.                                                      |
| Testimonial Dark Mode Image  | Image URL | The image shown above the testimonial text when viewed in dark mode clients.                     |
| Testimonial Image Width      | Text      | The width (in pixels) of the image above the testimonial text.                                   |
| Testimonial Image Alt Text   | Text      | The text that will be read by screenreaders for this image.                                      |

## Compatibility & Guidelines

### Templates & Blocks

For technical reasons, only the templates and blocks developed by 4Site are guaranteed to work together. This means that other blocks may not work properly inside the 4Site template and the 4Site blocks may not work properly inside other templates.

This is because the HTML structure and styling code of the template and blocks must work together.

### Block Configuration Guidelines

Your email template and blocks are set up to be resilient and mobile responsive by default. But there are a few best practices when configuring them to be aware of to ensure the best results.

1. Never set any widths (such as images) to greater than the width of the email (600px). The documentation should state max widths where appropriate. Note that some are less than 600 due to horizontal padding on the blocks (e.g. the divider block).  
2. Make sure you only add correct value types into options. Where it states a value should be numerical in pixels, only enter numbers. Unfortunately Engaging Networks does not have validation for these values so we have to be careful.  
3. Send test emails to yourself to double check all links work as expected.  
4. Use appropriately sized images. This documentation contains guidelines on image sizes for blocks. Images should not break display even if they are oversized, but they may have a larger than desired height on mobile devices.  
5. Check the documentation for each block in this document if unsure on anything.

### Email Client Support & Features

Our emails are designed to work fully only on modern clients that are actively developed and have a large user base. The following clients are supported:

* **Desktop Clients:** Apple Mail, Outlook 365, Outlook 2021  
* **Mobile Clients:** Gmail, Apple Mail  
* **Web Clients:** Gmail

**Dark Mode Support:** Dark Mode is only fully supported by Apple Mail. Gmail and Outlook provide their own dark mode support, but it is not configurable or customisable by developers. Dark mode is not supported in other clients.

**Custom fonts**: Custom fonts are only supported by Apple Mail. On other clients, it will fallback to the default device font. For a consistent experience across all devices, use a default web safe font such as: Arial, Helvetica, Verdana, Georgia, Times New Roman or Tahoma. **NGS is using Arial and Georgia fonts.**

### Images

It is recommended to use high quality images in 2x resolution for optimal appearance on high resolution displays. We have added placeholder images where appropriate in their dimensions.

### JSON Exports

JSON exports of blocks and templates can be found in the "exports" folder of the repository and can be used as backups and for restoration.

## Building an Email Broadcast

You can refer to EN’s documentation on building an Email Broadcast here: [https://knowledge.engagingnetworks.net/marketingtools/broadcasts](https://knowledge.engagingnetworks.net/marketingtools/broadcasts)

Follow these steps:

* Duplicate one of your reference emails or create a new broadcast by starting from scratch and using “4Site Main Email Template”  
* Go through the Email Setup and Audience Selection steps.  
* Add blocks from the “4Site Blocks” folder and configure them as desired.  
  * You can also adjust any blocks already in the email if you duplicated a reference email.  
* The only requirement for an email is that it must have an “Unsubscribe” link present somewhere in the email.  
* In the testing tab, send a test email to your testing service to QA the design of your email  
  * We also recommend sending an email to yourself so you can verify all links are set up and working correctly  
* Once you’ve confirmed this, your email is ready to send.

## Updating Variable Replacements

To adjust the configurable settings for email editors within a block, follow these steps:

* Find the specific block in Marketing Tools and duplicate it to preserve a backup version.  
* Access the block and select the option to “Insert Variable Replacement.”  
* For generating a brand new replacement:  
  * Navigate to the “Create” tab and complete the necessary information in the provided fields.  
* For modifying an existing replacement:  
  * Select the edit icon adjacent to the variable you wish to change.  
  * Refine the available settings.  
* When your edits are complete, click “Done” followed by “Save Block.”  
* To embed your replacement variable into the block content:  
  * Position the cursor at the intended insertion point.  
  * Click the “Insert Variable Replacement” button.  
  * Identify your variable and click the “Insert” button  
  * Confirm the placement within the block is accurate.  
* After completing your edits, do a QA check:  
  * Insert the modified block into a reference email for testing purposes.   
  * Navigate to the test tab of the broadcast and send a sample to your preferred testing platform.  
  * Verify the block displays correctly across different mail clients and screen sizes.

### Example: adding a new background color option

To do this:

* All of your blocks have a background color option, so we could choose any. Let’s do this on “Button Block”.  
* Open the block and click the “insert variable replacement” button
* Locate the “Background Color” replacement and click the pencil icon
* Inside the options click “Manage Options”
* Click “Add” to add a new option. Insert our hex code value and label. The value will be inserted into the email, and the label will be what is visible to the email builder.
* After that we can click “Update” in the replacements modal, then “Save Block” at the bottom of the block.

## Coding New Blocks

**This part of the documentation is intended for developers who want to code new blocks and edit existing ones that are compatible with 4Site’s template. The following text is just a short primer on the topic.** 

Our email code is created with [MJML](https://mjml.io/) which provides a solid base for creating cross-client compatible email structure without getting into the complexities of manually nesting all your own Table elements.

If you want to work directly with the code you’ll need a code editor (VSCode with the [MJML Extension](https://marketplace.visualstudio.com/items?itemName=attilabuti.vscode-mjml) works well) and [NodeJS](https://nodejs.org/en) installed on your computer.

Follow these steps to get started:

* Clone the repository: [https://github.com/4site-interactive-studios/ngs-en-marketing-tools](https://github.com/4site-interactive-studios/ngs-en-marketing-tools).  
* Install NPM modules with “npm install”.

Creating or editing blocks will generally follow this workflow:

* Make code changes in “src/main.mjml” and/or “src/styles.css”.  
* Run: “npm run build” to build the HTML.  
* Open “dist/main.html” and find the newly edited code section (Tip: Comments from the MJML file are preserved, so use comments to easily find the start and end of your section).  
* If creating a new block:  
  * Copy this code into a new block in Engaging Networks.  
  * Configure any Variable Replacements needed for this block.  
* If updating an existing block:  
  * Before starting, always duplicate your block to create a backup.  
  * Compare the existing code and copy any changes into the block. (Tip: you can use an online diff checker tool to compare the 2 sets of code)  
* Once you’ve finished creating or editing your block, you can add it into a reference email to test it.  
* Go to the testing section of the broadcast and send a test email to your testing service.  
* Review the email to check that your block is looking as expected across various devices and clients. Remember to test all your configuration options values.

**If your code changed styles or code in the head of the email, you’ll need to update the template with these changes, then rebuild your email from scratch with the updated template.**

### Code structure for new blocks

New blocks must:

* Start with an “mj-section” element.  
* Have a CSS class of “block” and a unique CSS class for your block, e.g., “demo-block”.  
* Have a background color (typically white).  
* Recommended: Include comments before and after the block to make identifying it in the built HTML easier.

Here is an example:

```html
<!-- START: Three column block -->
<mj-section css-class="three-column-block block" background-color="#ffffff">

</mj-section>
<!-- END: Three column block -->
```


Then, we add “mj-column” element(s) inside the block to contain our content. For this example, say we want to make a block that has 3 columns with text inside them. Our basic block would look like this:

```html
<!-- START: Three column block -->

<mj-section css-class="three-column-block block" background-color="#ffffff">
  <mj-column>
    <mj-text>Column 1</mj-text>
  </mj-column>
  
  <mj-column>
    <mj-text>Column 2</mj-text>
  </mj-column>
  
  <mj-column>
    <mj-text>Column 3</mj-text>
  </mj-column>
</mj-section>
<!-- END: Three column block -->
```

After adding this code to the “src/main.mjml” file, we can run “npm run build” then, using the comments, identify the code section in the “dist/main.html” file and copy it into a new Block in Engaging Networks and begin setting up the Variable Replacements.

## References

EN documentation on using the Marketing Tools: [https://knowledge.engagingnetworks.net/marketingtools/broadcasts](https://knowledge.engagingnetworks.net/marketingtools/broadcasts)

EN documentation on templates and blocks: [https://knowledge.engagingnetworks.net/marketingtools/marketing-tools-templates](https://knowledge.engagingnetworks.net/marketingtools/marketing-tools-templates)

[https://knowledge.engagingnetworks.net/marketingtools/marketing-tools-components-blocks](https://knowledge.engagingnetworks.net/marketingtools/marketing-tools-components-blocks)

Code repository: [https://github.com/4site-interactive-studios/ngs-en-marketing-tools](https://github.com/4site-interactive-studios/ngs-en-marketing-tools)

MJML Documentation: [https://documentation.mjml.io/](https://documentation.mjml.io/)
