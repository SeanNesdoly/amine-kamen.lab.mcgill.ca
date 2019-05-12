+++
# Slider widget
widget = "slider"
active = true 
weight = 20
headless = false

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "BioRad QX200 Droplet Digital PCR System"
  align = "left"
  content = """
The QX200 Droplet Digital PCR (ddPCR™) System provides absolute quantification
of target DNA or RNA molecules for EvaGreen or probe-based digital PCR
applications.
"""

  # Overlay an image. Path is relative to `static/img/`.
  overlay_img = "resources/bio-rad-ddPCR.jpg"
  overlay_filter = 0.5 # Darken the image. Value in range [0,1].

[[item]]
  title = "GE ÄKTA - Avant Purification System"
  align = "left"
  content = ""

  overlay_img = "resources/akta-avant.png"
  overlay_filter = 0.5

[[item]]
  title = "Waters - HPLC Alliance System"
  align = "left"
  content = """
Reliable and flexible workhorse for HPLC separations. The advance software
functionality simplifies method development and reporting.
"""

  overlay_img = "resources/HPLC-alliance.jpg"
  overlay_filter = 0.5
  
[[item]]
  title = "BioRad - Chemidoc XRS+ System"
  align = "left"
  content = """
Based on CCD technology and modular options, the imaging system accommodates a
wide range of samples and supports multiple detection methods including
fluorescence, colorimetry, densitometry, chemiluminescence, and
chemifluorescence.
"""

  overlay_img = "resources/chemidoc.jpg"
  overlay_filter = 0.5
  
[[item]]
  title = "Pall-Life - Micro-24 MicroReactor"
  align = "left"
  content = """
A system offering significant advantages over shake flask screening for high
output processes. Its design offers superior mixing allowing researchers the
flexibility to quickly optimize processes.
"""

  overlay_img = "resources/micro24-microreactor.jpg"
  overlay_filter = 0.5
  

[[item]]
  title = "Applikon - Bioreactors & my-Control units"
  align = "left"
  content = """
Our control units enable us to operate bioreactors of different capacities, up
to 3 liters. These are suitable to generate enough material for small scale
applications and modify conditions for scaling up purposes.
"""

  overlay_img = "resources/applikon-control-system.jpg"
  overlay_filter = 0.5
  
[advanced]
 # Custom CSS
 css_style = "background-size: contain; background-position: 90%;"
+++
