+++
title = "An Integral Equation Method for the Cahn-Hilliard Equation in the Wetting Problem"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2009-02-26T15:05:00
date_end = 2009-02-26T15:25:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Xiaoyu Wei", "Shidong Jiang", "Andreas Kloeckner", "Xiao-Ping Wang"]

# Location of event.
location = "Spokane, Washington, USA"

# Name of event and optional event URL.
event = "SIAM Conference on Computational Science and Engineering (CSE19)"
event_url = "https://www.siam.org/Conferences/CM/Main/cse19"

# Abstract. What's your talk about?
abstract = "We present an integral equation approach to solving the Cahn-Hilliard equation equipped with boundary conditions that model solid surfaces with certain Young's angles. Discretization of the system in time using convex splitting leads to a modified biharmonic equation at each time step. To solve it, the basic idea is to split the solution into a volume potential computed with free space kernels, plus the solution to a second kind integral equation (SKIE). The volume potential is evaluated with a box-based volume-FMM method. For non-box domains, source density is extended by solving a biharmonic Dirichlet problem. The near-singular boundary integrals are computed using quadrature by expansion (QBX) with FMM acceleration. Our method has linear complexity and can achieve high order convergence with adaptive refinement. We showcase applications in simulating wetting transition and boundary effects on spinodal decomposition."

# Summary. An optional shortened abstract.
summary = "Small well-conditioned linear system, O(N) complexity."

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Optional filename of your slides within your talk folder or a URL.
url_slides = "talk/cahn-hilliard-cse.pdf"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Demo talk page uses LaTeX math.
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Sample dynamics."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++
