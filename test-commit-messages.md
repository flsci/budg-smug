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
  (i.e. {grep '^y,'...} and {grep '^,,,'...} )
- USE-INSTEAD: water-depth "!=0" & "==0" to fetch offshore vs onshore wells

- Format of `d0` files generated before this now considered legacy,
  and backward-compatibility will not be supported
- Update legacy `d0` files manually to reuse
- -OR- request updated `d0` files be generated for those wells

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
- --> (i.e. {grep '^y,'...} and {grep '^,,,'...} )
- USE INSTEAD: water-depth {!=0} & {==0} to fetch offshore vs onshore wells

- Format of `d0` files generated before this now considered legacy
- & backward-compatibility will not be supported
- Update legacy `d0` files manually to reuse
- -OR- request updated `d0` files be generated for those wells

# <cr>
# [optional footer(s)]
```

<br>

## Inline-Format Tests

```
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
  (i.e. {grep '^y,'...} and {grep '^,,,'...} )
- USE INSTEAD: water-depth {!=0} & {==0} to fetch offshore vs onshore wells
```
<!--------->
```
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
  (i.e. {grep '^y,'...} and {grep '^,,,'...} )
- USE INSTEAD: fetch offshore vs onshore wells w/ water-depth {!=0}, {==0}
```

<br>

<!--

### Text-Wrapping (v.2):

```
# <type>[optional scope]: <description>
build!: update input fields & fetch wells using water-depth

# [optional body]
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
  i.e. {grep '^y,'...} and {grep '^,,,'...}
- Use water-depth "!=0" & "==0" to fetch offshore vs onshore wells instead

- Format of `d0` files generated before this now considered legacy,
  and backward-compatibility will not supported
- Update legacy `d0` files manually to reuse
- -OR- request updated `d0` files be generated for those wells

# <cr>
# [optional footer(s)]
```

-->
