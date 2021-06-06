# Bikesharing
## Analysis Overview 
Using tableau to visualize NYC Citibike useage data for the month of August 2019. The data was briefly cleaned using Python, exported into a csv file, and then visualized in tableau with the creation of a number of graphs.

## Results
The following visualizations were used to create a story in tableau, and reflect a number of relationships in the data:

<img width="1000" alt="Citibike_useage" src="https://user-images.githubusercontent.com/79600550/120910892-a736c580-c650-11eb-9fae-a657f99ed8a9.png">

Here, overall citibike useage for the month of August is displayed. As mentioned in the text box above, overall useage tends to be most popular within two predominate time frames: 7am-9am and 4pm-7pm. 

<img width="1008" alt="heatmap_1" src="https://user-images.githubusercontent.com/79600550/120910960-0f85a700-c651-11eb-90ec-3486214da787.png">

Using a heatmap to reflect useage through each day of the week, the same time frames mentioned in the previous image are represented as most popular when considering weekdays. When considering weekends however, there is a more gradual increase of bike useage through a longer time frame (i.e 10am-7pm as mentioned above). It's also interesting to note that greatest citibike useage is occuring within the 5/6pm timeframe, as represented in the previous image. This is detectable by the darker red rectangles displayed on the heatmap. 

![Gender_dashboard](https://user-images.githubusercontent.com/79600550/120911058-15c85300-c652-11eb-81f7-d8bd15becaa9.png)

The above dashboard reflects citibike useage in relation to gender. The Pie chart indicates that the greatest number of citibike users are male (65.28%), followed by females at 25.10%, and lastly by the unknown gender category at 9.62%. When filtering for gender through daily and weekly useage, the same relationship noted in both preceding graphs is displayed in congruegence with useage frequency in each gender - i.e the relationship is most pronounced in the male heatmap who are the most frequent users of citibike, followed by the female category, and finally, a very slight parallel in the unknown gender category. This is easily detected based on the intensity of colour in each heatmap. 

![trip_duration](https://user-images.githubusercontent.com/79600550/120911205-3644dd00-c653-11eb-86b2-927b935b4f40.png)

The next graph features trip duration for each gender. Although an exponentially larger number of bikes are being used in the male category, all genders tend to follow a very similar relationship in regard to trip duration. That is, the length of citibike trips are most popularily around 5 or 6 minutes across all gender categories, and taper off within the hour. No trips are longer than one hour across all gender categories.

![usertype_useage](https://user-images.githubusercontent.com/79600550/120911294-4b6e3b80-c654-11eb-9cef-27f6f0662085.png)

The final visualization displays weekly useage across gender categories, but also filters for usertype - i.e customer or subscriber. As indicated in the above text boxes, subscribers are the most popular type of citibike users at 81.07% while generic customers only make up 18.93%. As the data follows - subsribers in the male catgeory make up a very dense proprotion of people using citibike, and hence, are the most popular category of users. This is followed by subscribers in the female category. Interestingly enough however, the unknown category is the only gender category that displays lower useage by subscriber vs. customer. 

The above series of viualizations display a number of indications about the data that appear to be quite clear. First, the citibike service in NYC is most popularly used amongst males, a finding that has shown to remain true even when isolating for several variables such as usertype, trip duration, hours of the day or days of the week. Interestingly, the length of citibike rides doesn't seem to differ across any of the gender categories. Second, citibike's subscriber feature is effective across the majority of its users (with the exception of unknown gender types), as a very large proportion comes from this catgeory. Finally, peak morning and early evening hours of the week-day represent the best hours for business for nearly all types of users, while late morning to evening are most busy for weekends. 

Given the data, above visualizations and interpretations, 



