# School_District_Analysis
For this project we needed to analyze data for an entire school district to determine:
1. Scores per grade in reading and math 
2. Scores based on school size 
3. Scores based on funding
4. Scores based on school type
5. Filter out data from misleading test scores

##Resources 
-Data Source: school district analysis csv. 
-Programs needed: Python 3.7, Anaconda, and Jupyter notebook

##Results:
  For this analysis we first found the data for all schools based on our original csv files. After learning of some potential dishonesty from the 9th grade class of Thomas High School we replaced their scores with a NaN and ran the analysis again. The image below is a new representation of the district after replacing the misleading scores with NaN.!{![school district sum](https://user-images.githubusercontent.com/89491163/136733891-d93f5de9-bbbf-4b58-b6f0-dc7ee49b0e7f.png)}

The changes we see in the district from this second analysis are  
The over passing percentage for the district dropped to 64.9%
The over passing percentage of Thomas High School dropped to 65%
After replacing the scores with NaN Thomas High School is no longer a top school in the district 

##Summary 
Due to academic dishonesty and the inability to determine which individuals were providing inaccurate scores the entire 9the grade class from Thomas High School will not be represented in the data. A full set of data would provide a clearer analysis of the district as a whole but we must remove their scores from the data. After replacing all of the 9th grade scores with NaN we saw a significant decrease in passing percentages for Thomas High School as a whole. The district score also suffered from this and saw a decrease in overall passing. While charter schools still have a high passing percentage because of the removal the overall passing percentage also decreased for charter schools.
