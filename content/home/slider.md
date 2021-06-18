---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...
# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 4000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px


item:
  - title: Media
    content: 'In media'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: kulikgroup_Jun2021_v2.png  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.1  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    #cta_label: Download my app
    #cta_url: 'https://example.org'
    #cta_icon_pack: fas
    #cta_icon: graduation-cap
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    #overlay_img: logo.png
    overlay_filter: 0.1
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    #overlay_img: 'logo.png'
    overlay_filter: 0.1
  - title: Images
    content: 'In Images'
    align: right
    #overlay_color: '#333'
    overlay_img: robot_and_layer_from_wide_fin_rgb.png
    overlay_filter: 0.1
---
