Recommender Systems

Recommender systems work on algorithms and principles that help to understand people's prefereneces and then predict other interests they may have that a business can recommend.

The data in this repository is from movie ratings. We use this data to understand users' movie interests and recommend other movies the users may like.

This repository contains four notebooks:
1. [DataPreparation](https://github.com/ItunuoluwaOlowoye/RecommenderSystems/blob/main/DataPreparation.ipynb): Here, the different splitting strategies are employed to split the data into train and test sets.
2. [SarRecommendation](https://github.com/ItunuoluwaOlowoye/RecommenderSystems/blob/main/SarRecommendation.ipynb): Here, the SAR algorithm is used to build recommendation engines
3. [LightGbmRecommendation](https://github.com/ItunuoluwaOlowoye/RecommenderSystems/blob/main/LightGbmRecommendation.ipynb): Here, the lightGbm algorithm is used to build the recommender
4. [BatchArchitecture](https://github.com/ItunuoluwaOlowoye/RecommenderSystems/blob/main/BatchArchitecture.ipynb): This notebook explains how to use batch architecture to deploy a recommender system

The model was deployed with Streamlit and can be accessed [here](https://recommender-systems-itee.streamlit.app/). If the app has gone to sleep, simply wake it up.