## muP introduction

muP parametrization transfert is a simple idea : you want to optimize your deep learning hyperparameters (learning rate, batch size, initialization etc) on small model because it's computationally cheap and then use your best found parametrization on a bigger model to avoid spending compute budget on optimizing the big model. 

Those are the two main papers I will look at to implement the new parametrization : 

- https://arxiv.org/pdf/2203.03466 : Tensor Programs V: Tuning Large Neural Networks via Zero-Shot Hyperparameter Transfer

- https://arxiv.org/abs/2310.17813 : "A Spectral Condition for Feature Learning" instead of muP we simply a spectral normalization
