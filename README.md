# Obsidian-Excalidraw-ymjr

This is a modified version of the [obsidian-excalidraw-plugin](https://github.com/zsviczian/obsidian-excalidraw-plugin).

[English](./README.md) | [简体中文](docs/README_ZH.md)

Based on my specific needs, I made necessary modifications to the obsidian-excalidraw-plugin when custom scripts couldn't fulfill those requirements.

You can find the custom scripts at [obsidian-excalidraw-scripts](https://github.com/Bowen-0x00/obsidian-excalidraw-scripts) (Uploading...)

You can find the demo obsidian vault at [obsidian-excalidraw-example-vault](https://github.com/Bowen-0x00/obsidian-excalidraw-example-vault). Here is a demonstration [video](https://www.bilibili.com/video/BV1zN4y1H7Dx/). 

## Features
Here are the functionalities that required modifications in order to be implemented.

When combined with custom scripts, it allows for:

- Support for multiple custom fonts simultaneously
- Obsidian tag functionality for elements
- Mouse event hooks
  - Show/hide elements
  - Expand/collapse mind map
    - <img src="images/mindmap2.gif" width="300px">
    - <img src="images/mindmap2 - mobile.gif" width="300px">
  - Adjust row/column height/width in tables
  - Zoom in/out or mouse scroll to show/hide elements
- Keyboard event hooks
  - Add elements to mind maps
  - Play GIF frame by frame
  - Show/hide individual elements in the current view
- Bold text
  - <img src="images/partial highlight2.gif" width="300px">
- Indentation of the first line of text in containers
- Gradient for shapes and text
- Shadow for shapes and text
- Layer functionality
  - <img src="images/layer3.gif" width="300px">
- Fix for wrapping issues with Chinese characters
- Dragging point hook
  - Measurement feature
- Display canvas thumbnail
  - <img src="images/thumbnail2.gif" width="300px">
- Mouse hover hook
  - Change shadow on mouse hover (callout, buttons)
- Uniform formula size to match font size
  - <img src="images/latex_fit2.gif" width="300px">
- Reference and navigation to specific parts of an excalidraw canvas
- Play GIF within shapes (not as an iframe)
- Settings
  - Laser pen settings
  - Customize the names of saved attachments
  - Whether to embed font information when exporting SVG.
  - Whether to display all arrow options.
- Fixed element to screen
- Maintain gradients when exporting/embedding SVG.
  - <img src="images/Cover74.PNG" width="300px">
- Library grouping & on-demand loading.
  - <img src="images/library1.gif" width="300px">
  - <img src="images/library2.gif" width="300px">
- Drag and stretch a custom-shaped arrow while keeping the arrowhead unchanged.
  - <img src="images/fixedDragable.gif" width="300px">
- Show and hide detail.
  - <img src="images/detail2.gif" width="300px">
- Automatic connection feature (right-angle connection, attaching to connection points)
  - <img src="images/switch connection shape2.gif" width="300px">
  - <img src="images/switch connection shape_move2.gif" width="300px">
- Code syntax highlight.
  - <img src="images/code.gif" width="300px">
- Echarts.
  - <img src="images/echarts.gif" width="300px">
- Eender local md, code, echarts when exporting svg.
  - <img src="images/export svg.gif" width="300px">
- Calendar element.
  - <img src="images/calendar element.gif" width="300px">
- Flow animation
  - <img src="images/arrow flow animation.gif" width="300px">

You can view the demonstration and more details on
- My [Bilibili Space](https://space.bilibili.com/39231346/).

## Installation and Usage

### Precautions
Please make sure to backup your work to ensure that your important content is not lost (such as saving abnormalities caused by insufficient memory).

For example:

- Use git version control.
- Utilize onedrive for cloud synchronization and version control.
- Enable file recovery plugins in the core plugins.
### Steps to Follow
1. Install the plugin.
   1. Method 1 (Manual Installation): Place `main.js`, `manifest.json`, and `styles.css` in the plugin directory, such as `YourVaultPath\.obsidian\plugins\obsidian-excalidraw-plugin-ymjr`.
   2. Method 2 (BRAT Auto Installation):
      1. Install the BRAT script from the community plugins.
      2. In the BRAT plugin settings, click on `Add Beta plugin`.
      3. In the prompted GitHub repository dialog, enter `Bowen-0x00/obsidian-excalidraw-plugin-ymjr`.
2. In the `Community plugins -> Installed plugins` of Obsidian, disable the original `Excalidraw` and enable `obsidian-excalidraw-plugin-ymjr`.![Enable Plugin](images/settings%20-%20community%20plugins.PNG)
3. Use the scripts corresponding to the functionality you need, and place the scripts in the folder specified by `Basic -> Excalidraw Automate Script folder` in your plugin settings.![Script folder](images/settings%20-%20script%20folder.PNG)

## Feedback, questions, ideas, problems
Feel free to contact me if:

- You have any issues or questions regarding usage.
- You have suggestions or feedback.
- You want to discuss interesting ideas or new features.

Communication channels can be:
- GitHub issues.
- Email.
- Bilibili comments or private messages.
- My personal contact information (WeChat, QQ).


## Say Thank You
If you find the modifications I made helpful to you, feel free to leave comments and messages.

You can also sponsor me a cup of coffee:
- WeChat sponsorship code.
<img src="images/赞助码.jpg" width="200px">
- ko-fi
  <a href='https://ko-fi.com/G2G3SY16R' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## Thanks
Thanks to [zsviczian](https://github.com/zsviczian) and other contributors of [obsidian-excalidraw-plugin](https://github.com/zsviczian/obsidian-excalidraw-plugin).

Thanks to contributors of [excalidraw](https://github.com/excalidraw/excalidraw).