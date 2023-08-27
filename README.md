# Music-Genre-Classification using KNN
We have used K-nearest neighbors algorithm because in various researches it has shown the best results for this problem. K-Nearest Neighbors is a popular machine learning algorithm for regression and classification. It makes predictions on data points based on their similarity measures i.e distance between them.

The first step for music genre classification project would be to extract features and components from the audio files. It includes identifying the linguistic content and discarding noise.

Mel Frequency Cepstral Coefficients:

These are state-of-the-art features used in automatic speech and speech recognition studies. There are a set of steps for generation of these features:

-Since the audio signals are constantly changing, first we divide these signals into smaller frames. Each frame is around 20-40 ms long

-Then we try to identify different frequencies present in each frame

-Now, separate linguistic frequencies from the noise

-To discard the noise, it then takes discrete cosine transform (DCT) of these frequencies. Using DCT we keep only a specific sequence of frequencies that have a high probability of information

About the dataset:

The GTZAN genre collection dataset was collected in 2000-2001. It consists of 1000 audio files each having 30 seconds duration. There are 10 classes ( 10 music genres) each containing 100 audio tracks. Each track is in .wav format. It contains audio files of 10 genres.

Initial Run Accuracy: 0.6923076923076923

Predicted input file as: rock
