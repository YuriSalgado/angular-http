# angular-http-project

Simulates the development of an place picker based on user favorite places, practice essentials of http, nodejs, signals and observables

## Project Structure

```
src/app
│
├── places/ # responsible for application places
│ ├── available-places # display places to user select
│   ├── available-places.component.css
│   ├── available-places.component.html
│   └── available-places.component.ts
│ ├── places-container # container
│   ├── places-container.component.css
│   ├── places-container.component.html
│   └── places-container.component.ts
│ ├── user-places # favorite places that user selected
│   ├── user-places.component.css
│   ├── user-places.component.html
│   └── user-places.component.ts
│ ├── place.model.ts # modal for place
│ ├── places.component.ts # emit selected place
│ └── places.service.ts # logical for places operations
│
├── shared/ # responsible for common components
│ ├── modal/ # reusable AOC modal to provide feedback about server errors
│ └── error.service.ts # basic logical for errors
│
├── app.component.html # Template that orchestrates components
├── app.component.ts # Root component logic
│
├── index.html # Landing page
├── main.ts # Boostrap Angular
│
└── styles.css # Global styles
```

## Installation

Use the package manager [npm](https://www.npmjs.com/) and start app

For both client/server:

```gitbash
npm install
```

\*make sure you're in the correct directory

## Usage

```gitbash
npm start
```

\*make sure you're in the correct directory

1. Open in your browser http://localhost:4200/
2. Wait for 2 seconds (emulated server delay)
3. Choose how many favorite places you want add
4. Choose how many favorite places you want remove
5. Refresh page when do you prefer

## License

[MIT](https://choosealicense.com/licenses/mit/)

<p align="center">
  <img src="https://i.imgur.com/zLQPsuh.png" alt="Practice - place picker - app"/>
</p>
