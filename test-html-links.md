
## test-html-links

<br>

<!-- ---------------------------------------------------------------------- -->
> ## `href` attribute:
>
> Can also use `href="#top"` (or the empty fragment `href="#"`) to link the top of current page.

<br>

### Syntax:

```html
<!-- <a> element links to the section below -->
<p><a href="#Section_further_down">
  Jump to the heading below
</a></p>

<!-- Heading to link to -->
<h2 id="Section_further_down">Section further down</h2>


<!--
Ref: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a
-->
```


### Test:

<ul><li><a href="#layer-props">Layer Properties</a></li>
    <li><a href="#data-sources"></a>GIS Data Sources</li>
        <ul><li><a href="#databases">Database Connections</a></li>
            <li><a href="#file-systems">File Systems</a></li>
            <li><a href="#servers"></a>GIS Servers</li>
        </ul>
</ul>

<!-- ---------------------------------------------------------------------- -->
> ## `name` attribute:
>
> As seen in many markdown refs.

<br>

### Syntax:

* [Section 1](#sect-1)
  * [Subsection 1a](#sect-1a)
  * [Subsection 1b](#sect-1b)
* [Section 2](#sect-2)

<a name="sect-1"></a>
## Section #1: Subtitle


### Test:

* [Layer Properties](#layer-props)
* [GIS Data Sources](#data-sources)
  * [Database Connections](#databases)
  * [File System](#file-systems)
  * [GIS Servers](#servers)

<!-- ---------------------------------------------------------------------- -->
<hr>

<!-- EXAMPLE DOCUMENT -->

<h1 id="layer-props">Layer Properties</h1>

<a name="layer-props"></a>
# Layer Properties

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

<br>

> #### Layer Properties window :

<img src="https://github.com/flsci/gbds-lm5-setup/blob/master/img/guide2/gis-data/layer-props-2.png" width="40%"/>

<!-- ---------------------------------------------------------------------- -->
<br><hr>

<h1 id="data-sources">GIS Data Sources</h1>

<a name="data-sources"></a>
# GIS Data Sources

##### [ [Database Connections](#databases) &#x00A0;&#x2022;&#x00A0; [File System](#file-systems) &#x00A0;&#x2022;&#x00A0; [GIS Servers](#servers) ]

<!-- ---------------------------------------------------------------------- -->
<br>

<h2 id="databases">Database Connections</h2>

<a name="databases"></a>
> ## Database Connections
>
> This feature has not been set up yet, but is in-progress.

<!-- ---------------------------------------------------------------------- -->
<br>

<h2 id="file-systems">File Systems</h2>

<a name="file-systems"></a>
> ## File Systems
>
> This is currently where you can find shapefiles and images from the `lm4` database.

<!-- ---------------------------------------------------------------------- -->
<br>

<h2 id="servers">GIS Servers</h2>

<a name="servers"></a>
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

<!-- ---------------------------------------------------------------------- -->
