# LymeDiseaseProject

This project is created during my Data Science class (DS 202) in Iowa State University. The original repo for this project can be seen here: https://github.com/BinayaS/DS-202-Final-Project. The presentation for this project can be seen here: https://iastate.box.com/s/c74qtrj3brihtiwvfu533p2ypa3824s1

The project is called "The Relationship Between Lyme Disease, Temperature, and Precipitation". Specifically, this project focuses on the history of the lyme disease from 1992-2011 that has been plaguing the United States for a while. Lyme disease is the most common vector-borne disease in the United States.

This project explores the relationship between the cumulative outbreak of the disease with regards to the temperature and precipitation of different areas across the United States. This is because lyme disease originated from a deer tick that is transferred through different mammals which causes flu-like symptoms as well as rashes.

This project is created using R, with emphasis on combining different types of data to map locations and cumulative outbreaks. Specifically, I did the mapping of the cumulative outbreaks of each counties in the United States to find the pattern of where the outbreak is the most common, using datasets of US counties' latitude and longitude. I then use left_join() to combine with our cleaned datasets of cumulative Lyme Disease from 1992-2011. I filtered the states with the more than 100 cases, and then I use ggplot() to plot a map of the United States with the filtered states highlighted in red.

Our team concluded that the states with temperatures around 60 degree and high level of precipitation tend to have more cases of lyme disease. Lyme Disease are more prevalent in Northeast states.

The final analysis of our project is documented in the file Final_Project_Report.Rmd
