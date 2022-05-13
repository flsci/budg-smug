> #### Commit Messages/

<br>

## Commit-Message Formats

### &#x2192; Breaking-Changes: Option-1

```
# <type>[optional scope]: <description>
build!: update input fields & fetch wells using water-depth

# [optional body]
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
-->(i.e. {grep {grep '^,,,'...} and {'^y,'...} )
- USE-INSTEAD: Water-Depth {==0} & {!=0} to fetch onshore vs offshore wells

- Format of `d0` files generated before this now considered legacy
--> Backward-compatibility will not be supported
- MIGRATE/FIX: Manually update legacy `d0` files to reuse
- -OR- Request getting new `d0` files generated for those wells

# <cr>
# [optional footer(s)]
```

### &#x2192; Breaking-Changes: Option-2

```bash
# <type>[optional scope]: <description>
build!: update input fields & fetch wells using water-depth

# [optional body]
BREAKING CHANGE: the data-fields "Offshore,Mexico,Cuba," were deprecated
and removed from `d0` input-files.

- Pattern-matching used w/ those fields no longer supported
  (i.e. {grep '^y,'...} and {grep '^,,,'...} )
- USE INSTEAD: water-depth {!=0} & {==0} to fetch offshore vs onshore wells

- Format of `d0` files generated before this now considered legacy,
--> Backward-compatibility will not be supported
- MIGRATE/FIX: Update legacy `d0` files manually to reuse
- -OR- Request getting a new set of `d0` files generated for those wells

# <cr>
# [optional footer(s)]
```

<br>

