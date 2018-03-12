# Presentation Materials for Workshop

# Part 1: Introducing R and the Tidyverse

Goal: Improve your research workflow - be more productive (and reproductive).

## Hello, R

## (Data) Science is a Verb

### Wrangle

### Rectangle

### Chronicle

## Learn More About R

# Part 2: RStudio + Keras + Tensorflow

Goal: Integrate deep learning into a research workflow that is productive and reproductive.

## Why R?

## Hello, Keras

Recognize hand-written single-digit numbers using the example MNIST training set. This comes from J.J. Allaire's example, Auggy-mented with additional context from questions I had as I was learning the material. Even if you are totally new to this, the concepts will be presented in context.

## Feeling Validated

How do we validate that our model is performing the way we want? How can we communicate our assumptions in a clear way to others?

## The Plots Thicken (TFRuns)

What happened at each layer during the training? How can I see what my model "sees"? What parameters had the most impact? Again, how do I share my story with others?

## Tidy and Share (TFDatasets + TFEstimators)

Deep learning adds an additional data Mangling step to the Wrangling and Rectangling that already take up much of our time. The TFDatasets library offers some tools to make it hurt less. Many deep learning problems already have a documented method, so why spend a lot of time on configuration? The TFEstimators library provides implementations of many different model types which is especially useful while you're getting started.

## Learn More about R + Tensorflow

We only touched on very high-level concepts because our goal was to provide an initial exposure to the wild world of deep learning. What you focus on next will depend on your background and area of research!

Recommended Reading:

 * Deep Learning with R
 
RStudio's Tensorflow and Keras Documentation:

 * https://tensorflow.rstudio.com/
 
# Appendix
 
## Download R

 * https://www.r-project.org/

## Install RStudio

 * https://www.rstudio.com/products/rstudio/download/#download

Alternatives to local installs on your Laptop:

Hosted RStudio IDE through CognitiveClass.ai 
 * Available here: https://labs.cognitiveclass.ai/tools/rstudio-ide/ 
 
## Set up RStudio + Keras

 * https://keras.rstudio.com/

This is dependent on how you have Python set up.
 * Use system Python to start, custom Python and Conda setups will require some troubleshooting
 * install the keras package through RStudio
 * run "install_keras"
 
## Set up RStudio + Tensorflow

This should already be set up if you set up Keras, but if you run into any problems with the setup, this may be of help.
  
  * https://tensorflow.rstudio.com/tensorflow/articles/installation.html
  * Install the tensorflow packages through RStudio
  * run "install_tensorflow" if you did not run "install_keras" in the previous step already
