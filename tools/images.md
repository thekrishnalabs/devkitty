# Image Tools

Image tools help with resizing, conversion, compression, inspection, and quick visual debugging.
They are useful for frontend workflows, content creation, asset preparation, and documentation.

---

## Purpose

The image family covers conversion, optimisation, metadata inspection, and utility generation.
These tools must stay fast, clean, and easy to understand.

---

## Included Tools

### Image Compressor
Reduces file size while preserving visual quality as much as possible.

### Resize Image
Changes image dimensions with optional aspect ratio control.

### Crop Image
Crops images to a chosen frame or dimension.

### Convert PNG to JPG
Converts PNG images into JPG format where appropriate.

### Convert JPG to PNG
Converts JPG images into PNG format.

### Convert WebP
Converts common image formats into or out of WebP.

### SVG Optimizer
Cleans SVG output and removes unnecessary markup.

### SVG Viewer
Displays SVG content safely and clearly.

### Favicon Generator
Produces favicon-ready output from a source image or logo.

### ICO Converter
Creates ICO files for browser and app use.

### Base64 Image Converter
Encodes images into Base64 data URLs and decodes them back.

### Blur Generator
Creates controlled blur effects for preview and design use.

### Dominant Colour Extractor
Finds the main colour palette in an image.

### Image Metadata Viewer
Shows technical image metadata such as dimensions and format.

### EXIF Remover
Strips EXIF data from uploaded images.

### Placeholder Generator
Creates simple placeholder images for layout testing.

---

## Interaction Standards

Image tools must support:

- Upload and drag-drop flows
- Clear file previews
- Copy or download output
- Format and size visibility
- Safe handling of large files
- Mobile-safe layouts

---

## Output Standards

Image transformations must be predictable.
The user should always know what format, size, and quality level is being produced.

---

## Common Use Cases

- Asset preparation
- Documentation screenshots
- App icon generation
- Favicon creation
- Performance optimisation
- Metadata cleanup
- Design work

---

## Privacy Rules

Whenever technically possible, image processing should happen locally in the browser.
If a workflow requires upload or server-side processing, that must be made explicit.

---

## Future Expansion

This family may later include:

- Palette from image
- Batch image processing
- Transparent background checker
- Image comparison view
- Thumbnail generator
- Watermark preview
