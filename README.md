# models
Raw CNN &amp; FAM model generation

We need TensorFlow version 0.10+ to run.

Also you need Keras, which can be installed easily from pip.

It is important that .keras/keras.json, looks something like this:

```
{
    "image_dim_ordering": "th", 
    "epsilon": 1e-07, 
    "floatx": "float32", 
    "backend": "tensorflow"
}
```

# To generate documentation use:

doxygen models.dox

# Note

Please use the FAM model at the moment, I'm just tweaking the CNN model, as I need to implement 64 sample shifts.
