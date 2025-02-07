# gluestack-ui Starter Kit

Welcome to the gluestack-ui Starter Kit! This project is designed to help you kickstart your application development with React and React Native. It supports both Next.js and Expo, providing a flexible and modular architecture.

## Getting Started

### Installation

1. Clone the repository:

```bash
https://github.com/gluestack/gluestack-ui-starter-kits.git
```

2. Install dependencies:

Go to `expo-app`, `next` and `universal` folders and run the following command:

```bash
yarn
```

### Running the Application

#### Next.js

To run the Next.js application, run the following command:

```bash
cd next && yarn dev
```

#### Expo

To run the Expo application, run the following command:

```bash
cd expo-app && yarn start
```

#### Universal

To run expo app, run the following command:

```bash
cd universal && yarn run:expo
```

To run next app, run the following command:

```bash
cd universal && yarn run:next
```

## Project Structure

### Next.js

- `next`: Contains the Next.js application along with components and screens.

### Expo

- `expo`: Contains the Expo application along with components and screens.

### Universal

- `app/next`: Contains the Next.js application.
- `app/expo`: Contains the Expo application.
- `packages/components`: Shared components used across platforms.
- `packages/screens`: Shared screens that can be used in both Next.js and Expo projects.

# Usage

You can copy project of your choice and start building your application.

# Ejection

If you have copied the universal project and want to eject the project, you can run the following command:

```bash
cd universal && yarn eject
```
