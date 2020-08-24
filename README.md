# Run Angular with Goland

This project was be generated and runs by Angular 9 and Golang 1.14 .

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Run server

Before we run the project, we need to build it first. After that run `go run main.go` or run `npm start` for a dev server. Navigate to `http://localhost:3000/`. 
You need to reload the page if you change any of the source files. You don't need to build again because I add `--watch=true` to Angular build.

Our project will be hosted on Goland which runs as a background below.

## Benefits when we run by GO

- Faster because don't run on Node server.
- Easier to add the middleware before go to our application page.
