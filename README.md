# Human Reactions to Noisy MNIST Data
Here we provide our behavioral data from 64 human subjects who performed a digit discrimination task using noisy MNIST dataset. For more details, pleases refer to our paper [here](https://www.biorxiv.org/content/10.1101/2022.08.23.505015v1.abstract).

### Data description
- **difficulty**: image difficulty (categorical; difficult vs. easy)
- **SAT**: speed-accuracy trade-off. Instruction given to the subject to adjust responding policy (categorical; accuracy focus vs. speed focus)
- **image_index**: index of the image in experiment_images.mat file (an integer between 1-120)
- **subject**: subject index (an integer between 1-64)
- **stim**: stimulus (an integer between 1-8)
- **response**: subject’s response (an integer between 1-8)
- **confidence**: subjects’ reported confidence (an integer between 1-4)
- **correct**: response accuracy (binary; 1: correct, 0: wrong)
- **resp_rt**: response RT. Elapsed time between the stimulus appearance on screen and subject’s response (double)
- **repeat**: Whether the stimulus appears for the first time or second time (binary; 0: first appearance, 1: second appearance)
- **mnist_index**: index of the image in the mnist dataset (integer)

