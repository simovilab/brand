# Fonts

Typography assets and font files for SIMOVI branding.

## 📁 Contents

This folder should contain:
- Brand font files (TTF, OTF, WOFF, WOFF2)
- Font licensing documentation
- Typography specification sheets
- Web font CSS files

## 🔤 Font Categories

### Primary Typeface
- **Purpose**: Headlines, titles, emphasis
- **Weights**: Light, Regular, Medium, Bold
- **Formats**: Desktop (.ttf/.otf) and web (.woff/.woff2)

### Secondary Typeface  
- **Purpose**: Body text, captions, metadata
- **Weights**: Regular, Italic, Bold
- **Formats**: Desktop (.ttf/.otf) and web (.woff/.woff2)

### Monospace (if applicable)
- **Purpose**: Code, technical documentation
- **Weights**: Regular, Bold

## 📄 Required Files

For each font family, include:
- Font files in multiple formats
- Font specimen/preview sheet
- License information
- Installation instructions
- Web font CSS/SCSS files

## ⚖️ Licensing

- Ensure all fonts have appropriate licenses for intended use
- Include license files with font packages
- Document any usage restrictions
- Provide fallback font recommendations

## 🌐 Web Usage

```css
/* Example web font implementation */
@font-face {
    font-family: 'SIMOVI Primary';
    src: url('simovi-primary-regular.woff2') format('woff2'),
         url('simovi-primary-regular.woff') format('woff');
    font-weight: normal;
    font-display: swap;
}
```
