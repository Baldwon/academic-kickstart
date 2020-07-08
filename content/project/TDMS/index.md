+++
# Project title.
title = "Time-Domain Mixed-Signal MAC Processor"

# Date this page was created.
date = 2019-12-02T00:00:00

# Project summary to display on homepage.
summary = "Design of 4-bit Time-Domain Mixed-Signal MAC Processor with 8T SRAM Array as Data Cache for Resource-constrained DNN Applications
"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["teachstat"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="r-project", name="R Package", url = "https://github.com/Mr8ND/TC-prediction-bands#2-tcpredictionbands-package"}]


# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
  [image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Deep neural networks (DNN) provide superior classification accuracy in a variety of machine learning applications, such as image/speech/sensor data processing. However, DNN requires intensive computing and memory resources due to the large amount of Multiply-and-Accumulate (MAC) operations, which brings challenges to energy-efficiently employ DNN algorithms in the general-purpose microprocessors under resource-constrained circumstances. Recently, a new technology to achieve energy-efficient MAC operation is proposed: time-domain computing. Multi-bit digital bitstream encoded as PWM signals and frequency varying signals to accomplish MAC operations. In this project, we choose this time-domain architecture to energy-efficiently do the MAC operation. We also use on-chip SRAM array as input data cache to save energy. 
