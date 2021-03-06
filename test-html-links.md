## test-html-links

<br>

# URI Fragments

<!-- ---------------------------------------------------------------------- -->
> ## Using `href` :
>
> * Define links using **`#`** and a fragment name instead of a URL : &#x00A0; **`<a href="#fragment-name">Visible Link</a>`**
> * Then use the **`id=`** attribute to mark the fragment location / link destination : &#x00A0; **`<a id="fragment-name">`**
> * Can also use **`href="#top"`** or an empty fragment (**`href="#"`**) to link the top of current page
  
<br>

<!-- ---------------------------------------------------------------------- -->
<details>
<summary><b>Syntax</b>
</summary>

```html
<!-- <a> element links to the section below -->
<p><a href="#Section_further_down">Jump to the heading below</a></p>

<!-- Heading to link to -->
<h2 id="Section_further_down">Section further down</h2>

<!--Ref: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a-->
```
</details>

<!-- ---------------------------------------------------------------------- -->
<details>
<summary><b>TEST #1</b>
</summary>
  
<ul>
  <li><a href="#layer-props">Layer Properties</a></li>
  <li><a href="#data-sources">GIS Data Sources</a></li>
  <li><a href="#databases">Database Connections</a></li>
  <li><a href="#file-systems">File Systems</a></li>
  <li><a href="#servers">GIS Servers</a></li>
</ul>

</details>

<!-- ---------------------------------------------------------------------- -->
<details>
<summary><b>TEST #2</b>
</summary>
  
<ul>
  <li><a href="#layer-props">Layer Properties</a></li>
  <li><a href="#data-sources">GIS Data Sources</a></li>
  <li><a href="#databases">Database Connections</a></li>
  <li><a href="#file-systems">File Systems</a></li>
  <li><a href="#servers">GIS Servers</a></li>
</ul>

</details>

<!-- ---------------------------------------------------------------------- -->
<details open>
<summary><b>TEST #3</b>
</summary>

* [Layer Properties](#layer-props)
* [GIS Data Sources](#data-sources)
  * [Database Connections](#databases)
  * [File System](#file-systems)
  * [GIS Servers](#servers)

</details>

<br>

<!-- ---------------------------------------------------------------------- -->
> ## Using `name` :
>
> *** The **`name=`** attribute is now deprecated<br >&#x2002;&#x2003; &#x2192; it's superseded by global attribute **`id=`**

<br>

<details>
<summary><b>Syntax</b>
</summary>

* [Section 1](#sect-1)
  * [Subsection 1a](#sect-1a)
  * [Subsection 1b](#sect-1b)
* [Section 2](#sect-2)

<a name="sect-1"></a>
## Section #1: Subtitle

</details>

<details open>
<summary><b>TEST</b>
</summary>

* [Layer Properties](#layer-props)
* [GIS Data Sources](#data-sources)
  * [Database Connections](#databases)
  * [File System](#file-systems)
  * [GIS Servers](#servers)

</details>

<!-- ---------------------------------------------------------------------- -->
<br>
<hr>

# EXAMPLE DOC

<br>

<!--
<a name="layer-props"></a>
<h2 id="layer-props">Layer Properties</h2>
-->

<a id="layer-props"></a>

## Layer Properties

<br>

> #### Finding the `Layer Properties` window :

<table style="width:100%">
<tr>
    <td align="left" width="300px">
    <ol><li>Go to the Inventory pane</li>
        <li>Right-click the layer name</li>
        <li>Select <code><b>Layer Properties</b></code></li>
    </ol>
    </td>
    <td><img src="https://github.com/flsci/gbds-lm5-setup/blob/master/img/guide2/gis-data/layer-props-1.png"/>
    </td>
</tr>
</table>

<!-- ---------------------------------------------------------------------- -->
<br>
<hr>

<!--
<a name="data-sources"></a>
<h2 id="data-sources">GIS Data Sources</h2>
-->

<a id="data-sources"></a>

## GIS Data Sources

##### [ [Database Connections](#databases) &#x00A0;&#x2022;&#x00A0; [File System](#file-systems) &#x00A0;&#x2022;&#x00A0; [GIS Servers](#servers) ]

<!-- ---------------------------------------------------------------------- -->
<br>
<hr>

<!--
<a name="databases"></a>
<h2 id="databases">Database Connections</h2>
-->

<a id="databases"></a>

> ## Database Connections
>
> This feature has not been set up yet, but is in-progress.

<!-- ---------------------------------------------------------------------- -->
<br>
<hr>

<!--
<a name="file-systems"></a>
<h2 id="file-systems">File Systems</h2>
-->

<a id="file-systems"></a>

> ## File Systems
>
> This is currently where you can find shapefiles and images from the `lm4` database.

<!-- ---------------------------------------------------------------------- -->
<br>
<hr>

<!--
<a name="servers"></a>
<h2 id="servers">GIS Servers</h2>
-->

<a id="servers"></a>

> ## GIS Servers
>
> DSG now supports web-based GIS servers, like Esri's ArcGIS Living Atlas of the World.

<br>

> #### ArcGIS Living Atlas basemaps : World Imagery & Light Grey reference

<table>
<tr>
  <td><img src="https://github.com/flsci/gbds-lm5-setup/blob/master/img/guide2/gis-data/living-atlas-imagery.png" /></td>
  <td><img src="https://github.com/flsci/gbds-lm5-setup/blob/master/img/guide2/gis-data/living-atlas-grey.png" /></td>
</tr>
</table>

<br>
<hr>
<!-- ---------------------------------------------------------------------- -->
