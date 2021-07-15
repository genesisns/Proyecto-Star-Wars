# Star Wars Project - NLP

In this project three of the Star War's movie scripts were analyzed and processed using NLP. 
Firstly, a simple word frequency count was performed to see which the most relevant characters are.

![image](https://user-images.githubusercontent.com/44349963/125864120-65f4cb30-7a29-4081-ba86-46be4551c54a.png)

Then a word frequency count was performed, followed by stop word removal and tokenization to generate word clouds for two characters: Yoda and Vader.

![image](https://user-images.githubusercontent.com/44349963/125864344-13503ebf-4e61-4afb-890a-d71ae7e40b86.png)

Next, the whole dialogue was processed, dealing with upper and lower cases, lemmanization and tokenization all in one place. 
Also a count vectorizer was used to understand which words are common in the trilogy and thus, should carry less weight in the analysis.

![image](https://user-images.githubusercontent.com/44349963/125862433-b383ff40-fb2d-4f91-994f-5587ddd42c7f.png)

![image](https://user-images.githubusercontent.com/44349963/125862450-3b8b06df-0654-4601-b133-6b5dbed2c271.png)


Lastly, sentiment analysis using Vader was performed, in the processed dialogues with and without lemmanization, concluding that the difference is not great and that lemmanization
should thus not be used.

![image](https://user-images.githubusercontent.com/44349963/125862353-cac39627-a346-40a6-ad68-25b19d25fa61.png)

