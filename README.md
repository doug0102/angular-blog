# AngularBlog

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.1.

## Contentful

This project uses [Contentful](https://www.contentful.com/) to create blog posts that are then consumed in this application. You will need to create an account and have a content model with the following fields

- `Name: Title, Field ID: title, Type: Short Text`
- `Name: UrlHandle, Field ID: urlHandle, Type: Short Text`
- `Name: FeaturedImage, Field ID: featuredImage, Type: Media`
- `Name: UrlHandle, Field ID: urlHandle, Type: Short Text`
- `Name: Summary, Field ID: summary, Type: Long Text`
- `Name: Content, Field ID: content, Type: Rich Text`
- `Name: Author, Field ID: author, Type: Short Text`
- `Name: UpdateDate, Field ID: updateDate, Type: Date & Time`
- `Name: Visible, Field ID: visible, Type: Boolean`

You will also need to copy your API key information from Contentful and add it to the `environment.ts` file environment object as

- `spaceId: 'YOUR-SPACE-ID'`
- `accessToken: 'YOUR-ACCESS-TOKEN'`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
