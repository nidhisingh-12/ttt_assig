Terribly Tiny Tales Assignment
Problem Statement

Develop a frontend in Reactjs or Nextjs, which does the following:

    Renders a "profile screen" as follows: https://www.terriblytinytales.com/profile.jpeg (this is a sample screenshot taken from mobile view)

    The profile data can be hardcoded in a local JSON and need not have a backend.

    The screen when opened on different mobile types, should render consistently. This can be checked in Chrome Inspect in mobile view, by changing device types or on actual physical devices.

Solution

    The solution is developed using Reactjs.
    The solution is responsive and can be viewed on different mobile types.
    Data is fetched from a local JSON file.
    The solution is developed using functional components and hooks.
    The solution is developed using Font-Awesome icons.
    UseState and CallBack hooks are used to handle the state and events.
    Components are used to make the code modular and reusable.
    Assests are used to store the images.
    CSS is used to style the components.

Steps to run the project

    Clone the repository.
    Run npm install to install the dependencies.
    Run npm start to run the project.
    Open http://localhost:3000 to view it in the browser.
    Inspect the page and change the device type to view the responsiveness.

Components

    App.js - The main component which renders the All child components.

    Consists of 3 child components:
        Navbar
        Profile
        Posts

    Also consists 2 elements:
        Cover Image
        Posts Container UI

    Navbar.jsx - The component which renders the Navbar.

    Profile.jsx - The component which renders the Profile.

    Posts.jsx - The component which renders the Posts.

Fuunctionalities

    The Navbar is fixed at the top of the page.
    The Profile is renders the profile data and show total number of followers, following and user reviews.
    The Posts renders the posts data and show total number of posts along with like button which increments the number of likes on click.
    The page is responsive and can be viewed on different mobile types.
