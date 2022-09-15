# 1-	Split the audio file into small audio files depending on the type of the audio wave and we choose this time depending on the type of the wave after viewing and collect some information of the wave.

![image](https://user-images.githubusercontent.com/107008585/190523563-660e7d14-fb23-41ae-bf47-bf2e2c3e360f.png)

# 2-	After split the audio into small files we will read each file alone and run the two models Arabic model and English model to get the text from the wave.

![image](https://user-images.githubusercontent.com/107008585/190523621-bbe2ba89-a4cf-455e-ac5a-24b8c48ed3ea.png)

# 3-	We have two options now:
   # 1-	The first one and not effective is to choose the model that can detect more words from the audio file.
   # 2-	The second one and this is effective is to making language detection to the output text of the English or Arabic text if it is English using English model, else         use Arabic model.
# Now we have the mixed text in list just join the output of each audio by order to make the final output of this audio file.
# And then we ready to summarization.
# Libraries used in each step:
   # 1-	We use librosa and matplotlib to visualize the wave signal.
   # 2-	We use Speech Recognition library and choose the google model to get text from audio.
   # 3-	We use Spacy library to making text detection after download English dictionary.
   # 4-	We use Numpy library to make some mathematical operations.
   # 5-	We use Pandas library to save each audio file and the output text from it and also detect the audio files that the model fails to get text from it so we make a           report of all files using this library.
