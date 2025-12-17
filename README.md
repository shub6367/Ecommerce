# EasyShop

## Description

An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enables three main different flows or implementations:

1. Buyers browse the store categories, products and brands
2. Sellers or Merchants manage their own brand component
3. Admins manage and control the entire store components 

### Features:

* Node provides the backend environment for this application
* Express middleware is used to handle requests, routes
* Mongoose schemas to model the application data
* React for displaying UI components
* Redux to manage application's state
* Redux Thunk middleware to handle asynchronous redux actions

## Getting Started

### Prerequisites

* Node.js
* MongoDB
* npm or yarn

### Installation

1. Clone the repository
```
git clone <your-repository-url>
cd project
```

2. Install dependencies
```
npm install
```

3. Set up environment variables
   - Create `.env` files in both `client` and `server` directories
   - See the example files for required environment variables

4. Start the development server
```
npm run dev
```

The application will be available at `http://localhost:3000`

### Database Setup

1. Make sure MongoDB is running
2. The application will automatically create the necessary collections
3. To seed the database with initial data, run:
```
npm run seed:db admin@example.com yourpassword
```

## Development

- Client runs on port 3000
- Server runs on port 5000
- API endpoints are prefixed with `/api/v1`

## ENV

Create `.env` file for both client and server. See examples:

[Frontend ENV](client/.env.example)

[Backend ENV](server/.env.example)


## Vercel Deployment

Both frontend and backend are deployed on Vercel from the same repository. When deploying on Vercel, make sure to specifiy the root directory as `client` and `server` when importing the repository. See [client vercel.json](client/vercel.json) and [server vercel.json](server/vercel.json).

## Start development

```
npm run dev
```

## Languages & tools

- [Node](https://nodejs.org/en/)

- [Express](https://expressjs.com/)

- [Mongoose](https://mongoosejs.com/)

- [React](https://reactjs.org/)

- [Webpack](https://webpack.js.org/)


### Code Formatter

- Add a `.vscode` directory
- Create a file `settings.json` inside `.vscode`
- Install Prettier - Code formatter in VSCode
- Add the following snippet:  

```json

    {
      "editor.formatOnSave": true,
      "prettier.singleQuote": true,
      "prettier.arrowParens": "avoid",
      "prettier.jsxSingleQuote": true,
      "prettier.trailingComma": "none",
      "javascript.preferences.quoteStyle": "single",
    }

```

