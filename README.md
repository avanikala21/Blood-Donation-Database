Database Management and Database Design – DAMG 6210

Topic: Blood Donation and Requirement System 

Professor: Prof. Nicholas Brown 

Team Members: Dhruvi Bavaria (002767470), Avani Kala (002772623)

1.	Steps we followed for project:

    •	Created an initial ER diagram of the dataset we were aiming for.

    •	Searched for datasets for Blood-banks, Hospitals and Persons with blood type initially, as they are our primary tables containing solid information.

    •	Other tables had link of this table and we generated data for tables of donor, patient, requests, pre-exam and blood bags using random function.

    •	We cleaned the data that we scrapped and ran python script which creates table and inserts data from csv files.

    •	Data was reflected in our database, and we linked the foreign keys by altering the table and adding constraints. Created use cases and views.

    •	Implemented Normalization up to 3NF form and updated the python script to store the data in table as per new design of tables after normalization.

2.	Project Description: 

    The aim of developing the ‘Blood Donation and Requirement System’ database is to:

    • Keep track of donors, patients and quantity of blood type in blood banks. 

    • Hospitals and individual to keep track of their blood requests and in case of any emergency they can contact respective blood banks to check the availability. 

    • Blood banks can check the eligibility of person if they can donate the blood or not.

3.	ER Diagram:

![image](https://user-images.githubusercontent.com/113712334/233174968-7ccc0a42-99b3-4167-876a-d568feb305a3.png)

4.	Use cases and views:
     Case 1: Hospital wants to request A+ blood from all blood-banks that have it.
      ![image](https://user-images.githubusercontent.com/113712334/233175659-27a4aecd-8430-4eee-a528-d8342eb8f7af.png)

     Case 2:  'Callahan Eye Hospital' wants to check its blood request status
      ![image](https://user-images.githubusercontent.com/113712334/233175731-eab1985c-b9b9-4219-b5ee-10091a58d198.png)

     Case 3: Doctor wants to know pre-exam status of a particular person
      ![image](https://user-images.githubusercontent.com/113712334/233175778-35f208f1-7999-47af-bbf3-2512be0e2f8c.png)

     Case 4: Blood-Bank wants to know if there is any person who is a donor as well as patient.
      ![image](https://user-images.githubusercontent.com/113712334/233175816-a1d521af-824a-47f7-8ee7-9549320e1a65.png)

     Case 5: What is quantity of O+ blood type at different banks
      ![image](https://user-images.githubusercontent.com/113712334/233175873-e8870e03-0f25-4d92-8cd4-b08ed23abdce.png)
