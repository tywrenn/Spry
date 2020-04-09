# Spry

This is a fork of Spry with HTML 5 validation fixes

## Overview

Spry is a JavaScript-based framework that enables the rapid development of Ajax-powered web pages. 

Spry was designed to feel like an extension of HTML and CSS, so anyone with basic web-production skills can create next-generation web experiences by adding the power of Ajax to their pages.

Spry can be used with any server-side technology (ColdFusion, PHP, ASP.Net etc.). By building the front-end of your web application with Spry you enable a more efficient designer-developer workflow by keeping UI separated from back-end application logic.


## Using Spry
<ul>
<li>Spry is implemented as a set of JavaScript libraries. To use Spry on a page, simply include the JavaScript library that contains the Spry features you need, use those features on your page, and then deploy that JavaScript file to your site along with your page.</li>
<li>Spry has three parts: Spry Data, Spry Widgets and Spry Effects. They can be used together or independently of one another.</li>
<li>No browser plug-ins or server-side modules are required for Spry to work.</li>
<li>Any code editor can be used to develop Spry pages.</li>
</ul>

## Spry Data
<ul>
<li>The Spry Data set transforms complex data sources into a familiar row/column format that can be placed anywhere within your page.</li>
<li>Supported data sources include XML, JSON and HTML</li>
<li>Easily add Dynamic Regions to your page that control retrieval and placement of data without writing any JavaScript.</li>
</ul>

## Spry Widgets
<ul>
<li>Spry widgets are advanced web components expressed in basic HTML markup, CSS and a little JavaScript.</li>
<li>Customization and styling is easily done using your existing HTML & CSS skills.</li>
<li>Spry widgets are accessible. They respond to keyboard navigation and degrade gracefully when JavaScript its turned off.</li>
</ul>

## Spry Effects
<ul>
<li>Spry effects allow you to add smooth and graceful transitions to almost any element on your page</li>
<li>A single line of JavaScript is used to add an effect to your page.</li>
<li>Effects can highlight information, create animated transitions, or visually alter a page element for a certain period of time</li>
</ul>

### What is included

<p><strong><a href="https://tywrenn.github.io/Spry/docs.html">Articles</a></strong> - <a href="https://tywrenn.github.io/Spry/docs.html">Documentation</a> that describe the Spry framework.</p>
<p><strong><a href="https://github.com/adobe/Spry/tree/master/data">Data</a></strong> - The XML data files used in all our sample files. </p>
<p><strong><a href="https://tywrenn.github.io/Spry/demos/">Demos</a></strong> - More <a href="https://tywrenn.github.io/Spry/demos/index.html">complex samples</a> that show the Spry framework in action.</p>
<ul>
<li><a href="https://tywrenn.github.io/Spry/demos/effects/index.html">Effects</a> - A demo of all our Spry Effects. Rewritten in 1.5.</li>
<li><a href="https://tywrenn.github.io/Spry/demos/formsvalidation/index.html">Form Validation</a> - A demo of the Form Validation widgets. </li>
<li><a href="https://tywrenn.github.io/Spry/demos/gallery/index.html" target="_blank">Photo Gallery</a>&#8212;An XML-based photo gallery.</li>
<li><a href="https://tywrenn.github.io/Spry/demos/products/index.html" target="_blank">Product Table</a>&#8212;An interactive data grid displaying XML-based data. </li>
<li><a href="https://tywrenn.github.io/Spry/demos/rssreader/index.html" target="_blank">RSS Reader</a>&#8212;An RSS reader showing how multiple XML files can be used to build a rich interface.</li>
<li><a href="https://tywrenn.github.io/Spry/demos/periodic_table/periodic_table.htm">Periodic Table</a> - A demo of the HTML data set and advanced CSS techniques.</li>
</ul>
<p><strong><a href="https://github.com/tywrenn/Spry/tree/master/includes">Includes</a></strong> - Core JavaScript files that implement the data framework. </p>
<ul>
<li>SpryCSVDataSet.js - Enables CSV files as a data source.</li>
<li>SpryData.js - Contains the code that defines XML data sets and dynamic regions.</li>
<li>SpryDataExtensions.js - Contains helper functions such as advanced filtering.</li>
<li>SpryDataShell.js - A placeholder data set that regions can bind to, which allows data sets of same/different formats to be swapped in and out.</li>
<li>SpryDebug.js - A file that provides advanced debugging information for Spry pages.</li>
<li>SpryDOMUtils.js - Our Element Selector. Manipulate the page using CSS Selectors.</li>
<li>SpryEffects.js - The Spry Effects framework file. </li>
<li>SpryHTMLDataSet.js - Enables the HTML data set functionality.</li>
<li>SpryJSONDataSet.js - Enables JSON as a data source.</li>
<li>SpryNestedJSONDataSet.js - Allows the use of complex JSON as a data source.</li>
<li>SpryNestedXMLDataSet.js - Allows the use of complex XML as a data source.</li>
<li>SpryPagedView.js - Enabled users to easily set up paging in data sets.</li>
<li>SpryTSVDataSet.js - Enables TSV files as a data source. Users can also specify a different field delimiter other than tab.</li>
<li>Spry URLUtils.js - Get URL parameters and hashes to be used with Spry pages.</li>
<li>SpryUtils.js - Contains helper functions, mostly form submission code.</li>
<li>SpryXML.js - Function file for handling XML formatting. Only required for certain sample files. </li>
<li>xpath.js - Google's JavaScript implementation of the <a href="http://www.w3.org/TR/xpath" target="_blank">XPath 1.0</a> standard. You can get more information about it by   visiting their open source <a href="http://goog-ajaxslt.sourceforge.net/" target="_blank">google-ajaxslt project page</a>.</li>
</ul>
<p><strong>includes_minified</strong> - <a href="http://javascript.crockford.com/jsmin.html">Minified</a> copies of all our javascript files..</p>
<p><strong>includes_packed</strong> - <a href="http://dean.edwards.name/packer/">Packed</a> copies of all our javascript files.<br />
</p>
<p><strong><a href="https://tywrenn.github.io/Spry/samples/">Samples</a></strong> - A series of <a href="https://tywrenn.github.io/Spry/samples/index.html">simple files</a> (located within the /samples/ directory in the ZIP) that show basic functionality of Spry . These  provide working code samples of specific features of spry or common  techniques used on Spry pages. One of the more useful samples is the <a href="https://tywrenn.github.io/Spry/samples/data_region/DataSetExplorer.html">Data Set Explorer</a> page. </p>
<p><strong><a href="https://tywrenn.github.io/Spry/widgets/widgets.html">Widgets</a></strong> - Contains our released widget js, css and reference  files. <a href="https://tywrenn.github.io/Spry/widgets/widgets.html">Widget Map</a>.</p>
<p><a href="https://github.com/tywrenn/Spry/blob/master/License.md">License</a>&#8212;Spry is licensed under a MIT license. <br />
<a href="https://tywrenn.github.io/Spry/ChangeLog.html">Spry change log</a>&#8212;Log of what changed between Spry releases.</p>
