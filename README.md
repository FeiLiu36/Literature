# [Title]

Markdown

html

图床

## Introduction

To tackle the instability of the training procedure...



These methods can be divided into two categories:

- ...



## Bibliography

[CR-GAN](#CR-GAN)



---

### CR-GAN

[Consistency regularization for generative adversarial networks](https://arxiv.org/pdf/1910.12027.pdf)

**[`ICLR 2020`]**	**(`Google`)**	**[[Code](https://github.com/NVlabs/stylegan)]**

**[`Tero Karras`, `Samuli Laine`, `Timo Aila`]**

<details><summary>Click to expand</summary><p>


> **Summary**

They propose a training stabilizer based on **consistency regularization**. In particular, they **augment data** passing into the GAN discriminator and **penalize the sensitivity** of the discriminator to these augmentations.

> **Details**

$T(x)$ donates a stochastic data augmentation function. $D(x)$ donates the last layer before the activation function. The proposed regularization is given by:
$$
\min_{D} L_{c r} = \min_{D} \|D(x)-D(T(x))\|^{2}
$$
</p></details>

---

### CR-GAN

[Consistency regularization for generative adversarial networks](https://arxiv.org/pdf/1910.12027.pdf)

**[`ICLR 2020`]**	**(`Google`)**	**[[Code](https://github.com/NVlabs/stylegan)]**

**[`Tero Karras`, `Samuli Laine`, `Timo Aila`]**

<details><summary>Click to expand</summary><p>


> **Summary**

They propose a training stabilizer based on **consistency regularization**. In particular, they **augment data** passing into the GAN discriminator and **penalize the sensitivity** of the discriminator to these augmentations.

> **Details**

$T(x)$ donates a stochastic data augmentation function. $D(x)$ donates the last layer before the activation function. The proposed regularization is given by:
$$
\min_{D} L_{c r} = \min_{D} \|D(x)-D(T(x))\|^{2}
$$
</p></details>

---



$\theta$

$$
\theta
$$



### Equation

Latex
$$
\operatorname{argmin}_{\theta} \mathcal{L}(\theta)=\mathbb{E}_{\mathbf{z}, \mathbf{y}, \alpha}\left[\left(A\left(G\left(T_{\theta}(\mathbf{z}, \alpha), \mathbf{y}\right)\right)-(A(G(\mathbf{z}, \mathbf{y}))+\alpha)\right)^{2}\right]
$$
image

<div align=center><img src="https://raw.githubusercontent.com/yzy1996/Image-Hosting/master/20201119214216.svg"/></div>



### Image

<div align=center><img width="300" src="https://raw.githubusercontent.com/yzy1996/Image-Hosting/master/20201119220419.png"/></div>



