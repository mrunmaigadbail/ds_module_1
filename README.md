# ds_module_1
Homework for Module 1 -Excel

Excel sheet CrowdfundingBook contains 1000 sample projects 

Crowdfunding sheet
1. We have applied conditional formatting to column (G) outcome based on its outcome successful, failed, live, canceled
2. After creating new column percent funded(F) we applied formula pledged/goal (E2/D2)
3. In percent funded we applied 3 color scale where it starts at 0 in dar shade of red, and transitoned to green at 100 and blue at 200
4. After creating new column average donation (I) we applied formula IFERROR(E2/H2,0)
5. Then we created new columns named Parent category (S) and Sub-Category (T). after using function Text to column in data menu we split category and sub-category (R column) into 2 columns separated by "/"
6. created new column Date Created Conversion(N) to convert launched_at(L) data into date format using formula (((L2/60)/60)/24)+DATE(1970,1,1)
7. created new column Date Ended Conversion(O) to convert deadline(M) data into date format using formula (((M2/60)/60)/24)+DATE(1970,1,1)

Sheet 1 contains pivot table and stacked column chart that analyse crowdfunding worksheet to count how mant campagins were sucessful, failed, canceled and live as per category
Sheet 2 contains pivot table and stacked column chart that analyse crowdfunding worksheet to count how mant campagins were sucessful, failed, canceled and live as per sub-category
Sheet 3 contains pivot table and stacked line with markers graph that analyse crowdfunding worksheet to count how mant campagins were sucessful, failed, canceled and live as per sub-category
Sheet 4 contains goal analysis where we counted how many suscessful, failed and canceled projects based on different goal ranges. Also it shows percentage of projects that were successful, failed, or canceled per goal range. we added line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.
Sheet 5 contains Statistical Analysis to evaluate the values for successful campaigns and unsuccessful campaigns:
o	The mean number of backers
o	The median number of backers
o	The minimum number of backers
o	The maximum number of backers
o	The variance of the number of backers
o	The standard deviation of the number of backers
