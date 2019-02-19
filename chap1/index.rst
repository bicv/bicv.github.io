.. title: Chapter 1. Introduction, G. Cristóbal, L. Perrinet and M. Keil
.. slug: chap1
.. date: 2016-01-06 11:08:19 UTC+01:00
.. tags:
.. link:
.. description:

Introduction
------------

As state-of-the-art imaging technologies become more and more advanced,
yielding scientific data at unprecedented detail and volume, the need to
process and interpret all this data has made image processing and
computer vision also increasingly important. Sources of data that have
to be routinely dealt with for today’s applications include video
transmission, wireless communication, automatic fingerprint processing,
massive databanks, non-weary and accurate automatic airport screening,
robust night vision to name a few. These technological advances were
closely followed by the increase in computer power of traditional,
von-Neumann architectures. However, a major concern is that such
architectures are efficient for specific computations such as retrieving
an item in a database, or apply a precise sequence of operations. These
usually fail when the application becomes closer to biological vision,
such as the categorization of images independently of changes of
lightning, movements, changes in the environment or the imaging device.
Surprisingly, while computers can handle most complex tasks (such as
computing hash numbers, logarithms and linear algebra), most of the
time, the “simpler” the task is (such as “find the animal in the
image”), the more complex it becomes to implement on a computing device.
Multidisciplinary inputs from other disciplines such as computational
neuroscience, cognitive science, mathematics, physics and biology had
and will have a fundamental impact in the progress of imaging and vision
sciences. One main advantage of the study of biological organisms is to
devise very different types of computational paradigms beyond the usual
von Neumann architecture, e.g. by implementing a neural network with a
high degree of local connectivity, which may be more adapted to solve
the problems of modern imaging.

.. thumbnail:: ../images/erbeni.jpg
   :width: 70 %
   :align: center

   The *Erbenochile erbeni* eyes are distributed in a vertical
   half-cylinder surface with 18 or 19 lenses per vertical row. Note the
   striking similarity of this natural eye with the CurvACE sensor
   presented in Fig. 22 of chapter [007\_voelkel]. Image credit:
   Wikipedia [fig:erbeni]

This book provides a comprehensive but rigorous reference in the area of
biologically inspired computer vision modeling. Biologically-inspired
vision, that is, the study of living beings’ visual systems, can be
considered as a two way avenue. On the one hand, living organisms can
provide a source of inspiration for new computational efficient and
robust vision models and on the other hand machine vision approaches can
provide new insights for understanding biological visual systems. Along
the different chapters, this book covers a wide range of topics from
fundamental to more specialized topics. Following the classical Marr’s
premise for vision of three levels of analysis based on a computational
level, an algorithmic level and a hardware implementation
level, this book also analyzes the influence
of these studies in the design of novel, more advanced vision sensors.
In particular, the last section of the book provides an overview of few
representative applications and current state of the art of the research
in this area.

The scope of this book somewhat overlaps with a few other books
published in this area, most of them corresponding to conference
proceedings. Most recently,
several special sessions on this same topic were organized at different
workshops such as the “Biologically-consistent vision” in conjunction
with the 2011 Computer Vision and Pattern Recognition Conference and the
“Biological and Computer Vision Interfaces” in conjunction with the 2012
European Conference on Computer Vision. The first monograph on this
topic was published more than 20 years
ago and therefore does not reflect the
latest advances in the field. A very good reference in the field is the
book by Frisby & Stone that provides the
foundations of the computational and physiological research on vision.
Another relevant reference is the book by Petrou & Bharath although it
is more focused toward specialized hardware both at low-power and high
speed. A more recent reference in the area
is the book by Pomplum & Suzuki which is
more focused on specific aspects of visual function such as attention,
binocularity or cortical structures. At the time of writing, it is worth
to mention a special issue on bio-inspired imaging which highlights
recent progress in the domain of vision and biological
optics. As a consequence, this book is
valuable for both undergraduate and graduate students but also for
specialized researchers by tackling information that is usually spread
out in different sources in a single and comprehensive monograph.

