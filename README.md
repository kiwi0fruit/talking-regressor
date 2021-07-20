# talking-regressor

It's a repo for figuring out ways how to get automatic text summaries to Auto-ML models that perform regression (get compressed and factorized latent representation). Ideally it should be even able to answer questions on properties of that model.

I think it would be nice to have a tool that can take some statistical data from you, then it makes a regression that gets a probalistic model with disentangled latent representation (via Beta-TCVAE, simply Factor Analysis or even GAN - but I'm not aware of the state of Auto-ML for GANs). Then the desired "magic" part. First it asks you some questions on obtained disentangled representation. Then it would be able to write an automatic report on the nature of the probabilistic model and even answer questions on it.

At the moment my expertise in this area is limited to models implemented in the [jats-semi-supervised-pytorch](https://github.com/kiwi0fruit/jats-semi-supervised-pytorch) project. That's not enough for sure. So I would return to this problem sometimes and would write what I found relevant.

May be useful:

* [Study Shows Transformers Possess the Compositionality Power for Mathematical Reasoning](https://syncedreview.com/2021/05/26/deepmind-podracer-tpu-based-rl-frameworks-deliver-exceptional-performance-at-low-cost-27/)
* [Compositional Processing Emerges in Neural Networks Solving Math Problems](https://arxiv.org/abs/2105.08961)
* This may be useful as we are able to generate automatic math formulas from learned model. After all we know the math definition of the model from Auto-ML.
