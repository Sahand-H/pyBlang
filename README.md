# pyBlang

## Introduction

This package is an interface to Blang, (link)


## Installation


## Quick Guide

The package works by calling the Blang command line interface (CLI), for the time being, the blangSDK should be installed separately with the CLI setup properly via the instructions found here: 

That's the only requirement for the package to function.


### Installation



### Setting up a model

```python
import pyBlang as pb

model = pb.Model(name = modelName, project_path = projPath, post_process = 'NoPostProcessor')
```

The code above instantiates a model object, and the arguments listed are the only required arguments.

- `name`: name of the model within the .bl file.
- `project_path`: the path to the Blang project directory.
- `post_process`: `NoPostProcessor` by default, but can be set to `DefaultPostProcessor`.

### Running the model
Once a Model object has been set up, 