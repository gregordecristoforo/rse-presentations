class: gray-background

# Research software engineering (RSE) in 10-15 minutes

.left-column50[
.fat[1:] The RSE role

.fat[2:] Toolset

.fat[3:] Courses

.fat[4:] Use cases

.fat[5:] Vision
]

.right-column50[
## [research-software.uit.no](https://research-software.uit.no/)

<img src="img/logo.png" style="height: 250px;"/>
]

---

# About me

.left-column30[
<img src="img/avatar.jpeg" style="width: 80%;"/>
]

.right-column70[
- Theoretical chemist turned research software engineer.

- I write research software and teach programming to researchers and lead the
  [CodeRefinery project](https://coderefinery.org).

- I lead the high-performance computing group and the research software
  engineering group at UiT.
]

---

# Research software engineers

.. are people who combine .emph[professional software expertise] with an .emph[understanding of research] .cite[https://researchsoftware.org/]

- Often people **who grew up in research** and liked computing and programming

- ... or people **who come from software development** drawn towards meaningful and impactful work of academia

- [Society of Research Software Engineering](https://society-rse.org/)

- Recent conference: [RSECon 2022](https://rsecon2022.society-rse.org/)

- https://nordic-rse.org/

- [Nordic-RSE unconference Oct 18-19](https://nordic-rse.org/events/2022-online-unconference/)

---

# FAIR principles and software

Researchers need to navigate many tools and concepts.

<img src="img/turing-way/8-fair-principles.jpg" style="height: 380px;"/>

.cite[(c) [Scriberia](http://www.scriberia.co.uk) for [The Turing Way](https://the-turing-way.netlify.com), CC-BY]

---

<img src="img/reproducible-research.jpg" style="height: 550px;"/>

.cite[Heidi Seibold, CC-BY 4.0, https://twitter.com/HeidiBaya/status/1579385587865649153]

---

# Team and project: [coderefinery.org](https://coderefinery.org/)

- Started in 2016, now we are in phase 3 until 2025
- **Partners**: NeIC (1 FTE), Aalto University, ENCCS, CSC, DeIC, Sigma2/NRIS, SNIC, T1C for interactive HPC (DK), USIT/UiO

.left-column50[
- Over 2000 persons trained
- Over 30 instructors/speakers
- Over 100 exercise leads
- **Pioneering teaching methods**
- **Working in public**
- Lesson material
- Video recordings
- Manuals
- Training network
- Brand
- Impact
- Community
- Knowledge
]

.right-column50[
<img src="img/coderefinery.png" style="height: 250px;"/>
]

---

# Our course portfolio via [coderefinery.org](https://coderefinery.org)

.left-column50[
- Version control
- Collaboration using Git
- Testing
- Documentation
- Notebooks
- Modular code development
- Reproducible research
- Software licensing
- How to share and publish code
- **...**

Lessons and recordings: https://coderefinery.org/lessons/
]

.right-column50[
<img src="img/complex-machine.png" style="height: 400px;"/>

.cite[citation needed]
]

---

# Code review

<img src="img/review.jpg" style="height: 400px;"/>

.quote["but the code is not ready"]

---

# Big problem: visibility and outreach

.quote[[ ] check this box if you would like to be informed about events in future organized by us. This is how we will store your contact information: ...]

Ideas:
- roll-ups
- info-screens
- events
- stands
- office hours

---

# Use case 1: optimization

Oceanography: speed-up of grid mesh generation from days to seconds by a code
rewrite from Matlab to Python+Rust using a more optimal algorithm

<img src="img/mesh.jpg" style="width: 100%;"/>

---

# Use case 2: web development

- [SMARTool: The Strategic Mastery of Russian Tool](https://smartool.github.io/smartool-rus-eng/),
  Using GitHub Pages, JavaScript, and a CSV-based lightweight
  "database" to simplify maintenance, reuse, and contributions.

- [Constructicon: Searchable database of multiword grammatical constructions of Russian](https://constructicon.github.io/russian/).
  Moved a project from a dedicated web server and custom database to GitHub Pages, JavaScript, and a YAML-based lightweight
  "database" to simplify maintenance, reuse, and contributions.

---

# Use case 3: rewrite instead of buying a 30 GB hard disk

```python
# problematic if data.txt is 30 GB big
result = 0.0
with open("data.txt", "r") as f:
    lines = f.readlines()
    for line in lines:
        result += analyze(line)


# better
result = 0.0
with open("data.txt", "r") as f:
    for line in f:
        result += analyze(line)
```

---

class: center, middle, inverse

# A look into the future?

---

# Centralization of resources

- .emph[Reduced focus on hardware]: cloud and pooling

- From local computing centers towards national (e.g.
  [Sigma2/NRIS](https://www.sigma2.no/)) and international compute resources
  (e.g.
  [EuroHPC](https://eurohpc-ju.europa.eu/)/[LUMI](https://lumi-supercomputer.eu/))

- .emph[Distributed support staff]

- Organizations will have to collaborate on training and .emph[stay close to the users]

---

# High-performance computing is changing

- New user interfaces

- New user communities

- HPC in the browser

- Training cluster in the cloud on demand (see e.g. [Magic Castle](https://github.com/ComputeCanada/magic_castle))

- Instead of the Top 500 list more focus on top 100 in terms of .emph[usability or support]?

---

# Our vision

## Short term

- Provide consulting: good advice is **not** expensive
- .emph[Code review] sessions
- Work on "smaller" projects and .emph[document use cases]
- Focus on UiT
- Attract more projects


## Longer term

- Be part of funding applications
- Research groups have access to best in class RSE services
- Hire more staff who collaborate on projects
- "Proper" application procedure
- Going beyond UiT
- .emph[Career path opportunities]

---

# How everything nicely ties together

## Training, RSE-work, High-performance computing

- .emph[Staying current]: If we want to teach programming tools, we also have to write code

- .emph[Complementary skills]: We can solve problems with hardware or with software

- .emph[Progression]: Training events are a great place to advertize services


## Contact: https://research-software.uit.no/contact/
