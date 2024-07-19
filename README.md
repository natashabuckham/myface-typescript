# MyFace

This project was an introduction to HTML, CSS, and making webpages dynamic using JavaScript.

## HTML
First, we implemented functionality in HTML by linking pages together using routing, displaying information using EJS syntax, and accessing data from Models.
We used semantic HTML tags and tested our pages using a screenreader to improve accessibility.
We implemented client-side form validation to complement existing server-side validation.

## CSS
Next, we styled the pages using CSS.
First, we designed some lo-fi wireframes to have a common direction to work towards.

![Screenshot 2024-07-19 113341](https://github.com/user-attachments/assets/be292347-d0be-4d54-8f10-a96f9ae8913f)

Next, we implemented styling, learning about CSS selectors and properties. We used mobile-first responsive design to ensure the elements were arranged correctly on differently-sized screens.

![Screenshot 2024-07-17 103530](https://github.com/user-attachments/assets/73894a67-ccff-40db-9f5e-4c3047b468d9)

![Screenshot 2024-07-17 103504](https://github.com/user-attachments/assets/9fc8a55c-8300-4684-b239-eba4db381e35)

We used JavaScript element selectors and event listeners, as well as CSS animations and pseudo-classes to implement dynamic elements. 
These included a collapsible menu and colour-changing buttons when hovered over.

## Getting started.

To get setup, download this code, and then run the following commands in the root directory of the app.

```shell
npm install
npm run migrate
npm run seed
```

- `npm install` downloads all the libraries that we depend on.
- `npm run migrate` setups a database for us to use.
- `npm run seed` adds some sample data to our database.

Once you have run all of those, we can simply start the app with

```shell
npm start
```

This should start the app, and we can see it by going to http://localhost:3001 in the browser.

To update the application, just change any of the code, save it, and the app should automatically update.
Just refresh the page to see the impact of your changes.

### Resetting the data

If you ever need to reset the database, then:

- stop the app
- delete the `dev.sqlite3` file.
- run `npm run migrate` and `npm run seed` again to re-make and re-populate the database.
