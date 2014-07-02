radialRepeat
============
#### Photoshop CS2+ JSX script for radially repeating content

radialRepeat allows you to create interesting and complex radially-symmetrical patterns easily and quickly using small incremental edits.

This script was inspired by the [interesting artwork](http://wiki.xxiivv.com/fractals) created by [aliceffekt](https://github.com/aliceffekt), as well as an older ["timelapse" recording](http://www.youtube.com/watch?v=iu0ODV8scH4) of his process.  I thought it would be useful to provide a portable Photoshop script to automate the process of creating these patterns, with useful options to customize the process.

[![radially-symmetrical artwork](http://wiki.xxiivv.com/img/diary/385.jpg "Aliceffekt - Rainise")](http://wiki.xxiivv.com/fractals)

Instructions
------------
1. Place radialRepeat.jsx into your Photoshop scripts folder.
	* on Windows: C:\Program Files\Adobe\Adobe Photoshop\Presets\Scripts
	* on Mac OS X:  Applications/Photoshop/Presets/Scripts
2. *OPTIONAL*: Assign the script to a keyboard shortcut ( *Edit -> Keyboard Shortcuts* )
3. Create a new document and create a new layer.
4. Draw something in this layer!
5. Run the script, either with your key-command or by choosing *File -> Scripts -> radialRepeat*.  If you have set "promptForNumberOfNodes"  (see [Options](#options) below), you will be asked how many total nodes you'd like your graphic to have.  **Protip**:  You don't have to use the same number of nodes every time!  Try changing it up each time for interesting results!

**Automatic history state**:  Just as it begins running, radialRepeat automatically sets a history "bookmark" (by setting the History Brush source) in the document's history.  If you don't like the results from the latest run, you can revert back by scrolling up in the document history and choosing that history state.

Options
-------

The script can be set to either always use the same number of nodes, or to ask you how many total nodes you want every time you run the script.  These settings can be changed in the "SETTINGS" section of the script.  You can edit the script using any text editor - just be sure that it saves it as plain text (as opposed to .doc, .rtf).

* **numberOfNodes** *(default 16)*: To set the total number of nodes (with no prompt dialog), change the "numberOfNodes" value.  Must be 2 or greater.
* **promptForNumberOfNodes** *(default false)*: If you would like to be prompted for this number every time you run the script, change "promptForNumberOfNodes" to true.

License
-------
MIT.  See [LICENSE](LICENSE).
