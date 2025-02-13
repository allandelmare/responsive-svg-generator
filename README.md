# Responsive SVG Generator

A simple web tool that creates responsive SVG images by combining desktop and mobile versions into a single file. The generated SVG automatically switches between versions based on screen width using CSS media queries.

## Features

- Upload desktop and mobile images with preview of dimensions and aspect ratio. Currently only works with identical aspect ratio images.
- Live preview with resizable width to test responsive behavior
- Customizable mobile breakpoint (default 768px)
- SVG metadata options:
  - Customizable title and description
  - Accessibility attributes (ARIA labels)
- Downloads as a single SVG file with embedded images

## Technical Details

- Pure HTML, CSS, and JavaScript implementation (no dependencies)
- Uses CSS media queries for responsive switching
- Preserves image aspect ratio using SVG viewBox
- Converts images to base64 before embedding in the SVG
- Supports common image formats (PNG, JPG, GIF)

## Limitations

- Both desktop and mobile images must have the same aspect ratio
- Maximum preview width of 1200px
- Minimum preview width of 300px
