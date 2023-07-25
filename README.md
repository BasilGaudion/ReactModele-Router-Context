# React Project Template

Welcome to my React Project Template ! This is a basic template which includes a configured setup for React Router and Context API. Everything is already connected, just clone the repository, install dependencies, and start the development server !

## Requirements 🔍

Before you begin, ensure that you have [Yarn](https://yarnpkg.com/) and [Node.js](https://nodejs.org/) installed on your local machine. If you don't have them installed, follow the links provided to download and install.

- [Node.js download link](https://nodejs.org/en/download/)
- [Yarn Installation guide](https://classic.yarnpkg.com/en/docs/install)

Verify the installation of both by running the following commands in your terminal:

```bash
node --version
yarn --version
```

## Getting Started 🚀

Follow these steps to get the project up and running:

1. Clone the repository to your local machine.

2. Navigate into the project's root directory and run the following command to install dependencies:

```bash
yarn
```
3. Start the development server by running the following command in a terminal window from within the project

```bash
yarn start
```

The app will start running on `localhost:8080`. Open it in your browser to view the application.

## Project Structure 📂

Here's a brief overview of the key files and their locations:

- **Context/Provider files**: `src/utils/providers`
- **Routing**: `src/utils/AppRoutes.js`
- **Initial Landing Page**: `src/pages/Home`

## Pages 📄

The application's pages are located in the `src/pages` directory. The initial presentation page is `Home` which is located at `src/pages/Home`.

## Routing 🚏

Routing in this application is handled by `react-router-dom`. The routes are defined in the `src/utils/AppRoutes.js` file. If you wish to add or modify routes, you will need to do it in this file.

## Context API 💡

All context providers are located in the `src/utils/providers` directory. The main provider `useDefaultProvider` can be found in this directory. 

Feel free to rename the provider, but don't forget to modify the provider name in the `src/components/App.js` file too.

## Contributing 🤝

Contributions are always welcome! Feel free to fork the repository and submit pull requests.

## Support 🆘

If you need any help or have questions, please open an issue on the repository.

## License 📜

This project is licensed under the MIT License.

---

That's it! Now you are all set to work on this React project. Enjoy coding!
