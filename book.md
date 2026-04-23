---
layout: post
title: GDL Book
permalink: /book/
---

"**Symmetry**, as wide or as narrow as you may define its meaning, is one idea by which man through the ages has tried to comprehend and create order, beauty, and perfection."---Hermann Weyl, _Symmetry_

"I have discovered such wonderful things that I was **amazed**...out of nothing I have created a strange new universe."---János Bolyai, in a letter to his father

The Geometric Deep Learning textbook is a resource intended to help students and practitioners enter the field of geometric deep learning. 
As we prepare for releasing our book with MIT Press, we will make individual draft chapters of the book available here. 
We are expecting a cadence of roughly 2--3 weeks per individual chapter release. Once published here, the chapters will remain online, for free.

In addition, we have leveraged the material from the GDL Textbook to support Master's level courses at both [Oxford](https://www.cs.ox.ac.uk/teaching/courses/2023-2024/geodl/timetable.html) and [Cambridge](https://www.cl.cam.ac.uk/teaching/2324/L65/).
Wherever relevant, we will also use this page to share lecture slides corresponding to individual chapters.

### Preparation

The GDL Book does not strongly assume any particular prior mathematical preparation, yet its foundations rest on several key areas of mathematics -- Vector Calculus, Differential Geometry, Topology, Functional Analysis, Spectral Theory and Graph Theory.

Should you wish a more thorough introduction to these mathematical concepts, we warmly recommend starting with:

[**Mathematical Foundations of Geometric Deep Learning**](https://arxiv.org/abs/2508.02723) _(Borde and Bronstein, 2025)_

### Contents

[**Acknowledgement**](book/acknowledgement.html)

[**Preface**](book/preface.html)

[**Notation**](book/notation.html)

#### **Part I:** _Geometric Foundations of Deep Learning_

| _Title_ | _Slides (Oxford)_ | _Slides (Cambridge)_ |
| [**Chapter 1**: _Introduction_](book/introduction.html) | [Lectures 1--2 (_Introduction_)](slides/Oxford_1_2_Introduction.pdf) | [Lecture "0" (_Course Introduction_)](slides/Cambridge_0_Course_Introduction.pdf) |
| [**Chapter 2**: _Foundations of Supervised Learning_](book/foundations.html) | [Lecture 3 (_Learning in High Dimension_)](slides/Oxford_3_Learning_in_High_Dimension.pdf) |  |
| [**Chapter 3**: _Foundations of Equivariant Deep Learning_](book/algebraicpriors.html) |  | [Lecture 1 (_Introduction to Groups and Representations_)](slides/Cambridge_1_Introduction_to_Groups_and_Representations.pdf) |
| [**Chapter 4**: _Foundations of Geometric Deep Learning_](book/geometricpriors.html) | [Lectures 4--5 (_Geometric Priors_)](slides/Oxford_4_5_Geometric_Priors.pdf) |  |

#### **Part II:** _Learning on Geometric Domains_

| _Title_ | _Slides (Oxford)_ | _Slides (Cambridge)_ |
| [**Chapter 5**: _Graphs_](book/graphs.html) | [Lectures 7--8 (_Graphs_)](slides/Oxford_7_8_Graphs.pdf) | [Lecture 4 (_Graph Neural Networks_)](slides/Cambridge_4_Graph_Neural_Networks.pdf) |
| [**Chapter 6**: _Grids_](book/grids.html) | [Lectures 9--10 (_Grids_)](slides/Oxford_9_10_Grids.pdf) |  |
| [**Chapter 7**: _Group Convolution on Homogeneous Spaces_](book/groups.html) | [Lecture 11 (_Groups & Homogeneous Spaces_)](slides/Oxford_11_Groups_Homogeneous_spaces.pdf) | [Lecture 3 (_How To Build Geometric Neural Networks_)](slides/Cambridge_3_How_To_Build_Geometric_Neural_Networks.pdf) |

#### **Part III:** _Geometric Deep Learning at the Bleeding Edge_

TBD.

This work is governed under a Creative Commons CC-BY-NC-ND license. Copyright in this Work has been licensed exclusively to [The MIT Press](https://mitpress.mit.edu), which will be releasing the final version to the public in 2026. All inquiries regarding rights should be addressed to The MIT Press, Rights and Permissions Department.

If you would like to cite any part of the book in your research, for the time being, please cite our [proto-book](https://arxiv.org/abs/2104.13478), using the following BibTeX entry:
```
@article{bronstein2021geometric,
      title="{Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges}", 
      author={Michael M. Bronstein and Joan Bruna and Taco Cohen and Petar Veličković},
      year={2021},
      journal={arXiv preprint arXiv:2104.13478},
}
```

If you notice any factual errors or typos, or have suggestions for exercises to add to the chapters, do not hesitate to contact the authors directly by e-mail at gdl-book@googlegroups.com. If your note leads to an updated version of these chapters, we will credit you in the Acknowledgement.
