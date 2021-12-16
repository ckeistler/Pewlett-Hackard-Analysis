# Pewlett-Hackard-Analysis

## Overview of Analysis
Through the 7th module in the data analytics course, we were tasked with building SQL tables and quiries with pgAdmin.  With our base dataset, we were tasked with determining the number of retiring employees per title, and identifying employees who were eligible to participate in a mentorship program. 

## Results

![ChallengeStep11](https://user-images.githubusercontent.com/88443672/146458098-53ef4f1c-89d3-45ff-85e3-743a74ae3b66.png)


- In order to achieve the totals that the module picture indicates as accurate, we need to skip step 11 in deliverable 1 of the challenge.  Following the instructions and filtering to the to-dates equal to '9999-01-01', we find that there are 25,916 Senior Engineers that fall within the filters used to identify employess with retirement likely in the near future.  We have to exclude the "to-date" filter to get the result of 29,414 Senior Engineers that the picture in the challenge indicates as the correct result.
![selectcount](https://user-images.githubusercontent.com/88443672/146459008-417f9219-0a2d-411f-9b7b-3aa5de821d34.png)![SelectCountModule](https://user-images.githubusercontent.com/88443672/146459014-41a91bd5-7e75-407c-8735-a6927f890e59.png)

- In the results that the directions lead too, there are 72,458 employees that fall within the search parameters, versus the 90,398 that the module pictures as correct, by which you have to skip step 11.

- There are 1,547 employees that are identified as mentorship-eligible.

- Regardless of using step 11 or not, the results in both instances show ~50% of the employees identified as nearing retirement as an Engineer of some form.
  
## Summary
