
### 1. Methodology

<p align="center"> 
<img width="615" alt="Screenshot 2021-12-25 at 1 23 18 PM" src="https://user-images.githubusercontent.com/71596140/147380330-45e13bc3-d592-453d-9031-acb3e6e5f647.png"> 
</p>
<p align="center"> Figure 1. DFD Diagram </p>


### 2. Description 
#### Project Perspective:
1. There is two-way communication between different clients and servers. Users can use this messaging application for group discussion via a group Room name. It allows users to find other logged-in users in that room. <br />
2. No need for an email address: Existing system requires a user to go through a login system which is overwhelming sometimes for short interactions or for those who are not so good with technology; whereas in the proposed system user only need a room name and a user name which will be displayed as its name in conversation. This system is helpful for those in schools, colleges, small companies, etc. <br />
3. Live location: Live location provided through Geolocation API defines a high-level interface to location information associated only with the device hosting the implementation. <br />
4. Data transfer: Users can share a certain amount of data within the room as per the free tier with a feature of destroying data transfer after closing of messaging space. Moreover, not all messages are meant to live forever, or at least that's the idea behind Vanish Mode, which lets you send temporary, self-destructing messages. <br />

#### Constraints:
1. The application supports only limited data transfer. <br />
2. The profanity filter as of now works only on English text. <br />
3. The system needs to be permanently connected to the internet. <br />
4. Limited users are allowed on the free server as of now. <br />


#### Product Functions:
1. There is two-way communication between different clients and servers. <br />
2. This Messaging application can be used for group discussion with profanity filter, Real-time location sharing, Embedded Media player. <br />
3. It allows users to find other logged-in users. <br />

#### Assumption and dependencies:
1. There should be LAN or internet connection. <br />
2. Clients should know each other. <br />
3. There can be multiple clients. <br />
4. The user has accepted all the permissions required to use the app. <br />
5. Location services may be required. <br />
6. The system must provide a capacity for parallel operation, period accessible, and system design should not introduce scalability issues about the number of surface computers, tablets, or mobile displays connected at any one time. <br />
7. The central database server and backup database servers should be updated regularly. This updating and replication of data from the main database server to the backup database server can introduce additional latency in the working of the system.

### 3. Input/Output :-

<br />
<p align="center"> 
 <img width="664" alt="Screenshot 2021-12-25 at 1 30 00 PM" src="https://user-images.githubusercontent.com/71596140/147380416-88a56e98-a390-46f0-8ee7-e7008948649c.png"> 
</p>

### 4. Live Link

Link: https://ourooms.onrender.com

Please wait 10-15 seconds after opening the app link

### 5. Screenshot of the Interface:
![WhatsApp Image 2021-12-06 at 8 27 27 PM](https://user-images.githubusercontent.com/71596140/147381377-f8f4249b-0f28-4c24-af0a-16f7bc59ec8e.jpeg)
<p align="center"> Figure 2. Login Page </p>
<br />

![WhatsApp Image 2021-12-06 at 8 50 45 PM](https://user-images.githubusercontent.com/71596140/147381354-095a8944-96d9-419b-9891-3488a5e2c1cb.jpeg)
<p align="center"> Figure 3. User 1(Shubham) has created the room as an admin and User 2 (Gautam) has joined it. </p>
<br />

![WhatsApp Image 2021-12-06 at 8 29 28 PM](https://user-images.githubusercontent.com/71596140/147381407-b6b0cf24-8da9-467f-b379-5bf9ee5147c2.jpeg)
<br />

![WhatsApp Image 2021-12-06 at 8 29 47 PM](https://user-images.githubusercontent.com/71596140/147381413-9c14418c-0bfe-480e-8596-27f95969c263.jpeg)
<p align="center"> Figure 4. User 1 sends messages and locations and while receiving messages simultaneously. </p>
<br />

<p align="center"> 
<img width="721" alt="Screenshot 2021-12-25 at 1 43 07 PM" src="https://user-images.githubusercontent.com/71596140/147380661-d4c48205-376a-4e84-94f8-fa6efc00fe89.png">
</p>
<p align="center"> Figure 5. Illustrating the working of Profanity API by censoring foul words. </p>
<br />

![WhatsApp Image 2021-12-06 at 8 33 07 PM](https://user-images.githubusercontent.com/71596140/147381447-dd10b24c-1af6-492d-afb6-e1f4437eed08.jpeg)
<br />

![WhatsApp Image 2021-12-06 at 8 33 39 PM](https://user-images.githubusercontent.com/71596140/147381452-50b22684-1a83-48ea-b045-6b035625833a.jpeg)
<p align="center"> Figure 6. Media playing. </p>
<br />

![WhatsApp Image 2021-12-06 at 8 52 47 PM](https://user-images.githubusercontent.com/71596140/147381468-81550fa2-3308-4b5d-bdde-ba57080772a6.jpeg)
<br />
![WhatsApp Image 2021-12-06 at 8 53 07 PM](https://user-images.githubusercontent.com/71596140/147381471-f35d362e-63a4-4626-ace9-f84e78a11bd2.jpeg)
<p align="center"> Figure 7. File Sharing Functionality. </p>

### Mobile View:
![WhatsApp Image 2021-12-06 at 8 35 14 PM](https://user-images.githubusercontent.com/71596140/147381286-c61ee024-097a-4b25-ae30-d8e811e91075.jpeg)
<br />
<br />
![WhatsApp Image 2021-12-06 at 8 36 29 PM](https://user-images.githubusercontent.com/71596140/147381307-01b76ca1-09b7-4764-99ee-f0f6f898327e.jpeg)
<br />
<br />
![WhatsApp Image 2021-12-06 at 8 35 54 PM](https://user-images.githubusercontent.com/71596140/147381310-6c5f6de4-19d6-458b-bf3c-68a25cb30006.jpeg)

 
