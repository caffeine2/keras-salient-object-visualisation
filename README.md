# keras-salient-object-visualization
```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/bgGEonerPiw" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
```

Keras implementation of nvidia paper 'Explaining How a Deep Neural Network Trained with End-to-End Learning Steers a Car'.
The goal of the visualization is to explain what Donkey Car (https://github.com/wroscoe/donkey) learns and how it makes its decisions. The central idea in discerning the salient objects is finding parts of the image that correspond to
locations where the feature maps of CNN layers have the greatest activations.
