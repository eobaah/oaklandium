# Welcome to Oaklandium!

The website to learn more about the what, how, and why behind the initiative.

## Instructions for setup

The app uses a simple file structure for an Express web app server that renders views using HTML.

```sh
public/               # static assets
  css/                # css stylesheets
  img/                # Image assets will be stored here or on a CDN hosted on Azure
  js/                 # JavaScript files
  tests/              # test files for the application
views/                # html files
```

## Setting up your config

Run the command in the terminal so that the config loads correctly
`$ cp .env.template .env`

## Installing your dependencies

Run the following command in the terminal:
`$ yarn install` or `$ npm install` ... I'm not judging you.

### Starting your development server

Run the following command in the terminal:
`$ yarn dev` or `$ npm run dev`
