# THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY
This repository load, clean and visualize the data of the apps in the google play store and first 100 user reviews for each app.


## Dependencies

- Pandas
- Matplotlib
- Seaborn
- Plotly
- Numpy

## Dataset:
- [apps.csv](https://www.kaggle.com/yashhvyass/the-android-app-market-on-google-play?select=apps.csv)
- [user_reviews.csv](https://www.kaggle.com/yashhvyass/the-android-app-market-on-google-play?select=user_reviews.csv)

## Usage

```bash
$ python data_manipulation.py
```
In this bar graph we visualized that how many apps were present under each category 

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/Number%20of%20apps%20vs%20Categories.png) 

In this bar graph we visualized that what were trend of the rating. Were higher ratings given to apps or poor or lower ratings were given to the apps. We observed that average rating was 4.17 which means that mostly apps were highly rated

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/Rating%20Frequency%20vs%20Rating.png) 

In the hexgrid graph we visualized that small size apps were given higher rating as compared to apps who have a large size.

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/Rating%20vs%20Size.PNG)

In this point graph we observed that mostly free apps were rated high.

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/Rating%20vs%20Prize.PNG)

We visualized the prize range of apps within the categories.

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/App%20prices%20trend%20accross%20categories.PNG)

We visualized the prize range of apps within the categories but this time we ignored the junk apps.

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/App%20prices%20trend%20accross%20categories%20except%20junk%20files.PNG)

In this box plot we visualized that how many poeple uses free apps and how many uses paid apps.

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/number%20of%20downloads%20free%20vs%20paid.PNG)

## Conclusion
It can be easily deduced that people prefer free apps

![image](https://github.com/Usman-Ghani123/THE-ANDROID-APP-MARKET-ON-GOOGLE-PLAY/blob/main/plots/Sentiment%20Polarity%20Distribution.PNG)


