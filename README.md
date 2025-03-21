LAB 1 Overview 
 
-Add collaborators on Github + Clone Repository 

 
-Task 1 : - Rename “rename_directory”> “analyzed_data” 

                   -Delete “dummy”, “dummy-2”, “dummy-3.txt” 

                  -Move “satelite_temperature_data.csv” to “raw_data” directory 

-Task 2: -Create file “highest_temp.csv” 

                -Extract the top 10 highest temperatures from “satelite_temperature_data.csv” 

                -Save the extracted data to “highest_temp.csv” 
                -Choosing a country, extracting her entire data from “satelite_temperature_data.csv” and save the result in descending order of humidity (highest to lowest). 
                 -Collect the output from the above and save it to “humidity_data_$country_name.csv”($country_name: chosen country) 

 

                 Approach: 

1. Extracting the top 10 highest temperatures 
     command: cat satelite_temperature_data.csv | sort -t',' -k3 -nr | head –10 

2. Copy the output from 1. and save it into “highest_temp.csv” 
 
3. Copying the data of a chosen country (Rwanda) and save the result in descending order of humidity (highest to lowest).  
       Output: To extract data from the country of my choice, I’ll select Rwanda from the satelite_temperature_data.csv file, and sort it in descending order of humidity. Here's the extracted data: 

Country 

Month 

Temperature 

Humidity 

Rwanda 

May 

21.62 

89.98 

Rwanda 

June 

37.77 

77.56 

Rwanda 

August 

49.28 

43.97 

Rwanda 

May 

33.33 

38.8 

Rwanda 

June 

21.2 

66.71 

Rwanda 

May 

43.15 

72.97 

Rwanda 

May 

24.04 

70.14 

Rwanda 

August 

40.87 

43.98 

Rwanda 

July 

26.91 

43.96 

Rwanda 

May 

29.99 

20.95 

 

4. Create file “humidity_data_Rwanda.csv” in "analyzed_data"
