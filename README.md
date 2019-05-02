# Recurrence
This repository contains the corresponding python notebooks for my Blog <a target="_blank" rel="noopener" href="https://recurrence-reviewed.de/">recurrence-reviewed.de</a>.  
I am trying to address both people with a strong mathematical background but without prior experience in neural networks, as well as people with less experience in mathematics but already basic knowledge of neural networks.  
If you have ideas on how to improve or find errors as well as when you are missing out something please feel free to contact me.

## Installation
To run the python notebook you need a python installation with jupyterlab. To install the environment, using anaconda, you can use the environment.yml file provided here. This was created under Windows 10. You can create an environment on your machine by following the instructions provided in the <a target="_blank" rel="noopener" href="https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file">Anconda docs</a>.  
If this fails under Linux, you might have to remove some version numbers in the yml file. You can also create a new environment with numpy, matplotlib and jupyterlab.  
When you have installed your environment, activate it and switch to the folder where the downloadd notebooks are located with ```cd```. Start jupyterlab by running ```jupyter-lab``` and open the corresponding notebook.  
To provide an easy start for beginners, you can also <a target="_blank" rel="noopener" href="https://recurrence-reviewed.de/contact/">request an account</a> for my jupyter-lab server to try out the notebooks.

## 01 Introduction to Neuron Models
This notebook starts with the abstraction of a singel neuron, gives a basic introduction on how to model a neuron and continues with the mathematics behind feed-forward structures and a minimal python implementation. If you ever have programmed neuron layers or a whole network yourself, you can skip this chapter.

## 02 Leaky Integration
Here we introduce a leak-rate to model how much a neuron state depends on new inputs and how much it depends on previous activations. Thereby we recognise how leaky integration affects neuron dynamics and how we can use a leaky integrating neuron as low-pass filter.
