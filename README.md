# Forkify

Forkify is a recipe application that allows users to search for recipes, view detailed recipe information, and manage their favorite recipes through bookmarks. The application also supports adding new recipes and adjusting servings based on user preferences.

## Features

- **Recipe Search**: Users can search for recipes based on keywords. The application fetches search results asynchronously and displays them to the user. Pagination is supported to navigate through multiple pages of results.
- **Recipe Details**: Upon selecting a recipe, detailed information is loaded asynchronously, including ingredients, cooking steps, and serving size. Users can also update the serving size dynamically.
- **Bookmarks**: Users can bookmark their favorite recipes, which are stored in the browser's local storage. Bookmarked recipes can be easily accessed and managed within the application.
- **Add Recipes**: Users can add their own recipes to the application. The new recipes are uploaded asynchronously and become available in the search results. They are also bookmarked automatically.

## Application Workflow

![Flowchart](forkify-flowchart.png)

## Getting Started

To run the application locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/Icy-Guo/forkify.git
   ```

2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Run the project:
   ```bash
   npm run start
   ```

## Project URL

You can also try to use this application online! [Forkify](https://forkify-icy.netlify.app/)
