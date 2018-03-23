**Experiment design in Digital Musicology**

  

**Concept**

The experiment we are planning to conduct deals with psychoacoustics and the way people perceive sound, with a potential focus on cases when it is perceived as a background. We would like to reproduce and try to extend Dr Eero Simoncelli’s work on joint statistics analysis of textures and how their modeling matches our perception processes.

  

Dr Simoncelli’s contributions to the field of perceptual physics include, among other things, the concept of _lesioned textures._ Lesioned textures are imperfect copies of an original texture generated using gaussian or white noise as a starting point and iterating an algorithm over it to lead it to gradually become closer to the original, taking several statistics (which are computed locally all over the original image) as criteria for similarity. These criteria statistics are called constraint functions.

  

The idea behind this process is simple : both textures obtained are locally identical in terms of the chosen constraint functions, so it allows to test hypotheses about what kind of data or statistics the human brains actually perceives in a picture and to quickly verify it. To make this easier to understand: in an extreme case, if both picture would look exactly the same to human eyes, this would mean we have found the constraint functions that match exactly the way our brain analyses a picture.

More generally speaking, obtaining two images which are quite similar indicates that the chosen set of constraint function works in a similar way as the human sensory system, whereas strong dissimilarity probably indicates we have overlooked an important aspect of the way a stimuli is translated to our brain.

Whilst Dr Simoncelli did publish papers about joint statistics in sound texture perception, we have the feeling that a much smaller corpus of works has been released in the field of auditory perception in general. Our study would continue Dr Simoncelli’s work on sound perception and the creation of _auditory lesioned texture_. Some of the questions we would like to address include:

 
- What are the contraint functions set that we can find that yield the reproduction which is the most faithful according to human ears? Can we draw parallels with our understanding of the auditory system?

- Can we actually create sound that are closely related and hard to distinguish? If not, is it possible to create sounds that are indistinguishable when heard as a background? For instance, together with a human voice on which we would ask the subject to focus, for instance.

- Would a sudden change in one of the statistics be heard immediately when the texture is only in the background?

- If only static sound textures can be reproduced this way, what are the boundaries of this definition, what refrains us from doing the same with music? (Are there constraint function which seem to work well for music or other types of sound which would not be characterized as textures?)

**Extra question to further the research in the neuroscience field:** Can we generate sounds that elicit very similar response in the cortex? Do these necessarily sound similar?

  

**Methods**

We intend to build a quite complex model in a limited amount of time, with limited theoretical prerequisites in the field so we will use existent results as much as possible, mainly from Simoncelli’s publications, for the building of the model. Once the first samples are spawned by our model we will set up listening sessions and see which of our goals might be feasible considering the quality of our model and the amount of time we have. A Matlab coding framework is available on Simoncelli’s website, however only for pictures. As a starting point, we intend to find inspiration in this code and get a better theoretical understanding of basic psychoacoustics to get an overview of the kind of values that are computed by our auditory cortex on the sensory input.

**Literature**
J. H. McDermott, E. P. Simoncelli. "Sound Texture Perception via Statistics of the Auditory Periphery : Evidence from Sound Synthesis", Neuron. 71(5):926-40, September 2011.

J. Portilla, E. P. Simoncelli. "A Parametric Texture Model based on Joint Statistics of Complex Wavelet Coefficients", Int'l Journal of Computer Vision. 40(1):49-71, October 2000.


 A. Kell, J. H. McDermott. "Computational similarities between visual and auditory cortex studied with convolutional neural networks, fMRI, and electrophysiology", Journal of Vision, 15(12):1093, September 2015


