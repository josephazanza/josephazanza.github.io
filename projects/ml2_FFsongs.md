[<img src="../images/ml2_FFsongs_NN.png">](https://raw.githubusercontent.com/josephazanza/josephazanza.github.io/master/images/ml2_FFsongs_NN.png)

# Composing Final Fantasy Sound Tracks via Neural Networks

[Joseph Azanza](https://www.linkedin.com/in/josephazanza/) <br>
Asian Institute of Management

## Executive Summary
<p align='justify'>

This is a passion project driven primarily by my interest in the music of video games and the Final Fantasy franchise. The goal of this project is to apply my ML2 learnings and use neural networks to compose a Final Fantasy OST. The dataset I used are 100 handpicked MIDI files from Final Fantasy IV, Final Fantasy VII, and Final Fantasy X, representing three different eras of the franchise. The whole intuition of the project revolves around learning the sequences of notes and chords, predicting the next probable note or chord. The best network that I was able to train has 3 LSTMs + 2 sets of Batch Normalization-Dropout-Dense layers, with a validation accuracy of 74.89%. In terms of meeting the project goal, I was able to successfully generate OSTs using the trained network.

My key learnings on this project, both non-technical and technical ones, are summarized below:
</p>

|Key Learning|Expanded Description|
|:--:|:--:|
|Perfect is the enemy of good. |The AI generated song is not perfect, but I think the network and the output is good enough to stand on its own.|
|The advantage of domain knowledge. |Having more knowledge of music theory at my disposal can really enhance the output of the network further. At my current state, I am not sure how to include components such as different Note Durations, Rests, and other instruments, in the network training and song generating processes.|
|Importance of having fun and enjoying the process.| Doing this project felt similar to clearing the final dungeon of a game and I found that enjoying the process made work feel like play. Given the difficult term that we are in, I think it’s important to take a step back and enjoy what we can.|
|The importance of Batch Normalization layer. |This layer, when applied correctly, can dramatically increase training time while functioning as a regularization layer, hitting two birds with one stone.|
|The importance of understanding the different metrics. |My experiments lead me to choose between validation accuracy and validation loss, and if I did not have understanding of when is it applicable to choose one over the other, I probably would've beaten myself over and over in attempting to lower the validation loss to be near zero as possible. In reality though, I already have good working model that can generalize with a good accuracy.|
|Leveraging existing works and understanding and adapting them. |We don't have to start from scratch everytime. Understanding the work of others and leveraging these existing works (with proper citation), is also another important skill that every data scientist must have. Not only does it save time, but it also shows experience and maturity of learnings.|

<br><br>

<p align='justify'>
<b>Keywords:</b> music generation, LSTM, Final Fantasy
</p>

---

**Source code available at [ML2_indiv](https://github.com/josephazanza/ML2_indiv)**

---

## [Back to main page](https://josephazanza.github.io/)