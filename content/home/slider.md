+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "GWAS in the Cloud"
  content = "Learn how to perform a genome wide association analysis on the Terra platform."
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "dna.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Go to the tutorial"
  cta_url = "project/cloud_workflows"

# [[item]]
#  title = "ASHG workshop 2019"
#  content = "Reproducible GWAS on Terra"
#  align = "center"

#  overlay_color = "#555"  # An HTML color value.
#  overlay_img = ""  # Image path relative to your `static/img/` folder.
#  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

#  cta_label = "See project details"
#  cta_url = "project/cloud_workflows"

[[item]]
  title = "Influenza assembly dynamics"
  content = "Read about my work in modeling viral assembly dynamics from microscopy images."
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "virus.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "See project details"
  cta_url = "project/influenza"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "Type 2 Diabetes genetics"
  content = "Read about our work in understanding the genetic basis of Type 2 Diabetes using whole genome sequence data within diverse populations."
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "dna.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "See publication overview"
  cta_url = "publication/topmed_t2d"
+++