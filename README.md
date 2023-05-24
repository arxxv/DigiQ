# digiQ
[Devpost](https://devpost.com/software/digi-q)

Runner up at HackTheBronx hackathon organized by the Bronx Community, USA

DigiQ is a queue management application available as an Android app and web app, designed to simplify and streamline the process of joining and managing queues. The app provides users with a convenient way to create, manage, and join queues effortlessly. By leveraging the power of technology, DigiQ allows users to avoid physical waiting in queues by enabling their mobile devices to stand in line on their behalf.

Key Features:
1. Queue Creation: Users can easily create queues through the app, specifying relevant details such as queue name, description, location, and expected wait time.

2. Queue Management: The app provides comprehensive queue management capabilities. Queue creators can monitor the queue status, view the number of people in the queue, and make real-time updates to the queue information.

3. Queue Joining: Users can join queues using either the unique queue ID or a QR code generated at the time of queue creation. This eliminates the need for physical presence in the queue, allowing users to save time and avoid waiting in crowded areas.

4. User Authentication: DigiQ includes a robust user authentication system to ensure secure access and protect user information. Users can create accounts, log in, and authenticate themselves before joining or creating queues.

Technical Details:
- Backend API: The back-end API of DigiQ was built using Python programming language and the Flask framework. The API supports full CRUD (Create, Read, Update, Delete) functionality, enabling users to perform various operations on queues and user accounts.

- Database: The application utilizes CosmosDB, a NoSQL database provided by Microsoft Azure, to store and manage queue data, user information, and other relevant details. CosmosDB offers scalability, high availability, and low-latency access, ensuring a reliable and efficient storage solution for DigiQ.

- Hosting: DigiQ's API is hosted on Azure Web Services, providing a scalable and secure environment for the application. Azure Web Services ensures the availability and accessibility of the API, allowing users to interact with DigiQ seamlessly.

Overall, DigiQ revolutionizes the traditional queue management process by leveraging modern technology and automation. It offers a user-friendly interface, efficient queue management, and the convenience of joining queues remotely. Whether it's avoiding long lines at popular attractions, crowded venues, or busy service centers, DigiQ empowers users to save time and improve their overall queueing experience.

The [web-app](https://github.com/shubhamjain1922/digiQ) was built using React.js and the android-app was built using Flutter, by my friends
