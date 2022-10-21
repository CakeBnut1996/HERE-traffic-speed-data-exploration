# HERE-traffic-speed-data-exploration

The data from HERE shares a similar structure with INRIX. It is also TMC-based. The time range of HERE data available are from July 2019 to August 2020. Total number of TMCs recorded is around 6300. The size of the data is 53 GB. The speed is in kilometers per hour, based on each TMC segment. Unlike INRIX, missing values are not observed in HERE because speeds are automatically filled. The summary page of the downloaded data is shown below. 

![image](https://user-images.githubusercontent.com/46463367/197094744-73d8f5fd-9032-4e7a-96f8-1bf95462d68b.png)

Figure. Summary information of HERE data. 

The main columns are
- Average speed (kph): The speed collected by HERE (kph).
- Free flow (kph): The free flow speed estimated by HERE. 
- Functional class: It reflects traffic speed and volume. This is similar to the column “FRCLevel” defined by INRIX.

1: a road with high volume, maximum speed traffic
2: a road with high volume, high speed traffic
3: a road with high volume traffic
4: a road with high volume traffic at moderate speeds between neighborhoods
5: a road whose volume and traffic flow are below the level of any other functional class

The distribution of the length of the TMC in miles is shown below. As can be indicated by the median and the tail of the distribution, the length of the TMC used in HERE is longer than that in INRIX.

![image](https://user-images.githubusercontent.com/46463367/197094798-e56fe548-34bf-498e-8c9e-0e93507f338b.png)
 
Figure. The distribution of the length (miles) of the TMC


