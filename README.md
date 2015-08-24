# MagentoSnippets
Magento Front End Snippets, plugin for Sublime Text.

This tool serves to aid the productivity during the Magento's theme development through snippets. These snippets brings partial codes belonging the Magento framework. These code that we used everyday, but never memorized because they are often complex and lengthy.

## Installation
Install via [Package Control](https://packagecontrol.io/installation)

## How do I use it?
The tab trigger of this plugin is "mg-*".

In some editors just the tab key don't trigger the snippet, so you have to check few things to make magic happens like on gif below.

1. Check if you don't have set key binding for user (if so you have to remove it):<br />
    ```{ "keys": ["tab"], "command": "insert_best_completion", "args": {"default": "\t", "exact": true} },```
1. If it still doesn't work add to your user settings below line: <br />
    ```"tab_completion": false,```
1. Some people have assigned CTRL+Space as the snippet trigger
1. Check if another package is not coliding with snippet trigger (i.e. Emmet can cause some issues with Sublime Text 3 Snippet usage)

![MagentoSnippets: example of use](http://www.magefront.com.br/wp-content/uploads/2015/08/MagentoSnippets-sample.gif)

## Suggestions
If you have something to improve these snippets, please create a [issue](https://github.com/MageFront/MagentoSnippets/issues/new)

**For how to do your own snippet and contribute for this tool see the [contribution text](https://github.com/MageFront/MagentoSnippets/blob/master/contribute.md)**

## Available Snippets

### XML

1. `mg-addLinkRel` :: Add LinkRel in XML
1. `mg-xml-cms-block` :: CMS Block in XML
1. `mg-xml-css` :: Adds CSS in XML
1. `mg-insert` :: Insert block Method
1. `mg-local-xml` :: Writes the basic structure to a new local.xml file
1. `mg-ref` :: Add reference tag
1. `mg-rm` :: XML to removes a block
1. `mg-removeItem` :: Remove head items by xml
1. `mg-xml-setcolumn` :: Add number of columns in product list
1. `mg-set-template` :: Action to set a new root template
1. `mg-xml-skinjs` :: Add skin js in XML
1. `mg-unsetchild` :: Unset Child Method
1. `mg-xml-text` :: Free text in XML

### PHTML

1. `mg-php-cms-block` :: CMS Block in PHTML(PHP+HTML)
1. `mg-format-price-currency` :: Format Price
1. `mg-getAttrText` :: Get Attribute Text in product view
1. `mg-getchildhtml` :: Get Child Html Method
1. `mg-url` :: Get Url
1. `mg-url-asec` :: Get Array Secure Url
1. `mg-img` :: Image Skin Url
1. `mg-productTypeId` :: Get Type Product Id
1. `mg-script` :: Adds script/javascript tag
1. `mg-storeInfo` :: Gets store information
1. `mg-translate-phtml` :: Adds the translator helper output
1. `mg-vars` :: Get Variable from admin
1. `mg-viewport` :: Viewport metatag to load media-queries

### JS

1. `mg-console-log` :: Add console.log for debug
1. `mg-iife-jquery` :: IIFE passing jQuery as parameter
1. `mg-prototype-dom-ready` :: Adds Prototype DOM ready

### SCSS

1. `mg-clearfix` :: Creates a placeholder selector to fix floats
1. `mg-scss-imgurl` :: Calls the image url function
1. `mg-scss-sprite-height-width` :: Calls in scss sprite height and width functions
1. `mg-scss-sprite` :: Calls in scss the Sprite function
