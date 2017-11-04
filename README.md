# react-vr-website
A VR website made with (https://facebook.github.io/react-vr/index.html)react-vr.

## Getting Started

We've designed the React VR developer experience to get your first project up and running in only a few minutes. Before installing the developer tools, you'll need to make sure that you have two prerequisites installed:

- Node.js version 6.0.0 or higher
- `yarn` or `npm` (>= v3.0.0) package managers

Next, install the React VR CLI – a command-line tool that generates the basic layout of new projects.

```
npm install -g react-vr-cli
```

Or

```
yarn global add react-vr-cli
```

You'll only need to install this CLI once. It will alert you when it's out of date, and provide instruction on how to update it.

Once installed, the CLI can be used to create a new project by running

```
react-vr init PROJECT_NAME
```

where `PROJECT_NAME` is the name of your new application. Once it's been created and the dependencies are installed, change your working directory to `PROJECT_NAME`, and start the application server by running `npm start` (or `yarn start`).

When the server has booted, you can access your application by navigating to `http://localhost:8081/vr/` in your web browser. Your application's code can be found in `index.vr.js`, and you can learn more about available framework features by diving into our documentation.

## Will My Web Browser Support My VR Headset?

The WebVR spec is currently in development, and it will be some time before browsers like Chrome, Firefox, and Edge begin supporting it in stable releases. Recent experimental browsers, and some versions of Chrome for Android, have begun to support the spec. You can follow the tables at [https://webvr.rocks](https://webvr.rocks/) to track support for WebVR.
