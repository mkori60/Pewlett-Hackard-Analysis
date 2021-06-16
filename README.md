# Overview of the Analysis
The purpose of this project is to use SQL in order to help Pewlett Hackard visualize projected future retirement data. This project will help Pewlett Hackard understand who will be retiring in the next few years and how many employees will be retiring. The final analysis will also help Pewlett Hackard understand the number of employees retiring per title and identify employees who are eligible to participate in the mentorship program. 

## Results 
* The first step in the analysis was to create a list of all the employees likely to retire in the next few years based on birth date and title. However, the retirement_titles.csv file had duplicates which needed to be removed. 

<img width="462" alt="Screen Shot 2021-06-16 at 4 50 39 PM" src="https://user-images.githubusercontent.com/83051034/122304782-01dae780-cec3-11eb-958a-0c8d454bf598.png">

* The second step was to use the DISTINCT ON statement to remove any duplicates. Once that was completed, the analysis showed that there are 90,398 employees who are eligible for retirement in the next few years, as shown in the unique_titles.csv file. 

<img width="442" alt="Screen Shot 2021-06-16 at 4 51 04 PM" src="https://user-images.githubusercontent.com/83051034/122304803-0d2e1300-cec3-11eb-8a97-4be82ad36d4e.png">

* The next step in the analysis was to create a list that showed the total number of potential employees retiring based on their job title. Once completed, the analysis in the retiring_titles.csv file showed that the greatest number of potential retirees are either senior engineers or senior staff, while there are only 2 managers potentially retiring. 

<img width="280" alt="Screen Shot 2021-06-16 at 4 51 28 PM" src="https://user-images.githubusercontent.com/83051034/122304837-1c14c580-cec3-11eb-9d70-5e0a8d5e7697.png">

<img width="211" alt="Screen Shot 2021-06-16 at 4 52 56 PM" src="https://user-images.githubusercontent.com/83051034/122305000-5ed69d80-cec3-11eb-87c5-cd5504f24e7a.png">

* The last step in the analysis was to create a mentorship_eligibility.csv file that showed the number of employees who are eligible for the mentorship program based on their birth date and whether they still work at the company. In mentorship_eligibility.csv, the analysis shows that 1,549 employees will be eligible to participate in the mentorship program. 

<img width="454" alt="Screen Shot 2021-06-16 at 4 51 47 PM" src="https://user-images.githubusercontent.com/83051034/122304866-2767f100-cec3-11eb-85f6-764d0cdae570.png">

* Together, the analysis shows that Pewlett Hackard needs to focus their efforts primarily on hiring more than 20,000 senior engineers and staff. 

## Summary
As the "silver tsunami" arrives, Pewlett Hackard will need to fill 90,398 positions. The majority of these positions will be senior engineers and senior staff, followed by engineeers, staff, technique leader and assistant engineer. Only 2 managers will be retiring. While Pewlet Hackard must hire approximately 90,398 new employees, they only have 1549 to participate in the mentorship program. It is likely that there will not be enough mentors for all of the new employees, particularly with regards to senior engineers and senior staff. 

According to the additional mentorship_eligibility_by_title.csv file, there are only 300 senior engineers eligible for the mentorship program while Pewlett Hackard has a need to hire more than 20,000 new senior engineers. Additionally, there are only 409 senior staff eligible for the mentorship program while more than 20000 senior staff must be hired. 

<img width="368" alt="Screen Shot 2021-06-16 at 4 49 22 PM" src="https://user-images.githubusercontent.com/83051034/122304688-dbb54780-cec2-11eb-951e-748fd83c87c2.png">

<img width="202" alt="Screen Shot 2021-06-16 at 4 49 10 PM" src="https://user-images.githubusercontent.com/83051034/122304673-d6f09380-cec2-11eb-9871-66460a94f161.png">
