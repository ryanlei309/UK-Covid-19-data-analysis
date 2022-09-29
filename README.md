This is a uk covid 19 data analysis. One of my coursework in computer programming in data science module.

This project analyze the changes in cases and vacine proportion in each countries in the uk.

Fistly, I wrote a function to request the data from NHS API, then check the data type and missing values in each column.
Since every data is unique in the covid-19 data sets, I decided to delete all the rows with any missing data.
And create a rolling average column to present daily quantitative metrics because it is a better indicator than raw daily measures.

Afterwards, I plot the cumulateive positive cases in each area in the UK and cumulative death cases in the UK.


![image](https://user-images.githubusercontent.com/52303625/192925573-5f4e2dfe-a0b8-414f-989d-9bdb501a0ab7.png)


I plot the rolling average positive cases in each area in the UK as well.

![Screenshot 2022-09-29 at 10 37 33](https://user-images.githubusercontent.com/52303625/192926003-2f14a0cf-6508-4bed-82f0-c2fb8aa99ded.png)

Lastly, I plot the vaccination coverage changes in the UK.

![image](https://user-images.githubusercontent.com/52303625/192927084-21744b1f-1bb6-4fa9-8017-dee9c5458042.png)
