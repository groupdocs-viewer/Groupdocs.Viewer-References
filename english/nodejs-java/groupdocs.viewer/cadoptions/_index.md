---
title: CadOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/cadoptions/
---

## CadOptions class

 Provides options for rendering CAD drawings.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| HEIGHT | height |  |
| WIDTH | width |  |


## Functions

| Name | Description |
| --- | --- |
| [equals](equals)(Object) |  |
| [forRenderingByHeight](forrenderingbyheight)(int) | Initializes new instance of CadOptions class for rendering by height. |
| [forRenderingByScaleFactor](forrenderingbyscalefactor)(double) | Initializes new instance of CadOptions class for rendering by scale factor. |
| [forRenderingByWidth](forrenderingbywidth)(int) | Initializes new instance of CadOptions class for rendering by width. |
| [forRenderingByWidthAndHeight](forrenderingbywidthandheight)(int, int) | Initializes new instance of CadOptions class for rendering by width and height. |
| [getBackgroundColor](getbackgroundcolor)() | Gets image background color |
| [getHeight](getheight)() | The height of the output result in pixels. |
| [getLayers](getlayers)() | The CAD drawing layers to render. By default all layers are rendered; Layer names are case-sensitive. |
| [getLayoutName](getlayoutname)() | The name of the specific layout to render. Layout name is case-sensitive. This option applies only to CAD drawings that support layouts FileType#DXF, FileType#DWG, FileType#DWT, FileType#DWF and FileType#DWFX; By default only Model is rendered. |
| [getPc3File](getpc3file)() | PC3 - plotter configuration file |
| [getScaleFactor](getscalefactor)() | Values higher than 1 will enlarge output result; values between 0 and 1 will make output result smaller. |
| [getTiles](gettiles)() | The drawing regions to render. This option supported only for FileType#DWG and FileType#DWT file type. The RenderLayouts( CadOptions#isRenderLayouts()/ CadOptions#setRenderLayouts(boolean)) and LayoutName( CadOptions#getLayoutName()/ CadOptions#setLayoutName(String)) options are ignored when rendering by tiles. |
| [getWidth](getwidth)() | The width of the output result in pixels. |
| [hashCode](hashcode)() |  |
| [isRenderLayouts](isrenderlayouts)() | Indicates whether layouts from CAD document should be rendered. This option applies only to CAD drawings that support layouts FileType#DXF, FileType#DWG, FileType#DWT, FileType#DWF and FileType#DWFX; By default only Model is rendered. |
| [setBackgroundColor](setbackgroundcolor)(Color) | Sets image background color |
| [setLayers](setlayers)(java.util.ArrayList<com.groupdocs.viewer.results.Layer>) | The CAD drawing layers to render. By default all layers are rendered; Layer names are case-sensitive. |
| [setLayoutName](setlayoutname)(String) | The name of the specific layout to render. Layout name is case-sensitive. This option applies only to CAD drawings that support layouts FileType#DXF, FileType#DWG, FileType#DWT, FileType#DWF and FileType#DWFX; By default only Model is rendered. |
| [setPc3File](setpc3file)(String) | PC3 - plotter configuration file |
| [setRenderLayouts](setrenderlayouts)(boolean) | Indicates whether layouts from CAD document should be rendered. This option applies only to CAD drawings that support layouts FileType#DXF, FileType#DWG, FileType#DWT, FileType#DWF and FileType#DWFX; By default only Model is rendered. |
| [setTiles](settiles)(java.util.List<com.groupdocs.viewer.options.Tile>) | The drawing regions to render. This option supported only for FileType#DWG and FileType#DWT file type. The RenderLayouts( CadOptions#isRenderLayouts()/ CadOptions#setRenderLayouts(boolean)) and LayoutName( CadOptions#getLayoutName()/ CadOptions#setLayoutName(String)) options are ignored when rendering by tiles. |
| [toString](tostring)() |  |
| [toString](tostring)(ToStringStyle) |  |
