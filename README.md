# Accounting for the Sequential Nature of States to Learn Features for Reinforcement Learning ⏱🏃

**Nathan Michlo**, **Devon Jarvis**, **Richard Klein**, **Steven James**

> In this work, we investigate the properties of data that cause popular representation learning approaches to fail. In particular, we find that in environments where states do not significantly overlap, variational autoencoders (VAEs) fail to learn useful features. We demonstrate this failure in a simple gridworld domain, and then provide a solution in the form of metric learning. However, metric learning requires supervision in the form of a distance function, which is absent in reinforcement learning. To overcome this, we leverage the sequential nature of states in a replay buffer to approximate a distance metric and provide a weak supervision signal, under the assumption that temporally close states are also semantically similar. We modify a VAE with triplet loss and demonstrate that this approach is able to learn useful features for downstream tasks, without additional supervision, in environments where standard VAEs fail.

## Repo Overview

This repo contains additional resources such as the poster and paper

- [📜 Paper](https://github.com/nmichlo/rldm-2022-sequential-states/blob/main/sequential-states__rldm-2022__paper.pdf)
- [🖼 Poster](https://github.com/nmichlo/rldm-2022-sequential-states/blob/main/sequential-states__rldm-2022__poster.pdf)

For code, and related work, please see my [🧪 MSc. Research](https://github.com/nmichlo/msc-research)
- VAE frameworks and experiments are run using my [🧶 disent](https://github.com/nmichlo/disent) framework.
