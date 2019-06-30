# Storybook for Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Add storybook to Angular-CLI

First, install the @storybook/cli package globally:
`npm i @storybook/cli -g`
Now, in the root of an Angular project, run the `getstorybook` command:
This command will autodetect that it’s an Angular project and will add the necessary configurations, devDependencies and npm scripts.

## Run StoryBook

Run `npm run storybook` to run storybook.

## Build Storybook

Run `npm run build-storybook` to build storybook in a folder called storybook-static.

## Add styles to storybook page

Add a file called 'preview-head.html' in the '.storybook' folder that’s added by Storybook to the root of the project. In that file, you can add anything that would go into the head of a document. You can add your global styles in that file.

## Official Documentation

[Storybook](https://storybook.js.org/docs/basics/introduction/)