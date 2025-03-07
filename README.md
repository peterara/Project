# What is @fireactjs/saas

fireactjs-saas is the extension package for building SaaS web applications with Firebase, Reactjs and Stripe in a simple and fast approach. It is based on the `@fireactjs/core` package for the user authentication features. Its key features on top of the `@fireactjs/core` package are:

- Built-in Stripe subscription integration
- User permission control on the subscription account level
- Template base design for easy customization
- Component base architecture that supports full customization
- Easy to extend additional features

## Live demo

To experience the package, go to [https://saas-demo.fireactjs.com](https://saas-demo.fireactjs.com)

## Documentation

For documentation of the package, go to [https://fireactjs.com/docs/saas-package/](https://fireactjs.com/docs/saas-package/)

## Installation

Instructions for installing Fireactjs SaaS packages and creating your Reactjs SaaS application with the Fireactjs packages.

## Create Reactjs App with Fireactjs Core

Before installing the Fireactjs SaaS packages, you must set up your Reactjs application with the Fireactjs Core package for user authentication. Read [Fireactjs Installation Guide](https://fireactjs.com/docs/core-package/installation/).

## Install from NPM

The Fireactjs SaaS project comes with two packages: `@fireacjts/saas` for the Reactjs front-end and `@fireactjs/saas-cloud-functions` for the server-side Firebase Cloud Functions.

In your Reactjs app root folder, use the following command to install the `@fireactjs/saas` package:

```
npm i @fireactjs/saas
```

In your `/functions` folder where your Firebase Cloud Functions are located, use the following command to install the `@fireactjs/saas-cloud-functions` package:

```
npm i @fireactjs/saas-cloud-functions
```

