<html>
<body style='background-color:##D7ECF8;'>
<h3>RALIBRARY UWP</h3>
<div id='help' style='font-size:.9em;'>
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
<p>
<b>What's Next</b>
<ol>
    <li>Copy the entire directory containing your new plugin to the QGIS plugin directory
    <li>Compile the ui file using pyuic4
    <li>Compile the resources file using pyrcc4
    <li>Test the plugin by enabling it in the QGIS plugin manager
    <li>Customize it by editing the implementation file <b>geneticsimplifier.py</b>
    <li>Create your own custom icon, replacing the default <b>icon.png</b>
    <li>Modify your user interface by opening <b>geneticsimplifier.ui</b> in Qt Designer (don't forget to compile it with pyuic4 after changing it)
    <li>You can use the <b>Makefile</b> to compile your Ui and resource files when you make changes. This requires GNU make (gmake)
</ul>
</div>
<div style='font-size:.9em;'>
<p>
For more information, see the PyQGIS Developer Cookbook at:
<a href="http://www.qgis.org/pyqgis-cookbook/index.html">http://www.qgis.org/pyqgis-cookbook/index.html</a>.
</p>
</div>
&copy; Copyright 2019 Matheus Giovanni Lucena

    
