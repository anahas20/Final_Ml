# Final Project - Propaganda


## Conceptual Description

The project explores the subject of propaganda, a tool/technique/method used by organizations,
states, or simply individuals to promote a specific information publicizing a particular perspective. The
project will take two dichotomy “Twitter” users, using a natural language processor to be able to classify
which “Tweet” belongs to which user.

Propaganda leads to misleading information. The intention is the ability to identify the probability
where these information originated from or who is more likely to produce that content. The project
explores the problem on a smaller scale between two opposing sides. Also, it implements the possibility
to explore this practice on a larger scale analyzing bigger entities like governments and organization, and
to be able to distinguish if particular pieces of information are produced a particular side to prevent
information fraud, deceit, or deception

## Project Description

The project takes two dichotomy “Twitter” users, using a natural language processor to be able to classify
which “Tweet” belongs to which user.


## Data

Individual Scale - The two users are **@JoeBiden** and **@realDonaldTrump**

Media Scale - **Far left Media** accounts **[@NewYorker ; @voxdotcom ; @nytopinion ; @Newsweek]** ; **Far Right Media** accounts **[@DailyMail ; @FoxNewsOpinion ; @NYPostOpinion ; @NRO]**





## Process
steps:

- 1. Use Python wrapper by Twitter (API) to mine tweets from the selected users
- 2. Convert output tweets into a Pandas Dataframe
- 3. Use TF-IDF Vectorizer  to analyze and weight n-grams of each tweet
- 4. Pre-process text with Textacy
- 5. Built model and train
- 6. Create a prediction function

## Modules

- 1. **Biden vs Trump** [Individual Scale] - Comparing two individual users
- 2. **Left vs Right** [Media Scale] - Creating two groups of four Media accounts. One is Far-Left, and the other is Far-Right
- 3. **TweetMiner** - TweetMiner function from Bhishan Poudel and Mike Roman
