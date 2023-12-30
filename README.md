# s1blocks
s1blocks provides a simple web interface for interacting with the Scratch 1.x version of the Block Plugin (a.k.a. scratchblocks), used on the 1.x Wiki and Forums.

The interface is very rudimentary and contains only the bare minimum at the moment, but I plan to clean it up and make everything a bit more proper.

## Usage
To use the plugin, type your scratchblocks code into the text field, then click "Parse" to render the blocks.

Syntax for this plugin is similar to that of the [modern scratchblocks plugin](https://github.com/scratchblocks/scratchblocks), albeit with several features missing. For a more detailed explanation, see [Block Plugin (1.4)/Syntax](https://en.scratch-wiki.info/wiki/Block_Plugin_(1.4)/Syntax) on the Scratch Wiki.

### Implementing the Plugin

The block plugin itself can also be implemented elsewhere. It consists of two parts:

* `blocksplugin.js`, the JavaScript code for the plugin itself
* the `static` folder, containing images necessary for certain blocks to display properly

You should check `blocksplugin.js` and `index.html` to get an idea of how the plugin works.

## Known Issues
* Certain characters, such as `<` and `>`, can cause formatting issues

## Credit
The original block plugin was created in 2011 by Joren Lauwers (a.k.a. JSO), then a Scratch Team member.

The rights for Scratch and its blocks belong to the Scratch Foundation.

The original credit given in `blocksplugin.js` has been left intact and unaltered.