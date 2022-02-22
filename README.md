# Surfs Up Analysis
 
## *Overview*

Ths project focused on the temperatures of Oahu in June and December using the hawaii.sqlite database. The first step was to retrieve all of the temperatures for the month of June. The code and results are shown in the image below. The data was from 2010 to 2017.



![image](https://user-images.githubusercontent.com/85581208/147119527-ccccf20f-6f76-4cc7-b126-d9c1d22ad276.png)


Once all data points were pulled from the database, they were converted to a dataframe. Pictured below.



![image](https://user-images.githubusercontent.com/85581208/147119896-6d5e0877-86fa-4515-a398-16d75dd83e62.png)



Lastly, the df.describe() function was used on the dataframe to get a statistical analysis of the temperatures in June. The image below shows the results.



![image](https://user-images.githubusercontent.com/85581208/147120229-63d82959-734a-4e27-876f-f380c480a80f.png)


The steps above were then repeated for the month of December. This was easily completed by changing the month from 6 to 12 in the first step of pulling all the data points. The code and results are shown below for December. The results ended in a list just like the June results.


![image](https://user-images.githubusercontent.com/85581208/147120493-ca75e8c3-4141-47f2-9de5-b7a1aa2fb3ec.png)

Next the data was converted to a dataframe and then a statistical analysis as performed on the dataframe. The next two images show the results of those.


![image](https://user-images.githubusercontent.com/85581208/147120912-295f08a4-e287-4301-9ff6-772756dd71bb.png)




![image](https://user-images.githubusercontent.com/85581208/147120832-d5915312-af2f-4b13-a496-476f73774aa2.png)




## *Results*

Differences observed between June and December temperatures:

-The mean temperature for June was 74 and for December it was 71. It is slightly cooler in December which makes the water a little colder for surfing but not much of a difference.  

-The minimum temperature in June was 64 and the minimum for December was 56.  

-The maximum temperatures were the closest. For June is was 85 and the max temperature in December was 83.  


## *Summary*

Overall there is not a big difference in the temperatures in June and December in Oahu. The main takeways are the mornings might be colder in December.  Wet suits might be a more popular item in the surf shop during that time.  It appears the max temperatures are about the same. It gets a little warmer in June but the max temps only had a two degree difference. The average temperatures show it does average slightly cooler in December versus June. Overall there is little difference an surfing should be possible in both months when looking at the statistical analysis of the temperatures. The standard deviations were both around 3.5 if rounded down and up. The variability for both months were about the same.

In further analysis, the precipitation data was pulled for both June and December turned into a dataframe and analyzed. Images of results shown below with statistical analysis of both months.



![image](https://user-images.githubusercontent.com/85581208/147123039-1603b6e2-5629-435a-bf29-d15becf6bd1a.png)




There was overall more rain in June than in December but the max was the highest in December.  The both had a minimum of zero showing there are days with no rain.  December had a higher mean of 0.21 inches verses 0.13 inches in June.  Ultimately there is not a big difference between June and December for precipitation.

















              
              

