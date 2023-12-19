# Monorepo

Welcome to the Monorepo! This repository houses a collection of three distinct packages - SCSS, React, and Foundation. This monorepo architecture allows for managing multiple related packages under a single repository, enabling seamless development, testing, and deployment across interconnected projects.

# Purpose

The purpose of this project is to set up a configuration where we have three distinct packages under one repository to facilitate the reuse of dependencies. These packages are managed by Lerna and ultimately published to npm

## Packages

### 1. SCSS Package
The SCSS package contains a set of stylesheets written in Sass (SCSS syntax), providing a modular and scalable approach to styling web applications. It includes a variety of mixins, variables, and utility classes to streamline the styling process and maintain consistency across projects.

#### NPM Package
This SCSS package is published on npm as `@mono-mrinal/scss`. To install it, use the following command:
```bash
npm install @mono-mrinal/scss
```

### 2. React Package
The React package consists of reusable React components, designed to facilitate the development of dynamic and interactive user interfaces. These components are structured to enhance code reusability and maintainability in React-based applications.

#### NPM Package
The React package is published on npm as `@mono-mrinal/react`. To add it as a dependency, execute the following npm command:
```bash
npm install @mono-mrinal/react
```

### 3. Foundation Package
The Foundation package serves as the core groundwork for projects utilizing this monorepo. It may include shared configurations, utilities, or essential functionalities required across various applications within the repository.

#### NPM Package
The Foundation package is available on npm as `@mono-mrinal/foundation`. To integrate it into your project, use the following npm installation command:
```bash
npm install @mono-mrinal/foundation
```

## Usage
Each package within this monorepo can be utilized independently in your projects by installing the desired package via npm. Refer to the specific package's documentation or source files within the repository for detailed usage instructions, examples, and guidelines.

## Contributing
Contributions to this repository are welcome! Feel free to submit bug reports, feature requests, or pull requests to enhance the functionality, performance, or documentation of any package in this monorepo.