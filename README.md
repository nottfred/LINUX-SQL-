Apply filters to SQL queries
Project description
My organization is working to make their system more secure. It is my job to ensure the system is safe, investigate all potential security issues, and update employee computers as needed. The following steps provide examples of how I used SQL with filters to perform security-related tasks.

Step-by-Step instructions

1. Retrieve after hours failed login attempts: There was a potential security incident that occurred after business hours (after 18:00).
   All after hours login attempts that failed need to be investigated.

2. Retrieve login attempts on specific dates: A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09
   or on the day before needs to be investigated.

3. Retrieve login attempts outside of Mexico: After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside 
   of Mexico. These login attempts should be investigated.


4. Retrieve employees in Marketing: My team wants to update the computers for certain employees in the Marketing department.
   To do this, I have to get information on which employee machines to update.

5. Retrieve employees in Finance or Sales: The machines for employees in the Finance and Sales departments also need to be updated.
   Since a different security update is needed, I have to get information on employees only from these two departments.

6. Retrieve all employees not in IT: My team needs to make one more security update on employees who are not in the Information Technology department. To make the update,
   I first have to get information on these employees.

7. Summary


   LINUX file permissions
Project description
The team working on research at my company needs to adjust the access rights, for files and folders in the projects folder. The current permissions don't match the required level of authorization. Verifying and modifying these permissions is essential, for maintaining the security of their system. I carried out the following actions to address this issue:

Step-by-Step instructions
1. Check file and directory details
   
2. Current file permissions
   
3. Describe the permissions string
   
4. Change file permissions: The organization determined that other shouldn't have write access to any of their files. To
   comply with this, I referred to the file permissions that I previously returned. I determined project_k.txt must have the write    access removed for other.
   
5. Change file permissions on a hidden file: The research team at my organization recently archived project_x.txt. They do not want
   anyone to have write access to this project, but the user and group should have read access.

6. Change directory permissions: My organization only wants the researcher2 user to have access to the drafts directory
   and its contents. This means that no one other than researcher2 should have execute permissions.

7. Summary



