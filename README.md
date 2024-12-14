## About The Project

![Product Screenshot](https://picsum.photos/1920/1080)

This task management app was created to streamline the organization of projects and tasks, providing a collaborative platform inspired by tools like Trello and Jira. It allows users to create projects, manage tasks across multiple statuses, and collaborate in real-time with team members.

### Key Features

- **Secure Authentication**: Includes registration, login, email confirmation, and middleware validation.
- **Collaborative Features**: Users can invite collaborators, assign roles (manager, collaborator), and track task progress across five statuses: Pending, On Hold, In Progress, Under Review, and Completed.
- **Comprehensive CRUD Functionality**: Every project and task can be created, viewed, updated, or deleted with ease.
- **Advanced Task Management**: Features include a change history and threaded comments for every task.

### Built With

This app was designed to be both scalable and user-friendly, offering a modern solution to task and project management.

- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [TailwindCSS](https://tailwindcss.com/)

## Getting Started

Follow the steps below to set up the project locally:

### Prerequisites

To get started first you will need to install the following:

- NodeJS
- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [MongoDB](https://www.mongodb.com/es/cloud/atlas/register)
2. Get a free API Key at [MailTrap](https://mailtrap.io/es/)
3. Clone the repo
   ```sh
   git clone https://github.com/DaniGarridoNunez/planify_frontend.git
   ```
4. Install NPM packages in both /frontend and /backend
   ```sh
   npm install
   ```
5. Enter your API keys in `.env` at /backend for example:
   ```js
   DATABASE_URL=mongodb+srv://root:<db_password>@cluster0.example.mongodb.net/planify_mern
   FRONTEND_URL=http://localhost:5173
   SMTP_HOST=sandbox.smtp.mailtrap.io
   SMTP_PORT=2525
   SMTP_USER=yourusername
   SMTP_PASS=yourpassword
   JWT_SECRET=palabrasupersecreta
   ```
6. Enter your API keys in `.env.local` at /frontend:
    ```js
    VITE_API_URL=http://localhost:4000/api
    ```
7. And then run in both /frontend and /backend:
   ```sh
   npm run dev
   ```

## Usage

For those interested in how the project works without having to install it, here are some screenshots showcasing its key features:  

![Screenshot 1](https://picsum.photos/800/400)  
*Dashboard showing task statuses and project overview.*  

![Screenshot 2](https://picsum.photos/800/400)  
*Task details with comments and change history.*  

![Screenshot 3](https://picsum.photos/800/400)  
*Collaborator management and role assignment.*  

## Roadmap

- [x] Add collaboration support
- [x] Add user roles in projects
- [ ] Improve the Drag & Drop experience
- [ ] Multi-language Support
  - [x] Spanish
  - [ ] English

See the [open issues](https://github.com/DaniGarridoNunez/planify_frontend/issues) for a full list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git switch -c feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [MIT License](https://opensource.org/licenses/MIT) for more information.

## Contact

Daniel Garrido - danigarridonunez@gmail.com

Project Link: [https://github.com/DaniGarridoNunez/planify_frontend](https://github.com/DaniGarridoNunez/planify_frontend)