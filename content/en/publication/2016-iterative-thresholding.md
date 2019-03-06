+++
authors = ["Dong Wang", "Haohan Li", "Xiaoyu Wei", "Xiao-Ping Wang"]
abstract = "We proposed an efficient iterative thresholding method for multi-phase image segmentation. The algorithm is based on minimizing piecewise constant Mumford-Shah functional in which the contour length (or perimeter) is approximated by a non-local multi-phase energy. The minimization problem is solved by an iterative method. Each iteration consists of computing simple convolutions followed by a thresholding step. The algorithm is easy to implement and has the optimal complexity O(N logN) per iteration. We also show that the iterative algorithm has the total energy decaying property. We present some numerical results to show the efficiency of our method."
date = 2017-01-01
image_preview = ""
math = true
selected = true
title = "An Efficient Iterative Thresholding Method for Image Segmentation"
publication = "Journal of Computational Physics https://doi.org/10.1016/j.jcp.2017.08.020"
publication_short = "JCP"
url_pdf = "https://arxiv.org/pdf/1608.01431v2"
url_code = "https://github.com/xywei/threshseg"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
draft = false
+++

### Code 

A Matlab implementation is available at 
https://github.com/xywei/threshseg.

### Gallery

- Segmentation example: ![Segmentation](Flowers.png)
- Energy decaying property: ![Energy](Energy.png)
- Graphical user interface: ![GUI](GUI.png)

