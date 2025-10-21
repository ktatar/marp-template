---
marp: true
theme: my_theme
math: katex
paginate: true

---
<!-- _color: black -->

# Cool title with a Background

![bg opacity:30% ](tra-385.webp)

The code above the title is a local directive:

https://marpit.marp.app/directives?id=local-directives-1

---

# What is TRA 385?

This is a list:

- item 1
- item 2
- item 3

---

# This is a table 

| Activities  |  |  | | |
|:---|---|---|---|---|
| **Lectures** | Introduction to Art and Technology | Introduction to AI and ML | Creativity, Group work, and Tools for Innovation |
| **Tutorials** | Creative Coding with Sound (PureData) | Multimedia Design with TouchDesigner | Deep Learning for Multimedia | Interactive ML with Physical Computing |
| **Project** |Project Proposal| Design Iterations | Final Prototype | Reflections |

---
<!-- _class: no_border -->

# This is the same table without borders

| Activities  |  |  | | |
|:---|---|---|---|---|
| **Lectures** | Introduction to Art and Technology | Introduction to AI and ML | Creativity, Group work, and Tools for Innovation |
| **Tutorials** | Creative Coding with Sound (PureData) | Multimedia Design with TouchDesigner | Deep Learning for Multimedia | Interactive ML with Physical Computing |
| **Project** |Project Proposal| Design Iterations | Final Prototype | Reflections |

See how *Activities* are not bold now. That is because th class is updated in section.no_border class in my_theme.css  

---
<!-- _class: columns -->

<div>

## Two column slide

Originally solution from <https://github.com/orgs/marp-team/discussions/192#discussioncomment-1516155>

</div>
<div>

## Can't believe this works. YOLO

If you are brave for more sections, here is an online tool for css grids: https://grid.layoutit.com/

</div>

---

# Image on the left

![bg left](fuse.jpg)

---

# AND Image on the right

![bg right](fuse.jpg)

---

# Local videos are possible 

<video controls src="pb-ars.mp4" width="800"></video>

---

# Online videos as well 

<iframe width="560" height="315" src="https://www.youtube.com/embed/nx2Nj3I7NyU?si=5D-PemuLUUt3qepd&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This should work only when the presentation is hosted online. Youtube does not allow local hosts apparently.

---

# Fancy image options

![bg left:40% width:500px](fuse.jpg "Fuse it up" )

`<br/>` command works for creating empty spaces [2].

<br/>

<small>[1] this is a smaller text. Great for citations. 

[2] https://marpit.marp.app/image-syntax
</small>

---

# Inline HTML commands works 

<p style="font-size:64px;color:red;"> Text can be changed for example </p>

---

# ToDos

- Check Katex integration