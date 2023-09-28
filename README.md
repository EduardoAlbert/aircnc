<h1 align="center">
    <img alt="Aircnc" title="#Aircnc" src=".github/logo.png" width="250px" />
</h1>

![License](https://img.shields.io/github/license/EduardoAlbert/aircnc)
![Stars](https://img.shields.io/github/stars/EduardoAlbert/aircnc)
![Forks](https://img.shields.io/github/forks/EduardoAlbert/aircnc)
![Issues](https://img.shields.io/github/issues/EduardoAlbert/aircnc)

<p align="center">
  <img alt="Frontend" src=".github/aircnc.png" width="100%">
</p>

Aircnc (Code and coffe) is a fullstack project developed during Rocketseat's OmniStack Week. It connects companies offering workspace "Spots" with developers seeking a place to collaborate, exchange ideas, and work together for a period. Using Socket.io, it provides real-time communication, facilitating seamless connections between businesses and developers. In essence, Aircnc fosters collaboration and knowledge exchange between companies and developers.

Watch a demo video of the Website version [here](https://www.youtube.com/watch?v=BRnMj6IhA1U).

Watch a demo video of the Mobile version [here](https://www.youtube.com/watch?v=WUHr7949SWA).

Watch a demo video of the Real-time in action [here](https://www.youtube.com/watch?v=NbiohSUGJAg).

### Key Challenges and Features

-   [x] **Space Sharing**: Aircnc facilitates the connection between companies willing to share their workspaces (spots) and developers seeking inspiring environments to exchange ideas, get to know company culture, and work temporarily.

-   [x] **Promotion and Booking**: Companies can promote their spaces for free or offer them for rent, giving developers flexibility in their choice.

-   [x] **Company Space Registration**: A dedicated module allows companies to easily register and provide details about their available spaces.

-   [x] **Developer Space Reservation**: Interested developers can browse and book available spaces to suit their needs.

## Technology Stack

This project was developed using the following technologies:

### Website

-   **ReactJS**: Providing a dynamic and interactive user interface.
-   **Socket.io**: Enabling real-time communication and updates.
-   **Axios**: Handling HTTP requests efficiently.
-   [Check package.json](frontend/package.json)

### Mobile

-   **React Native**: Creating a mobile app for easy space access.
-   **Expo**: Simplifying mobile app development and testing.
-   **Socket.io**: Enabling real-time features on mobile.
-   **Axios**: Ensuring seamless mobile-backend communication.
-   [Check package.json](mobile/package.json)

### Server

-   **Node.js**: Providing a robust and scalable backend.
-   **Express**: Facilitating API development and routing.
-   **Socket.io**: Enabling real-time updates and notifications.
-   **MongoDB**: A powerful NoSQL database for data storage and management.
-   **Mongoose**: Simplifying MongoDB interactions.
-   **Multer**: Handling file uploads seamlessly.
-   **Dotenv**: Managing environment variables effortlessly.
-   [Check package.json](backend/package.json)

## How to run

### Requirements

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- [Yarn](https://yarnpkg.com/)
- [Expo](https://expo.io/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/EduardoAlbert/aircnc.git && cd aircnc
```

**Install dependencies**

```bash
$ yarn
```

**Follow the steps below**

### Backend

```bash
# Edit 'packages/server/src/server.js' and change URL_CONNECTION_MONGO
# to your MongoDB URL

# To finish, run the api service
$ yarn server dev

# Well done, project is started!
```

### Web

_Obs.: Before to continue, be sure to have the API running_

```bash
# Be sure the file 'packages/web/src/services/api.js'
# have the IP to your API

# Start the client
$ yarn web start
```

### Mobile

_Obs.: Before to continue, be sure to have the API running_

```bash
# Be sure the file 'packages/mobile/src/services/api.js'
# have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn mobile start
```

## Contribution

I would be delighted to receive your contributions to enhance the Aircnc. Feel free to open issues or submit pull requests with improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
