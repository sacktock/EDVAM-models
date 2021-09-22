# EDVAM: models
This project was completed as part of my summer research job at the "School of Engineering and Computing Sciences, Durham University" in the summer of 2021. I was tasked with leading my own research on 3D visual attention prediction in virual reality (VR) worlds. I implemented different recurrent neural network (RNN) architectures and trained them to model visual attention using the EDVAM dataset.

## About
This research follows on from the previous work conducted by the authors of the EDVAM dataset. Please look at their [[GitHub]](https://github.com/YunzhanZHOU/EDVAM) and refer to their most recent [[Paper]](http://www.jzus.zju.edu.cn/article.php?doi=10.1631/FITEE.2000318) for details about the data collection and format. 

## Files
- **LSTM_classifier.ipynb** a reimplementation of the predictive model outlined in the [[Paper]](http://www.jzus.zju.edu.cn/article.php?doi=10.1631/FITEE.2000318) mentioned above.
- **LSTM_seq_pred.ipynb** a simple RNN regression model that predicts the user's point of gaze data and camera configurtion data from a history of past data.
- **RNN_seq2seq.ipynb** a sequence to sequence RNN regression model that predicts future trajectories of user point of gaze data and camera configurtion data from a history of past data.
- **RNN_GAN_seq2seq.ipynb** a similar sequence to sequence RNN regression model trained with "Professor Forcing" - a training scheme for RNN based on the GAN framework.
- **report.pdf** a report paper to accompany the project.

## Experiments and Results
Please refer to the jupyter notebooks and the accompanying report for an overiview of the experiments and results conducted for this project.

## Misc
If you would like to collaborate on this project and/or want access to the trained models mentioned in the paper then please contact me using my personal email found below.

alex.w.goodall@gmail.com
