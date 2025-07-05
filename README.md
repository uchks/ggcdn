# ggcdn
CDN for `gg sans` font: https://cdn.jsdelivr.net/gh/uchks/ggcdn@main/ggsans.css

## How to Use

### Basic Usage

Add the following line to your HTML `<head>` section:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/uchks/ggcdn@main/ggsans.css">
```

Or import it in your CSS:

```css
@import url('https://cdn.jsdelivr.net/gh/uchks/ggcdn@main/ggsans.css');
```

### Apply the Font

Once loaded, you can use the fonts in your CSS:

```css
/* Use GG Sans for regular text */
body {
  font-family: "gg sans", sans-serif;
}

/* Use GG Mono for code/monospace text */
code, pre {
  font-family: "gg mono", monospace;
}
```

### Available Font Weights

**GG Sans:**
- `font-weight: 400` - Normal
- `font-weight: 500` - Medium  
- `font-weight: 600` - SemiBold
- `font-weight: 700` - Bold
- `font-weight: 800` - ExtraBold

**GG Mono:**
- `font-weight: 400` - Normal
- `font-weight: 700` - Bold

### Font Styles

Both italic and normal styles are available for GG Sans:

```css
.italic-text {
  font-family: "gg sans", sans-serif;
  font-style: italic;
  font-weight: 500;
}
```

### Complete Example

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/uchks/ggcdn@main/ggsans.css">
  <style>
    body {
      font-family: "gg sans", sans-serif;
      font-weight: 400;
    }
    
    h1 { font-weight: 800; }
    h2 { font-weight: 700; }
    h3 { font-weight: 600; }
    h4 { font-weight: 500; }
    
    code {
      font-family: "gg mono", monospace;
      font-weight: 400;
    }
    
    .emphasis {
      font-style: italic;
      font-weight: 500;
    }
  </style>
</head>
<body>
  <h1>This is ExtraBold (800)</h1>
  <h2>This is Bold (700)</h2>
  <h3>This is SemiBold (600)</h3>
  <h4>This is Medium (500)</h4>
  <p>This is Normal (400)</p>
  <p class="emphasis">This is Medium Italic</p>
  <code>This is GG Mono</code>
</body>
</html>
```

## Font Files

The CDN serves the following font files:
- `gg-sans-normal-400.woff2` - GG Sans Normal
- `gg-sans-italic-400.woff2` - GG Sans Normal Italic
- `gg-sans-normal-500.woff2` - GG Sans Medium
- `gg-sans-italic-500.woff2` - GG Sans Medium Italic
- `gg-sans-normal-600.woff2` - GG Sans SemiBold
- `gg-sans-italic-600.woff2` - GG Sans SemiBold Italic
- `gg-sans-normal-700.woff2` - GG Sans Bold
- `gg-sans-italic-700.woff2` - GG Sans Bold Italic
- `gg-sans-normal-800.woff2` - GG Sans ExtraBold
- `gg-sans-italic-800.woff2` - GG Sans ExtraBold Italic
- `gg-mono-normal-400.woff2` - GG Mono Normal
- `gg-mono-normal-700.woff2` - GG Mono Bold
