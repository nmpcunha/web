# @web/rollup-plugin-html

## 1.2.1

### Patch Changes

- cfdeb98: - do not touch `<script>` tags with inline content/code
  - treat `<script src="...">` tags as assets

## 1.2.0

### Minor Changes

- 23fadf2: allow disabling default inject behavior

### Patch Changes

- Updated dependencies [a7c9af6]
  - @web/parse5-utils@1.1.2

## 1.1.1

### Patch Changes

- d804089: don't hash social media and browser assets
- 717c415: Prevent remote URLs from counting as assets
- 9e18d84: write asset paths relative to HTML file

## 1.1.0

### Minor Changes

- 50ba2d6: watch referenced assets

## 1.0.2

### Patch Changes

- d130352: bundle referenced HTML assets

## 1.0.1

### Patch Changes

- 12da341: remove prepublish script

## 1.0.0

### Major Changes

- 3121966: First release

### Patch Changes

- Updated dependencies [3121966]
  - @web/parse5-utils@1.1.0
