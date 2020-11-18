---
title: "GodExpo: an automated god structure detection tool for Golang"
collection: publications
permalink: /publications/GodExpo_IWOR_2019
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-5-28
venue: 'Montréal, QC, Canada'
#paperurl: 'http://galib19.github.io/files/GodExpo_IWOR_2019.pdf'
citation: 'Yasir, R. M., Asad, M., Galib, A. H., Ganguly, K. K., & Siddik, M. S. (2019, May). GodExpo: an automated god structure detection tool for Golang. In 2019 IEEE/ACM 3rd International Workshop on Refactoring (IWoR) (pp. 47-50). IEEE.'


---

[[PDF]](http://galib19.github.io/files/GodExpo_IWOR_2019.pdf)
## Abstract 

God Class is a class that threatens maintainability
and understandability of code by performing most of the work
alone. Various tools exist that can detect God Class of Java or
C++ programs, however, there is no existing tool for detecting
God Class(Structure) in Golang. Although Golang is not an
object-oriented language, it offers structures which are similar
to classes in OOP as they can contain fields and methods. Unlike
OOP, methods of a structure can be defined on any file in the
package of Golang. This paper presents a tool entitled GodExpo
to detect God Structures in Golang programs by calculating
metrics namely Weighted Method Count, Tight Class Cohesion,
and Access to Foreign Data. In addition, GodExpo can provide
version wise result to observe the evolution of God structures.
To evaluate GodExpo, an experiment has been conducted on
several versions of two open source Golang projects and the tool
successfully found God structures in all versions of those projects.

## Keywords 

God Class, Code Smell, Golang, OOP Metrics