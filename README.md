# Speech Emotion Recognition System
Akash Pandey
## Project Overview

Through all the available senses humans can actually sense the emotional state of their communication partner. The emotional detection is natural for humans but it is very difficult task for computers; although they can easily understand content based information, accessing the depth behind content is difficult and that’s what speech emotion recognition (SER) sets out to do. It is a system through which various audio speech files are classified into different emotions such as happy, sad, anger and neutral by computer. SER can be used in areas such as the medical field or customer call centers. With this project I hope to look into applying this model into an app that individuals with ASD can use when speaking to others to help guide conversation and create/maintain healthy relationships with others who have deficits in understnding others emotions.

## Dataset
The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) Dataset from Kaggle contains 1440 audio files from 24 Actors vocalizing two lexically-matched statements. Emotions include angry, happy, sad, fearful, calm, neutral, disgust, and surprised. [Click for dataset](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)



## Conclusion
Using feature extraction methods by itself did not achieve a high accuracy score within my CNN model, but using data augmentation methods did improve the accuracy score to 53% however it was overfitting the data. This model needs to be improved upon before being applied towards making an app to detect emotion in real time. Fine tuning the VGG-16 architecture with image augmentation improved the overall model accuracy to 81%/

## Limitations
Limitations include not using feature selection to reduce the dimensionality of my augmented CNN which may have improved learning performance. Another limitation included using minimal data, the RAVDESS Dataset has only 1,440 files which may be why there was overfitting of the data. Additional datasets could have been utilized.

## Next Steps

Next steps for this project include building a front-end for user interaction, then work towards building an app to detect emotion. Afterwards, I would like to be able to build system that can recognize emotion in real time and then calculate degree of affection such as love, truthfulness, and friendship of the person you are talking to.




