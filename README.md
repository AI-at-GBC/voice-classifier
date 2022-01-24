# Voice Classification
## _Recognizing Speakers Using Machine Learning_
This repository contains code that can be used to create a sample dataset of speakers from audio clips of them speaking, and then train a model to classify new samples of their audio using two different methods, chosen for the purpose of experimentation. One method runs recognition using a Residual Neural Network (RNN), while the other runs image recognition on spectrograms of the speaker's audio clips.

While there are a number of existing example datasets for speaker recognition such as the popular [16000_pcm_speeches](https://www.kaggle.com/kongaevans/speaker-recognition-dataset) dataset, we wanted to see if we could create a classifier on our own voices. Therefore, this repository contains code (see 01_Spectrogram_Creation.ipynb) that can be used to take an example of your voice and make it useable by our speaker recognition algorithms.

Together, the code in this repository will allow users to provide new pieces of speaker data, and build a model to classify examples of that speaker talking.

Created for Advanced Mathematical Concepts for Machine Learning at George Brown College.

## Contributing
To submit changes to this repo, please do the following steps:
- `git checkout main`
- `git pull main`
- `git checkout -b <your_branch_name>` (create a branch name based on the changes you want to make)
- Make your changes
- Before committing your file, please reset your runtime to get rid of the runtime numbers (IE the numbers between the square brackets beside each cell). The option should be under runtime -> restart runtime, or something like that.
- Save your file - both the .ipynb and the .py
- `git add .`
- `git commit -m "Your commit message here"` - please write a short but descriptive message!
- `git push origin <your_branch_name>`
- Open a Pull Request (PR) in Github, attempting to merge your branch into main, and request reviews from the group
- When you have approvals, merge your pull request

## Authors
- [Daniel Siegel](https://github.com/danielmaxsiegel) - 101367445
- [Michael McAllister](https://github.com/michaeldavidmcallister) - 101359469
- [Hom Kandel](https://github.com/homnath008) - 101385341
- [Eduardo Bastos de Moraes](https://github.com/eduardomoraes) - 101345799
- [Juan Clackworthy](https://github.com/juanlukeclackworthy) - 101372229
