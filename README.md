# Hate Speech Detection on Vietnam Social Media Text
**Hate speech** on social media refers to expressions that insult or threaten individuals or groups based on characteristics such as race, ethnicity, religion, gender, or other characteristics. It can manifest in many forms, including written text, images, or videos, and is often associated with inciting violence, putting individuals or organizations in a negative or even life-threatening situation.
# Dataset
We surveyed and collected comments from users from many fanpages and posts on the Vietnamese Facebook social networking platform related to different topics such as politics, entertainment games, football, celebrities, etc. We selected posts with high negative interactions. Using the Selenium library to automatically collect, then synthesize and survey the model, build a labeling guildline

View dataset [here](https://www.kaggle.com/datasets/cthng123/hate-speech-detection-vietnamese)
# Experimental approach
In the data preprocessing, we use methods like Remove URLs; Filter emojis; Normalize teencodes, abbreviations; Tokenize Vietnamese text, etc.

Finally we train the dataset on 4 classification models with different architectures: LR, SVM, BiLSTM, VisoBERT. achieve the expected results.
