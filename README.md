# `gan-monet`

https://www.kaggle.com/competitions/gan-getting-started/overview

## Data and EDA

We want to make pretty Monet pictures with electricity. Here are some real ones:

![](./artifact/monet-mosaic.png)

### Exploring the data

![](./artifact/eda-1-img-size.png)

![](./artifact/eda-2-color-dist.png)

![](./artifact/eda-3-complexity.png)

## The Model

I decided on a DCGAN with the following structure.

![](./artifact/arch-discriminator.png)

![](./artifact/arch-generator.png)

## How did it go?

We aren't going to win any prizes. Mostly because this training takes 4 minutes per epoch on my computer.

Next time I'll buy a laptop with CUDA capability and train more than 10 epochs.

![](./artifact/monet-mosaic-generated.png)
