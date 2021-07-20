# talking-regressor

It's a repo for figuring out ways how to get automatic text summaries to Auto-ML models that perform regression (get compressed and factorized latent representation). Ideally it should be even able to answer questions on properties of that model.

I think it would be nice to have a tool that can take some statistical data from you, then it makes a regression that gets a probalistic model with disentangled latent representation (via Beta-TCVAE, simply Factor Analysis or even GAN - but I'm not aware of the state of Auto-ML for GANs). Then the desired "magic" part. First it asks you some questions on obtained disentangled representation. Then it would be able to write an automatic report on the nature of the probabilistic model and even answer questions on it.

At the moment my expertise in this area is limited to models implemented in the [jats-semi-supervised-pytorch](https://github.com/kiwi0fruit/jats-semi-supervised-pytorch) project. That's not enough for sure. So I would return to this problem sometimes and would write what I found relevant.

Language models like GPT2 *might* be useful but I wasn't able to find it joined with some separate structure representation (and after briefly looking at the transformer model I don't know if it's even possible)... I guess there is a long-long way to go (or things for me to google :).
