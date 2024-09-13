This is a basic Speech Based Disease Identification project. The project is broken down into different parts :
1. ASR : The speech is taken from user, and then transcribed. The transcriptions are then stored in a .txt file.
2. File Reading : The .txt file is read and contents stored in a variable.
3. Multiword Identification : The symptoms in the dataset are put together in a list so as to ease the task of tokenization.
4. Tokenization : The sentence/ user input is then tokenized using Transformers.
5. Disease Identification : The disease are identified with simple symptom matching and stuffs.

The dataset I used for disease and symptoms is taken from Kaggle : "Disease Symptom Prediction" dataset.
