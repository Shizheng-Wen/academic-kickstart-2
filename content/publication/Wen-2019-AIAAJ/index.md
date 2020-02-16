+++
title = "Application of Convolutional Neural Networks for Feature Identification in Complex Fluid Flows"
date = 2019-10-21
authors = ["__Shizheng Wen__", "Michael W. Lee", "Kai M. Kruger Bastos", "Earl H. Dowell"]
publication_types = ["3"]
abstract = ""
selected = true
publication = "In submission"
publication_short = "In submission"
url_pdf = "Wen-2019-AIAAJ.pdf"
url_code = "https://github.com/Shizheng-Wen/CNN-identification-in-Fluid-Mechanics"
url_slides = "Presentation.pdf"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Architecture of the conventional CNN employed for buffet flow classification."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

**abstract**:

Recent efforts have shown machine learning to be useful for analysis of nonlinear fluid dynamics. Predictive accuracy is often a central motivation for employing neural networks, but the pattern recognition central to the network’s function is equally valuable for purposes
of enhancing our dynamical insight into sometimes confounding dynamics. In this paper, convolutional neural networks (CNNs) were trained to recognize several qualitatively different subsonic buffet flows over a high-incidence airfoil. The convolutional kernels and
corresponding feature maps, developed by the model with no temporal information provided, identified large-scale coherent structures in agreement with those known to be associated with buffet flows. Sensitivity to hyperparameters including network architecture and convolutional kernel size was explored. One conclusion is that only a small training dataset is necessary, but that smaller kernels are better at coherent structure identification than are larger kernels. A long-short term memory CNN was then used to demonstrate that with the inclusion of temporal information, the coherent structures remained qualitatively comparable to those of the conventional CNN and less dynamically significant features were no longer recorded. The coherent structures identified by these models enhance our dynamical understanding of subsonic buffet over high-incidence airfoils over a wide range of Reynolds numbers.

---

__Summary of this work:__

This work applies machine learning for pattern recognition to a subsonic airfoil experiencing buffet at a high incidence angle and a range of Reynolds numbers. While previous research has applied machine learning to nonlinear fluid flows, little attention has been paid to the coherent structures constructed as part of the neural network. In the context of subsonic buffet flows, this new focus is of particular value.

The significance of this paper lies in the alignment of the learned flow patterns with existing theories on the dynamics of subsonic buffet flows. By extracting the convolutional kernels and corresponding feature maps, it was verified that the convolutional neural network employed in this research had identified large-scale coherent structures believed to drive the buffet phenomenon. The model was able to accomplish this feat without any provided kinematic, or even temporal, information.

While the development of coherent structures was the primary goal of this research, the neural network was given a more discrete task for training purposes: to identify from individual spatial flow snapshots whether the dynamics were periodic, quasi-periodic, or aperiodic (viz. chaotic) in nature. The network was able to accomplish this task with near-perfect accuracy after only several hundred snapshots were provided for training. In the process of developing and training the model, sensitivity studies were performed on several of the hyperparameters which define the neural network architecture. This ensured that the trends observed were not artifacts of the network’s overall construction. One significant finding from these studies, elaborated upon in the submitted article, was that the size of the convolutional kernel affected the coherence of the dynamical structures identified but did not affect the overall model accuracy to the same extent. The cause for this behavior is explained in the submitted paper.

In summary, a convolutional neural network was trained for a simple identification task and the learned coherent structures used by the model for pattern recognition were then studied for dynamical significance. The coherent structures were found to align with current theories on the nature of high-incidence subsonic buffet flows.

You can learn more about this research in my paper!

---

__My contributions:__

+ Trained a convolutional neural network (CNN) that was able to recognize several qualitatively different subsonic buffet flows over a high-incidence airfoil.
+	Verified the capability of the CNN to identify large-scale coherent structures in agreement with those known to be associated with buffet flows by analyzing the convolutional kernels and corresponding feature maps.
+ Explored the sensitivity to hyperparameters including network architecture and convolutional kernel size. 
+	Trained a long-short term memory CNN and demonstrated that with the inclusion of temporal information, the coherent structures remained qualitatively comparable to those of the conventional CNN and less dynamically significant features were no longer recorded.
+	Contributed to a first-author paper to be submitted to AIAA Journal (leading research journal in Aerospace Engineering).

