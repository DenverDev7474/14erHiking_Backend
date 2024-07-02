# 14erHiking React Native App Frontend
HikingBuddiesApp is a backend service designed to facilitate the organization and scheduling of group hikes, specifically focusing on 14er mountains. It provides a platform for hikers to create, join, and manage hikes, ensuring a seamless and enjoyable hiking experience.

## Features
- **User Authentication**: Secure login and registration functionality for hikers.
- **Hike Management**: Users can create, update, and delete hikes, including details like the mountain, route, event time, and available spots.
- **Mountain and Route Information**: Access detailed information about mountains and routes to plan your hike accordingly.
- **Attendee Management**: Hosts can manage attendees, including adding and removing hikers from hikes.
- **Weather Predictions(TBD)**: Get weather predictions for the day of the hike to plan accordingly.

### Prerequisites
- Node.js
- MongoDB


### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/HikingBuddiesApp.git
   ```
  
2. **Install NPM packages:**

```sh
npm install
```

3. **Create a .env file in the root directory and add the following:**
```
API_URL='/api/v1'
DATABASE_URL=mongodb://localhost:27017/hikingbuddies
SESSION_SECRET=your_secret_here
```



## API Endpoints
**Auth:** /auth - Authentication routes including login and register.
**Hikes:** /hikes - CRUD operations for hikes.
**Mountains:** /mountains - Retrieve information about mountains.
**Routes:** /routes - Retrieve information about hiking routes.
**Users:** /users - User profile management.


## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or find any bugs.

## License
This project is licensed under the MIT License - see the LICENSE file for details.