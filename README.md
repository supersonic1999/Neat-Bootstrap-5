# Neat Bootstrap
If you decided to use Bootstrap in several places of your site but including Bootstrap CSS rewrites your styles in other places you should use this CSS file.

Every bootstrap selector has had the letter n prepended to it. For example .col-sm-6 is now .ncol-sm-6. This works better than other isolated bootstrap versions because it doesnt apply this version's css on top of the existing bootstrap css.

## Usage

1. Include this file in the head of a HTML page.

```html
<link rel="stylesheet" href="nBoot.css">
```
2. Create `div` element with `class="nBoot"` where you want to use Bootstrap styles.
3. It's ready to use:
```html
<!-- there Bootstrap doesn't work -->
<div class="nBoot">
    <!-- there Bootstrap works-->
</div>
<!-- there Bootstrap doesn't work-->
```
