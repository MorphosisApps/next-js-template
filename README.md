# Morphosis Next.js Template

This is a [Next.js](https://nextjs.org/) template for internal use in Morphosis Apps Co., Ltd.

## What does it come with?
  - [Tailwind CSS](https://tailwindcss.com/)
  - [next-seo](https://github.com/garmeeh/next-seo)
  - [next-i18next](https://github.com/isaachinman/next-i18next)

## How to use it?
You can create new Next.js project using this template by running
```
npx create-next-app [project-name] -e https://github.com/MorphosisApps/next-js-template
# or
yarn create next-app [project-name] -e https://github.com/MorphosisApps/next-js-template
```

## How to start development?
After you've init your new project, there are two ways to start development:
1. Local Environment
2. Docker

### Local Environment
System requirement for Local Environment:
- [Node.js 12.0](https://nodejs.org/en/) or later
- MacOS, Windows (including WSL), and Linux are supported

To start developing your application run `yarn dev`. This starts the development server on `http://localhost:3000`.

### Docker
System requirement for Docker:
- [Docker](https://www.docker.com/) 

For Docker you can start developing your application by running `yarn dev:docker`. This starts the development server on `http://localhost:3000`, but on Docker containers.

If you would like to add other dependencies you must stop Docker first by running `yarn stop:docker` then you have to re-run `yarn dev:docker` again.

## Testing
For **unit testing** it is using [Testing Library](https://testing-library.com/docs/react-testing-library/intro/). You can run it by:
```
# Run once
yarn test 

# or
# Run with --watch
yarn test --watch
```

For **UI testing** it is using [Storybook](https://storybook.js.org/). You can run it by:
```
yarn storybook
```
This starts the development server on `http://localhost:6006`.

For **e2e testing**... WIP.

---
**Feel free to contribute :)**
