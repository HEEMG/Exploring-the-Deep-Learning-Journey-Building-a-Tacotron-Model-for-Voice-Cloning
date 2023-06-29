# Title: Exploring the Deep Learning Journey: Building a Tacotron Model for Voice Cloning

## Introduction:
In this blog post, we will dive into a fascinating deep learning  project that involves creating our own Tacotron model for voice cloning. By following a step-by-step process, we will collect data, process the dataset, train the model, and ultimately achieve our goal of synthesizing audio. Let's embark on this exciting journey!

## Step 1: Collecting Data
To start our project, we needed a dataset of Nepali script sentences. We wrote 500 sentences in Nepali script and recorded them as auto-isolated vocal tracks using Audacity. These tracks were saved as 22kHz mono WAV files. Each sentence was then split into separate audio files and transcribed, with the text files saved in the format "waves/name of audio file line." This meticulous data collection process is essential for training our Tacotron model accurately.

## Step 2: Processing the Dataset
In this step, we need to process our dataset for training. First, we navigate to the "wavs" folder and upload the WAV files that we want to include in our model. Then, we upload the corresponding text file into the "filelists" folder. This prepares our dataset for the subsequent model training phase.

## Step 3: Training the Model
Now comes the crucial part: training our Tacotron model. In this section, we set up the environment and initialize the necessary components for model training. By running specific cells, adjusting parameters if needed, and accessing the model link, we kickstart the training process. This phase requires patience and computational resources, as the model learns from the provided data to generate high-quality audio.

## Step 4: Synthesizing Audio
Once the model is trained, we can unleash its power to synthesize audio. Using Tacotron, we copy and paste the link to our model. Additionally, we utilize Waveglow as the vocoder, which converts the generated spectrogram into sound. Initializing both Tacotron and Waveglow models allows us to synthesize audio based on the given input text.

## Conclusion:
Congratulations! By following these steps, you have successfully embarked on a data science project that involved building your very own Tacotron model for voice cloning. Through diligent data collection, dataset processing, model training, and audio synthesis, you have gained valuable insights and hands-on experience in the exciting field of data science.

Remember, this project is just a starting point, and there are endless possibilities for exploration and further enhancements. As you continue your data science journey, keep experimenting, learning, and sharing your knowledge with the community. Happy data science adventures!