Why should we be inspired by biology?
-------------------------------------

A central question that can be formulated in this area is to understand
why and how it is useful to build technical systems with a biological
inspiration? Or putting it in other terms, why should
biologically-motivated studies be useful for constructing artificial
systems? It is clear that living systems are a continuous source of
inspiration. In this book, we will try to cover few examples of how such
biological findings will be of direct benefit e. g. for engineering new
devices and sensors. More generally, the main motto of this book is to
provide some insights on the “two-way avenue” analogy previously
mentioned. On the one hand there are chapters were findings from
biology, neurobiology or psychophysics are guiding the development of
computer vision algorithms and on the other hand there are other more
technical chapters that are motivated by biology.

In general, we can argue that Nature has been continuously a source of
inspiration not only for constructing artificial vision systems but also
in other domains such as material science. The coined term “biomimetics”
is the field of science and engineering that seeks to understand and to
use nature as a model for copying, adapting and inspiring concepts. An
early amazingly Nature’ design can be observed in the *Erbenochile
erbeni* a Devonian trilobite with calcite-derived compound eyes allowing
the animal to see not only 360 degrees on the horizontal plane but also
to cover a significant vertical area. Even more intriguing is the fact
that their eyes have eye shades and blocking glare which suggest that
trilobites were diurnal and not nocturnal (see
Fig. [fig:erbeni]). In some cases the
visual system of some organisms surpasses the human visual system’
performance. As such, it becomes clear that a clear advantage of living
organisms resides in evolution and natural selection. This led to
efficient solutions to many of the challenges they face. Therefore,
humans always make efforts to use nature as a model for innovation and
problem solving.

But here is more to it. For instance, the peacock mantis shrimp’ eyes
(*Odontodactylus japonicus*) are capable of serial or parallel vision,
trinocular vision, depth perception and the color vision is extended to
the ultraviolet and infrared ranges (see left cover image of this book).
They also exhibit at least sixteen different photoreceptors and
detection of polarized light and circular polarized light. Inspired by
the mantis shrimp’s compound eye and polarized vision, an international
team of researchers have recently built a miniature sensor that can
detect subtle differences in early stage cancerous cells from in vivo
endoscopy of mouse colon. The eyes of other
animals use other strategies to solve predatory tasks. The jumping
spider use special staircase-shaped retinas to produce sharp and out-of
focus images simultaneously (see right cover image of this book). By
comparing the focused and defocused images the spider can estimate depth
through unmoving eyes. Nagata et al have developed a mathematical model
that predicts the accuracy of the jumps for different
wavelengths. These recent promising
results could open up new avenues both in mathematical modeling and
signal processing for more challenging applications. In the context of
animal vision studies, Land & Nilsson’s book
provides a fascinating comparative account of the evolution and function
of animal eyes with emphasis on the optical system description. Also, a
very recent book on the same topic is Cronin et al’s
book. As a consequence,
biologically-inspired computer vision is not only about mimicking the
structure of animals’ visual systems, but to gain insights from the vast
range of different solutions that emerged through natural selection to
provide efficient solution to vision-based problems.

Organization of chapters in the book
------------------------------------

This book contains 17 chapters that have been organized in four
different parts:

-  Fundamentals

-  Sensing

-  Modeling

-  Applications

.. thumbnail:: ../images/mindmap.png
   :width: 70 %
   :align: center

   Mindmap of the book contents. Cross-links between chapters have been
   indicated as thin lines. [fig:mindmap]

The cross-links between the different chapters have been sketched in
Fig. [fig:mindmap]. This book aims at providing an overview about
bio-inspired computer vision bringing together from fundamentals to the
most recent advances and applications in the field. The three chapters
selected in the Applications section are good representatives of how the
transfer of ideas from biology to computer vision can be done in
practice. Fig. [fig:tagcloud] shows a picture of a tag cloud that has
been generated from the table of contents of the book.

The structure of the book is as follows (see also the :doc:`toc`):

