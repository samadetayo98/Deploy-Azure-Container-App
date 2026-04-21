# Configure PostgreSQL Database
Name: Adekanmbi, Samuel Adetayo

Step 1: Navigate to Azure Database for PostgreSQL flexible servers and Create resource

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/9c9301f5-bef1-4cd3-9dc0-6e528205bc8c" />

Step 2: Fill Server details and set workload type to 'Dev/Test'

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/87074918-5b49-4e22-84ea-03361f82f518" />

Step 3: Change the Compute + storage seetings to Burstable

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/1ef385d7-444a-44ae-a22f-e35dd2a42170" />

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/64e5639d-1fc6-4a32-8aab-d6cf33d03f26" />

Step 4: Select 'PostgreSQL authentication only' in the Authentication method

Step 5: Create your login details

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/5b749b81-c504-4717-a766-27b187f2a8f1" />

Step 6: Next to the networking section and Allow public access from any Azure service within Azure to this server

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/605c9be6-7540-4443-bd1b-67cffbf2c5ba" />

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/ee2093f9-c588-4b07-b7b3-1e53a1869381" />

Step 7: Security

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/1184f8cf-664b-412f-a9e2-4bff3a5a04f2" />

Step 8: Review and create

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/71a382fc-a91b-4680-afc7-b3bd82ab9a47" />

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/181dab4b-5398-4867-bc8d-5b71df957f04" />

Step 9: Go to resource, select settings and click on 'database'

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/e2eee272-d394-4029-b52e-b61d3874ec88" />

Step 10: Create a new database 'demodb'

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/a8765951-993d-405e-a755-7d46da6ed53c" />

Step 11: Click on connnect and change database to 'demodb'

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/e6f6c15c-efaf-4523-bc5a-899a42641f43" />

Step 12: Scroll down to Connect from browser or locally and copy the code

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/568791d8-d951-4556-a8bf-2f9563a8f401" />

Step 13: Click on the Cloud shell icon and type in 'psql --version'

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/b6abefbb-2f63-4cdf-8c69-ef462d50fad8" />

Step 14: Paste the code copied in step 12 and enter your password

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/057f92b8-a3f5-4e48-a660-95e86897ec78" />
