# Challenge 02 - Componentizing the application

## 💻 About the challenge

In this challenge, you must create an application to train what you have learned so far in ReactJS

This will be an application where your main objective is to refactor a page to list movies according to genre.

The application is already fully functional but most of its code is directly in the `App.tsx` file. To solve this in the best way, 
it is necessary to divide the application into at least two main parts: sidebar and the main content that has the header and the movie listing.
- The application has only one main feature, which is the movie listing;
- In the sidebar it is possible to select which category of movies should be listed;
- The first category in the list (which is "Action") should already start as checked;
- The application's header only has the name of the selected category that must dynamically change.

### Fake API with JSON Server

Just as we will use MirageJS in module 2 to simulate an API with transaction data from the dt.money application,
we will now use the JSON Server to simulate an API that has information about genres and movies.

Navigate to the created folder, open it in Visual Studio Code and run the following commands in the terminal:
```bash
yarn
yarn server
```

Notice that he started a fake API with the `/genres` and `/movies` resources on localhost on port `3333` from the information in the [server.json](https://github.com/rocketseat-education/ignite-template-componentizando-a-aplicacao/blob/main/server.json) file located
in the root of your project. Accessing these routes in your browser, you can see the return of information already in JSON.

### What should I edit in the application?

- **src/App.tsx** - This component contains the entire application with the exception of the Button component which does not need to be changed and Icon which also does not need to be changed.
- **src/components/Content.tsx** - This component, still empty, must have all the logic and body responsible for the header and content of the application.
- **src/components/SideBar.tsx** - This component, also empty, must have all the logic and body responsible for the section that contains the site title and the navigation part on the left of the page.

### 📖 [Notion](https://www.notion.so/Desafio-02-Componentizando-a-aplica-o-b9f0f025c95b437699d0c3115f55b0f1)
