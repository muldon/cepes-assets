# cepes-assets

A simple image repository for hosting static assets (SVG, PNG, JPEG, etc.) accessible via `<img>` tags in HTML.

## Folder Structure

```
images/
├── icons/        # Small icons and UI elements
├── logos/        # Logo images
└── backgrounds/  # Background images and banners
```

## How to Use Images

Images stored in this repository can be referenced directly in HTML using the GitHub raw content URL.

### URL Format

```
https://raw.githubusercontent.com/muldon/cepes-assets/main/images/<subfolder>/<filename>
```

### Examples

**Icon:**
```html
<img src="https://raw.githubusercontent.com/muldon/cepes-assets/main/images/icons/sample-icon.svg"
     alt="Sample Icon" width="64" height="64">
```

**Logo:**
```html
<img src="https://raw.githubusercontent.com/muldon/cepes-assets/main/images/logos/sample-logo.svg"
     alt="Sample Logo" width="200" height="60">
```

**Background:**
```html
<img src="https://raw.githubusercontent.com/muldon/cepes-assets/main/images/backgrounds/sample-background.svg"
     alt="Sample Background" width="800" height="400">
```

## Adding New Images

1. Place your image file in the appropriate subfolder under `images/`.
2. Commit and push to the `main` branch.
3. Reference it using the raw URL pattern shown above.

## Available Images

| File | Category | Preview URL |
|------|----------|-------------|
| `sample-icon.svg` | icons | [View](https://raw.githubusercontent.com/muldon/cepes-assets/main/images/icons/sample-icon.svg) |
| `sample-logo.svg` | logos | [View](https://raw.githubusercontent.com/muldon/cepes-assets/main/images/logos/sample-logo.svg) |
| `sample-background.svg` | backgrounds | [View](https://raw.githubusercontent.com/muldon/cepes-assets/main/images/backgrounds/sample-background.svg) |
