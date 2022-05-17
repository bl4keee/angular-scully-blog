# MyBlog

This project is an interesting example on how angular application can be wisely combined with a static site generator in the form of scully so as to effectively generate robust apps in no time.

## Screenshot

Front page of an application.

![blog-front](https://user-images.githubusercontent.com/50672367/168911182-5ad277bd-ac7e-4aca-bb49-88a47e3a27c8.PNG)

## Build

1. Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
2. Run `npm run scully` to generate scully routes. This command creates `scully-routes.json` inside the `src/assets` folder which contains the routes of Angular application and is needed for Scully runtime.
3. Run `npm run scully:serve` to start two web servers - static prerendered version of website built with Scully and Angular live version of given application.
