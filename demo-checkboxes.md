> #### HTML demos/ Checkboxes/

<br>

## For ../build-x.x.x--task-lists.md

<br>

```html
<table style="table-layout:fixed; width:100%;">
  <tr>
    <td><ul><li>[x] <code>Auto_NEW_Wells</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[x] <code>Auto_Wells_Picks</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[ ] <code>RunThis.script</code> &#x2002;&#x2002; </li></ul></td>
  </tr>
</table>

<table style="table-layout:auto; width:100%;">
...
</table>

```

<table style="table-layout:fixed; width:100%;">
  <tr>
    <td><ul><li>[x] <code>Auto_NEW_Wells</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[x] <code>Auto_Wells_Picks</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[ ] <code>RunThis.script</code> &#x2002;&#x2002; </li></ul></td>
  </tr>
</table>


<table style="table-layout:auto; width:100%;">
  <tr>
    <td><ul><li>[x] <code>Auto_NEW_Wells</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[x] <code>Auto_Wells_Picks</code> &#x2002;&#x2002; </li></ul></td>
    <td><ul><li>[ ] <code>RunThis.script</code> &#x2002;&#x2002; </li></ul></td>
  </tr>
</table>

<h2></h2>

<br>

```
| <ul><li>[x] <kbd>Auto_NEW_Wells.script</kbd> </li></ul> | <ul><li>[ ] <kbd>Auto_Wells_Picks.script</kbd> </li></ul> | <ul><li>[ ] <kbd>RunThis.script</kbd> </li></ul> |
|:--------------------------------------------------------|:----------------------------------------------------------|:-------------------------------------------------|

| <ul><li>[x] <code>Auto_NEW_Wells.script</code> </li></ul> | <ul><li>[ ] <code>Auto_Wells_Picks.script</code> </li></ul> | <ul><li>[ ] <code>RunThis.script</code> </li></ul> |
|:----------------------------------------------------------|:------------------------------------------------------------|:---------------------------------------------------|
```


| <ul><li>[x] <kbd>Auto_NEW_Wells</kbd> &#x2002;&#x2002; </li></ul> | <ul><li>[ ] <kbd>Auto_Wells_Picks</kbd> &#x2002;&#x2002; </li></ul> | <ul><li>[ ] <kbd>RunThis.script</kbd> &#x2002;&#x2002; </li></ul> |
|:------------------------------------------------------------------|:--------------------------------------------------------------------|:------------------------------------------------------------------|

<br>

| <ul><li>[x] <code>Auto_NEW_Wells</code> &#x2002;&#x2002; </li></ul> | <ul><li>[ ] <code>Auto_Wells_Picks</code> &#x2002;&#x2002; </li></ul> | <ul><li>[ ] <code>RunThis.script</code> &#x2002;&#x2002; </li></ul> |
|:--------------------------------------------------------------------|:----------------------------------------------------------------------|:--------------------------------------------------------------------|


<h2></h2>

<br>

```html
<table>
  <tr>
    <td><ul><li>[x] <kbd>Auto_NEW_Wells.script</kbd> </li></ul></td>
    <td><ul><li>[x] <kbd>Auto_Wells_Picks.script</kbd> </li></ul></td>
    <td><ul><li>[ ] <kbd>RunThis.script</kbd> </li></ul></td>
  </tr>
</table>

<!--2nd table uses "<code>" instead of "<kbd>"-->
```

<br>

<table style="width:80%;">
  <tr>
    <td><ul><li>[x] <kbd>Auto_NEW_Wells.script</kbd> </li></ul></td>
    <td><ul><li>[x] <kbd>Auto_Wells_Picks.script</kbd> </li></ul></td>
    <td><ul><li>[ ] <kbd>RunThis.script</kbd> </li></ul></td>
  </tr>
</table>


<table style="table-layout:fixed; width:80%;">
  <tr>
    <td><ul><li>[x] <code>Auto_NEW_Wells.script</code> </li></ul></td>
    <td><ul><li>[x] <code>Auto_Wells_Picks.script</code> </li></ul></td>
    <td><ul><li>[ ] <code>RunThis.script</code> </li></ul></td>
  </tr>
</table>


<br>

## HTML + Inline Markdown


```html
<ul><li>[x] <kbd>Auto_NEW</kbd> </li> <li>[ ] <kbd>Auto_Wells</kbd> </li></ul>
```

<ul><li>[x] <kbd>Auto_NEW</kbd> </li> <li>[ ] <kbd>Auto_Wells</kbd> </li></ul>

<h2></h2>

```html
<ul><li>[x] <code>Auto_NEW</code> </li> <li>[ ] <code>Auto_Wells</code> </li></ul>
```

<ul><li>[x] <code>Auto_NEW</code> </li> <li>[ ] <code>Auto_Wells</code> </li></ul>

<h2></h2>

