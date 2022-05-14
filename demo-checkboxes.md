> #### HTML demos/ Checkboxes/

<br>

## Markdown + HTML

#### [ Code ]

```
|                Task | Current Status |                                            Finished |
|--------------------:|:---------------|----------------------------------------------------:|
| `<ul><li>- [x] ...` | in progress    | <ul><li>- [x] item-a</li><li>- [ ] item-b</li></ul> |
|   `<ul><li>[x] ...` | in progress    |     <ul><li>[x] item-a</li><li>[ ] item-b</li></ul> |

```

> [ Rendered ]

|                Task | Current Status |                                            Finished |
|--------------------:|:---------------|----------------------------------------------------:|
| `<ul><li>- [x] ...` | in progress    | <ul><li>- [x] item-a</li><li>- [ ] item-b</li></ul> |
|   `<ul><li>[x] ...` | in progress    |     <ul><li>[x] item-a</li><li>[ ] item-b</li></ul> |

<br>

## HTML `form` & `fieldset`

#### [ Code ]

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

#### [ Rendered ]

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

#### [ Refs ]

* [HTML5 Tutorial](https://html5-tutorial.net/forms/checkboxes/)
