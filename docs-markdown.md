# test-docs / markdown

<br>

## HTML Entities


<body><table>
<tr>
<td><h3>v1.5.0</h3> <br><sup>(2020-05-05)</sup>
</td>
<td><b>Added&#x2002;&#x2003;&#xFF1A;</b> New format files to import/export 2D horizons.<br>
    <b>Changed&#x00a0;&#xFF1A;</b> Renamed owioformats/ files to improve user readability.
    <br>&#x00A0;
</td>
</tr>
<tr>
<td><b>v1.4.1</b>
    <br><sup>2020-04-12</sup>
</td>
<td><b>Fixed:</b><br>&#x2022;&#x00A0;owioformats/ : Removed outdated interpreter ID & added current to format file for WD surface picks.
    <br>&#x00A0;
    <br>&#x00A0;
</td>
</tr>
<tr>
<td><b>v1.4.0</b>
    <br><sup>2020-01-04</sup>
</td>
<td><b>Added:</b>
    <br>&#x2022;&#x00A0;workflows/ sub-directory and workflow documents.
</td>
</tr>
<tr>
<td><b>v1.3.0</b>
    <br><sup>2020-01-03</sup>
</td>
<td><b>Changed:</b>
    <br>&#x2022;&#x00A0;Updated script files <code>import/wells/</code> : Changed <b><code>mv</code></b> destination for spent i/o files FROM: <b>OLD/</b> TO: <b>d0/</b> and <b>d1/</b> to separate spent i/o files by input (data v.0) and output (data v.1), respectively.
    <br>
    <br>&#x2022;&#x00A0;Updated <b><code>mv</code></b> destination for spent i/o files in <code>import/wells/</code> script files FROM: <b>OLD/</b> TO: <b>d0/</b> and <b>d1/</b> to separate spent i/o files by input (data v.0) and output (data v.1), respectively.
    <br>&#x00A0;
</td>
</tr>
</table></body>

<details>
<summary style="font-weight:600; font-size:1.2em">Spaces
</summary>

<body><table>
<tr>
<td>

| char        | named   | hex   |
|:------------|:--------|:------|
| x yz        | space   |       | 
| x&#x00A0;yz | \&nbsp; | x00A0 |
| x&#x2000;yz | en-quad | x2000 |
| x&#x2001;yz | em-quad | x2001 |
| x&#x2002;yz | \&ensp; | x2002 |
| x&#x2003;yz | \&emsp; | x2003 |
| &#x00A0;    |         |       |

<td>

| char        | named       | hex   |
|:------------|:------------|:------|
| x&#x2004;yz | 3-per-emsp  | x2004 |
| x&#x2005;yz | 4-per-emsp  | x2005 |
| x&#x2006;yz | 6-per-emsp  | x2006 |
| x&#x2007;yz | figure      | x2007 |
| x&#x2008;yz | punctuation | x2008 |
| x&#x2009;yz | \&thinsp;   | x2009 |
| x&#x205F;yz | medium-math | x205F |

</tr>
</table></body>
</details>

<br>

## Box Outlines + Checkboxes

<details>
<summary style="font-weight:bold; font-size:large">
User Configs &#x2611;
</summary>

```
completed : 2021-01-27
```

<br>

> USERS

| <ul><li> [x] AW</li></ul> | <ul><li> [x] CF</li></ul> | <ul><li> [x] JS</li></ul> | <ul><li> [x] MP</li></ul> | <ul><li> [x] MS</li></ul> | <ul><li> [x] ZS</li></ul> |
|:--------------------------|:--------------------------|:--------------------------|:--------------------------|:--------------------------|:--------------------------|

<br>

> OTHER

| <ul><li> [x] JV</li></ul> | <ul><li> [x] PMP</li></ul> | <ul><li> [ ] RC</li></ul> | <ul><li> [ ] WG</li></ul> |
|:--------------------------|:---------------------------|:--------------------------|:--------------------------|

</details>

<br>

<details>
<summary style="font-weight: bold; font-size: larger">
Other Checkbox Styles
</summary>

Function | MySQL / MariaDB | PostgreSQL | SQLite
:------------ | :-------------| :-------------| :-------------
substr | :heavy_check_mark: |  :white_check_mark: | :heavy_check_mark:

</details>

<br>

## Embedding Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE" target="_blank">
<img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