```html
<ul><li>[x] <kbd>Auto_NEW</kbd> [ ] <kbd>Auto_Wells</kbd></li></ul>

<ul><li>- [x] <kbd>Auto_NEW</kbd> - [ ] <kbd>Auto_Wells</kbd></li></ul>
```

<ul><li>[x] <kbd>Auto_NEW</kbd> [ ] <kbd>Auto_Wells</kbd></li></ul>

<ul><li>- [x] <kbd>Auto_NEW</kbd> - [ ] <kbd>Auto_Wells</kbd></li></ul>


<br>

## HTML + Markdown tables

```
| <ul><li>[x] `Auto_NEW` </li> <li>[ ] `Auto_Wells` </li></ul> |
|:-------------------------------------------------------------|

| <ul><li>[x] <kbd>Auto_NEW</kbd></li> <li>[ ] <kbd>Auto_Wells</kbd></li></ul> |
|:-----------------------------------------------------------------------------|

| <ul><li>[x] <code>Auto_NEW</code></li> <li>[ ] <code>Auto_Wells</code></li></ul> |
|:---------------------------------------------------------------------------------|
```

| <ul><li>[x] `Auto_NEW` </li> <li>[ ] `Auto_Wells` </li></ul> |
|:-------------------------------------------------------------|

<br>

| <ul><li>[x] <kbd>Auto_NEW</kbd></li> <li>[ ] <kbd>Auto_Wells</kbd></li></ul> |
|:-----------------------------------------------------------------------------|

<br>

| <ul><li>[x] <code>Auto_NEW</code></li> <li>[ ] <code>Auto_Wells</code></li></ul> |
|:---------------------------------------------------------------------------------|

<h2></h2>

```
| <ul><li>[x] `Auto_NEW` </li></ul> | <ul><li>[ ] `Auto_Wells` </li></ul> |
|:----------------------------------|:------------------------------------|

| <ul><li>[x] <kbd>Auto_NEW</kbd> </li></ul> | <ul><li>[ ] <kbd>Auto_Wells</kbd> </li></ul> |
|:-------------------------------------------|:---------------------------------------------|

| <ul><li>[x] <code>Auto_NEW</code> </li></ul> | <ul><li>[ ] <code>Auto_Wells</code> </li></ul> |
|:---------------------------------------------|:-----------------------------------------------|
```

| <ul><li>[x] `Auto_NEW` </li></ul> | <ul><li>[ ] `Auto_Wells` </li></ul> |
|:----------------------------------|:------------------------------------|

<br>

| <ul><li>[x] <kbd>Auto_NEW</kbd> </li></ul> | <ul><li>[ ] <kbd>Auto_Wells</kbd> </li></ul> |
|:-------------------------------------------|:---------------------------------------------|

<br>

| <ul><li>[x] <code>Auto_NEW</code> </li></ul> | <ul><li>[ ] <code>Auto_Wells</code> </li></ul> |
|:---------------------------------------------|:-----------------------------------------------|


<h2></h2>

```
|                Task | Current Status |                                            Finished |
|--------------------:|:---------------|----------------------------------------------------:|
| `<ul><li>- [x] ...` | in progress    | <ul><li>- [x] item-a</li><li>- [ ] item-b</li></ul> |
|   `<ul><li>[x] ...` | in progress    |     <ul><li>[x] item-a</li><li>[ ] item-b</li></ul> |
```

<br>

|                Task | Current Status |                                            Finished |
|--------------------:|:---------------|----------------------------------------------------:|
| `<ul><li>- [x] ...` | in progress    | <ul><li>- [x] item-a</li><li>- [ ] item-b</li></ul> |
|   `<ul><li>[x] ...` | in progress    |     <ul><li>[x] item-a</li><li>[ ] item-b</li></ul> |


<br>

## HTML

```html
<form method="post" action="/Tests/Post/">      
    <fieldset>      
        <legend>What is Your Favorite Pet?</legend>      
        <input type="checkbox" name="favorite_pet" value="Cats">Cats<br>      
        <input type="checkbox" name="favorite_pet" value="Dogs">Dogs<br>      
        <input type="checkbox" name="favorite_pet" value="Birds">Birds<br>      
        <br>      
        <input type="submit" value="Submit now" />      
    </fieldset>      
</form>

<!--
from: html5-tutorial.net/forms/checkboxes -->
```

<form method="post" action="/Tests/Post/">      
    <fieldset>      
        <legend>What is Your Favorite Pet?</legend>      
        <input type="checkbox" name="favorite_pet" value="Cats">Cats<br>      
        <input type="checkbox" name="favorite_pet" value="Dogs">Dogs<br>      
        <input type="checkbox" name="favorite_pet" value="Birds">Birds<br>      
        <br>      
        <input type="submit" value="Submit now" />      
    </fieldset>      
</form>

<h2></h2>

