<h1 align="center">
    <img src="./assets/logo.png" alt="Flora"/>
</h1>

<img src="./assets/flora.gif" alt="Gif of application"/>

# 🌱 Flora: plant shop
This is a plant e-commerce project to reinforce studied concepts of contemporary web development.
The project consists of two levels of access, the administrative and the customer. On the part of the administrator, it is possible to register and control the products available in e-commerce. In the customer section there is the product listing and the shopping cart to simulate sales.

## 📝 Project
A RESTfull API was used to serve the data, giving flexibility to distribute the application on multiple platforms and a SPA (Single Page Application) on the web front end to optimize performance and guarantee the best user experience.


## ⚙️ Back-end

### Technologies
- PostgreSQL
- TypeORM
- Node.js
- Express
- Multer (File upload middleware)
- TypeScript
- REST Architecture

### Concepts
- Use migrations to version the database, making collaborative work easier;
- Use ORM to manipulate the database, abstracting the database itself and simplifying possible changes;
- Use semantic HTTP requests respecting the meanings of verbs and naming collections with their real meaning;
- Use the concept of "Services" to perform actions on the application's resources that involve business rules, abstracting each business rule in a single file, making the code maintenance easier;
- Use HTTP routes to serve static files;
- Use a temporary folder to upload files to the server. In real large-scale applications the ideal is to transfer these files from the temporary folder to a static file server.

## 💻 Front-end

### Technologies
- React.js
- React Hooks
- Styled-Components
- TypeScript

### Concepts
- Use React components in function form, with modern syntax that is easy to understand and using React APIs;
- Use Axios to consume external API;
- Use React hooks to manipulate application states and optimize rendering cycles;
- Use the context API to make items in the shopping cart available to all pages of the application;
- Use the componentization of reusable elements, such as product cards, header and footer. This allows the modularization of the code construction, providing agility in the development and making the maintenance of the system agile;
- Use ESLint and Prettier to configure code writing standards, avoiding writing disagreement between team members.

###  Layout
The application layout is available on the [Figma](https://www.figma.com/file/nIT6fFPNfYZF5EOsRtqYg5/Flora-e-commerce?node-id=0%3A1).

## 🔧 Execute on your PC

- Clone this repository;
- Change to folder backend `cd backend`;
- Run the command to install the dependencies, like `npm install` or `yarn`;
- Create a PostgreSQL database with the name "flora";
- Update the ormconfig.json file with your database username and password;
- Run migrations with the `yarn typeorm migration: run` command;
- Start the backend running command `yarn dev:server` or `npm dev:server`, your backend will run at port 3333;
- Open new terminal on root folder and then change to folder web `cd web`;
- Run the command to install the dependencies, like `npm install` or `yarn`;
- After that, run the command to start the project, for example: `npm run dev` or `yarn start`;
- Then access the application at <strong> `http://localhost:3000`</strong>, change the port if you're using another.

## 🤔 How to Contribute

- Fork this repository;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m 'feat: my new feature'`;
- Push to your branch: `git push origin my-feature`.

## 📜 License

> This project is under the MIT license. See the archive [LICENSE](https://github.com/lauromvs/flora/blob/main/LICENSE.md) for more details.

---

##### <p align="center"> <strong> < developed by <a href="github.com/jessicafpx"> @jessicafpx</a> and <a href="github.com/lauromvs"> @lauromvs  </a> /> </strong> 👋