-  Section 1: Fundamentals.

   -  Chapter 1 describes the basic bioinspired vision technology with
      the aim of outperforming conventional frame-based vision systems
      in many applications fields. It provides an overview of biosensors
      and neuromorphic retinas.

   -  Chapter 2 describes how the retina is able to process much more
      complicated information processing that were initially thought.

   -  Chapter 3 describes how natural image statistics can be exploited
      to effectively improve visual inference in computer vision
      systems.

   -  Chapter 4 provides the basics of visual psychophysics i.e. how to
      measure the performance of observers in predetermined visual
      tasks.

-  Section 2: Sensing.

   -  In chapter 5, algorithms inspired in the compound eyes of insects
      based on sensing the polarization of light are described,
      illustrating how this can be modeled to enhance the visual
      perception of standard cameras.

   -  Chapter 6 describes how natural concepts for miniaturization could
      be imitated for building computer vision systems with perfect
      adaptation to as small size, special tasks and specific
      applications.

   -  Chapter 7 describes the basics of plenoptic sensing and how these
      new devices can extend the capabilities of current standard
      cameras.

-  Section 3: Modeling.

   -  Chapter 8 describes Bayesian models as a useful modeling approach
      for describing perception and behavior at the computational level.

   -  Chapter 9 explains how neurodynamical models could be used not
      only as biologically inspired models for processing images but
      also for explaining perceptual phenomena.

   -  Chapter 10 presents models of bottom-up visual attention and their
      applications.

   -  Chapter 11 presents a review of several recent studies focusing on
      the integration of retinal and extra-retinal information for
      visual motion processing and human tracking behavior.

   -  Chapter 12 describes cortical models for image recognition mainly
      based on the HMAX architecture of Riesenhuber and
      Poggio.

   -  Chapter 13 describes how bio-inspired approaches may be applied to
      computer vision problems using predictive coding schemes focusing
      on sparse models as simple and efficient instances of such models.

   -  Chapter 14 describes methods for extracting and representing key
      points motivated from a biological standpoint.

-  Section 4: Applications.

   -  Chapter 15 describes how by mimicing neural processes of nocturnal
      animals, efficient computer vision algorithms can be devised.

   -  Chapter 16 provides an overview of elementary motion detectors
      (EMDs) oriented to computer vision applications when resources
      available are limited (e.g. power consumption).

   -  Finally, chapter 17 describes in detail a bioinspired model
      (ViSTARS) oriented to visually guided navigation in a cluttered
      world.

.. thumbnail:: ../images/tag.png
   :width: 70 %
   :align: center

   Tag cloud of the abstracts and table of contents of the book. Credit:
   wordle.net [fig:tagcloud]

Conclusions
-----------

Biological vision shows excellence in terms of performance and
robustness. Following one of the recommendations of the book referees,
one of the aims of the book is to make it multidisciplinary although
perhaps in the future the topic of biologically inspired computer vision
could become a single discipline by itself. One of the reasons of the
resurging interest in the topic of the book has been both the
availability of massive computing power (e.g. cloud computing) and high
performant computing power (GPU, FPGA, etc). This has been illustrated
in the chapters [016\_oskarsson, 017\_tim\_tiedemann] of this book.

For the reader’s convenience, there is an `accompanying website with
supplementary material <http://bicv.github.io>`_. It contains selected MATLAB
and Python codes, testing images and errata.

Acknowledgements
----------------

We would like to express our appreciation for the quality of chapter
delivered by the authors and for their efforts to keep the chapter
length within the limits given. This project has not been achieved
without the valuable contributions made by a significant number of
experts in the field from both the academia and industry. We are
grateful to their willingness to contribute to this groundbreaking
resource. We would like to extend thanks to all the Wiley VCH members
that help us managing the project and in particular to Val Moliere for
her enthusiastic support. We want to express also our gratitude to Roy
L. Caldwell and Thomas Shahan for providing us the macro pictures of the
book cover (*Odontodactylus japonicus male* (left) and *Phidippus audax
male* I(right)).
