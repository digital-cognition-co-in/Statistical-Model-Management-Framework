# Statistical-Model-Management-Framework
Statistical Model Management Framework - TensorFlow , Keras etc. 

### TensorFlow Serving - Source -- https://www.tensorflow.org/serving/architecture_overview

- Servables -- single shard of a lookup table to a single model to a tuple of inference models.

- Typical Servables -- a TensorFlow SavedModelBundle (tensorflow::Session)
