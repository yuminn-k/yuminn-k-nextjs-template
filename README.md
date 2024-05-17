# yuminnk-nextjs-template

This repository is a Next.js boilerplate project created with `npx create-next-app`, tailored for TypeScript development. It includes essential development tools such as GTS (Google TypeScript Style), commitlint, husky, and Jest.

## Table of Contents

- [Getting Started](#getting-started)
- [Scripts](#scripts)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/yuminnk-nextjs-template.git
    cd yuminnk-nextjs-template
    ```

2. **Install dependencies**:
    ```sh
    yarn install
    ```

3. **Run the development server**:
    ```sh
    yarn dev
    ```
    The application will be available at `http://localhost:3000`.

## Scripts

Here are the available scripts you can run in the project:

- `yarn dev`: Runs the development server.
- `yarn build`: Builds the production application.
- `yarn start`: Starts the production server.
- `yarn lint`: Lints the code using GTS.
- `yarn test`: Runs the tests using Jest.
- `yarn test:watch`: Runs the tests in watch mode.
- `yarn postinstall`: Sets up Husky for Git hooks.
- `yarn lint-staged`: Runs ESLint on staged files.

## Technologies Used

- **Next.js**: `14.0.4`
- **TypeScript**: `5.3.3`
- **GTS (Google TypeScript Style)**: `5.2.0`
- **Commitlint**: `18.4.4`
- **Husky**: `8.0.3`
- **Jest**: `29.7.0`

## Project Structure

The project structure follows the standard Next.js setup with a few additional configurations for linting and testing:

```
/yuminnk-nextjs-template
├── /components        # React components
├── /pages             # Next.js pages
├── /public            # Static assets
├── /styles            # CSS styles
├── /tests             # Jest tests
├── .eslintrc.js       # ESLint configuration
├── .gitignore         # Git ignore rules
├── commitlint.config.js # Commitlint configuration
├── jest.config.js     # Jest configuration
├── package.json       # Project dependencies and scripts
├── tsconfig.json      # TypeScript configuration
└── yarn.lock          # Yarn lock file
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.

Please ensure your code adheres to the project's linting and testing standards.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to customize this template to fit your needs!
