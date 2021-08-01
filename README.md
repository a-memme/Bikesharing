# Bikesharing
[Link to Tableau Dashboard](https://public.tableau.com/app/profile/andrew8402/viz/NYCCitibikeChallenge_16224167080570/CitibikeUseage)

## Analysis Overview 
- Using tableau to visualize NYC Citibike useage data for the month of August 2019. 
- Data was briefly cleaned using Python, exported into a csv file, and then displayed using several tableau visualizations.

## Results
The following visualizations were used to create a story in tableau, reflecting a number of relationships in the data:

<img width="1000" alt="Citibike_useage" src="https://user-images.githubusercontent.com/79600550/120910892-a736c580-c650-11eb-9fae-a657f99ed8a9.png">

Here, overall citibike useage for the month of August is displayed. As mentioned in the text box above, overall useage tends to be most popular within two predominate time frames: 7am-9am and 4pm-7pm. 

<img width="1008" alt="heatmap_1" src="https://user-images.githubusercontent.com/79600550/120910960-0f85a700-c651-11eb-90ec-3486214da787.png">

Using a heatmap to reflect useage through each day of the week, the same time frames mentioned in the previous image are represented as most popular when considering weekdays. When considering weekends however, there is a more gradual increase of bike useage through a longer time frame (i.e 10am-7pm as mentioned above). It's also interesting to note that greatest citibike useage occurs within the 5/6pm timeframe, as represented in the previous graph. This is detectable by the darker red rectangles displayed on the heatmap. 

![Gender_dashboard](https://user-images.githubusercontent.com/79600550/120911058-15c85300-c652-11eb-81f7-d8bd15becaa9.png)

The above dashboard reflects citibike useage in relation to gender. The pie chart indicates that the greatest number of citibike users are male (65.28%), followed by females at 25.10%, and lastly by the unknown gender category at 9.62%. When filtering for gender through daily and weekly useage, the same relationship noted in both preceding graphs is displayed, showcasing popular useage times. The magnitude of this relationship is reflected in the heatmaps as a function of gender useage popularity - i.e this relationship is most pronounced in the male heatmap as males
are the most frequent users of citibike, followed by females as the second most frequent users, and finally, by the unknown gender category, where the time/useage relationship seems to align significantly less. This is easily detected based on the intensity of colour in each heatmap. 

![trip_duration](https://user-images.githubusercontent.com/79600550/120911205-3644dd00-c653-11eb-86b2-927b935b4f40.png)

The next graph visualized above features trip duration for each gender. Although an exponentially larger number of bikes are being used in the male category, all genders tend to follow a very similar relationship in regard to trip duration. That is, citibike trips are most popularily five to six minutes long across all gender types. Trips become less and less frequent as the time increases up to one hour. No trips are longer than one hour across all genders.

![usertype_useage](https://user-images.githubusercontent.com/79600550/120911294-4b6e3b80-c654-11eb-9cef-27f6f0662085.png)

The final visualization displays usertype popularity and weekly useage across gender categories with the addition of a usertype filter - i.e customers and subscribers. As represented in the above pie chart, subscribers are the most popular type of citibike user at 81.07%, while generic customers only make up 18.93%. As the data follows - subscribers in the male catgeory make up a very dense proprotion of people using citibike, and hence, are the most popular category of users. This is followed by subscribers in the female category. Interestingly enough, the unknown category is the only gender category that displays lower useage by subscriber vs. customer. 

## Summary
The above series of viualizations indicate a number of inferences about the data that appear quite clear. First, the citibike service in NYC is most popularly used amongst males, a finding that has shown to remain true even when isolating for several variables such as usertype, trip duration, hours of the day or days of the week. Interestingly, the length of citibike rides doesn't seem to differ across any of the gender categories. Second, citibike's subscriber feature shows to be very effective, as a significantly large proportion of citibike users are subscribers, which is integral across majority of gender types. Finally, peak morning and early evening hours of the week-day represent the best hours for business for nearly all types of users, while late morning to evening are most busy for weekends. 

Given the above analysis, the citibike data for August tells an interesting story about its users - who are most likely to use the service, when they use the service most - at what specific days and times - and generally, how they use the service overall. A couple of additional visualizations using the same data could be created to further understand the information at hand. 

First, trip duration could be visualized filtering for usertype to determine whether the relationship of trip length differs between customer and subsriber. From here, it would be interesting to add another gender filter. Our customer useage heatmap in the above analysis indicated an interesting contrast with unknown gender types and their relationship with usertype in comparison to the male and female categories - it would be interesting to see what role the unknown gender types play in trip duration vs usertype (See *Extra Visualization #1 - Trip Duration by Usertype* on the [Tableau Dashboard](https://public.tableau.com/app/profile/andrew8402/viz/NYCCitibikeChallenge_16224167080570/CitibikeUseage)).

Finally, to build onto the above trip duration visualization,  a geomap graph could be created displaying areas where the longest/shortest trips are taken by minute (as no trips seem to exceed the 1 hour time frame). Depending on our findings of the previous graph, a usertype filter could be added to this map to create an even deeper understanding of this relationship.
