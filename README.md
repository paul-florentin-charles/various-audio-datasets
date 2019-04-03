## Notes datasets

They are built from NSynth dataset, which is available [here](https://magenta.tensorflow.org/datasets/nsynth).

I just filtered the test dataset to construct those.

The higher the index, the smaller the amount of samples.

## Impulse responses datasets

They are taken from [this](https://www.voxengo.com/impulses).

Except for the *huge* ir dataset, which is a free dataset you can get on Wilkinson Audio.

Likewise, the *big* ir dataset is EchoThief, located [here](http://www.echothief.com/downloads/).

## Training data 

Available in *npz* files at the root, they were made using [dereverbation-ml](https://gitgud.io/polochinoc/dereverberation-ml).

Each data file contains both data and labels.
