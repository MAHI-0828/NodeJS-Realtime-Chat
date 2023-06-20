# NodeJS Realtime Chat

This is a GitHub project for building a full-stack chat application using Node.js on the backend and React.js on the frontend. The application features real-time chat, support for group chat and one-on-one chat, as well as the ability to send images and files. It also includes authentication functionality and integration with ChatEngine.io for chat functionality.



## Getting Started

To set up the project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/MAHI-0828/NodeJS-Realtime-Chat`
2. Install the required dependencies:
   - For the backend: navigate to the `backend` directory and run `npm install`
   - For the frontend: navigate to the `frontend` directory and run `npm install`
3. Start the Node.js server: in the `backend` directory, run `npm start`
4. Start the React development server: in the `frontend` directory, run `npm start`
5. Access the application in your browser at `http://localhost:3000`

## Usage

- Upon accessing the application, you will be directed to an authentication page where you can sign up or log in with a username.
- After authentication, you will be redirected to the chat application where you can start chatting with other users.
- The chat supports both group chat and one-on-one chat.
- Messages are sent and received in real-time.
- You can also send images and files.
- The application includes read receipts to indicate message delivery status.

## Deployment

To deploy the application to a production environment, follow these steps:

1. Set up a Node.js server to host the backend code.
2. Build the frontend React application using `npm run build`.
3. Deploy the built files to a static file hosting service or a server that supports serving static files.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m "Add your message here"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Create a pull request describing your changes.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements
- Special thanks to the creators of ChatEngine.io for providing the chat functionality.