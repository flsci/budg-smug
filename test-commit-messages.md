> #### Tests/ Commit Message Formatting/

<br>

## 2nd-Line Indentation

### &#x2192; Text-Wrapping

```
# <type>[optional scope]: <description>
build!: update input fields & fetch wells using water-depth

# [optional body]
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
  --> i.e. {grep '^y,'...} and {grep '^,,,'...}
- Use water-depth "!=0" & "==0" to fetch offshore vs onshore wells instead

- Format of `d0` files generated before this now considered legacy
  & backward-compatibility will not supported
- Update legacy `d0` files manually to reuse
  -Or- request updated `d0` files be generated for those wells

# <cr>
# [optional footer(s)]
```

### &#x2192; Bullets

```
# <type>[optional scope]: <description>
build!: update input fields & fetch wells using water-depth

# [optional body]
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
- --> i.e. {grep '^y,'...} and {grep '^,,,'...}
- Use water-depth "!=0" & "==0" to fetch offshore vs onshore wells instead

- Format of `d0` files generated before this now considered legacy
- & backward-compatibility will not supported
- Update legacy `d0` files manually to reuse
- -Or- request updated `d0` files be generated for those wells

# <cr>
# [optional footer(s)]
```
