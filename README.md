# Helpful Human Coding Challenge

## Table of Contents

- [License](#license)
- [Description](#description)
- [Deployed Application](#url)
- [Usage](#usage)
- [Goals](#goals)
- [Technology](#technology)
- [Issues](#issues)
- [Questions](#questions)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This app is to meant demonstrate some of my web development skills to Helpful Human via their applicant interview challenge.

I interviewed with the company on 5/4, began building the application on 5/5, and then finished the application and got it deployed on 5/9. Each day I would spend roughly 4-5 hours on developing, testing. and pushing the code to GitHub it.

Next steps with this app would be to figure out how to get the useQuery hook to work on the front end and then use the colors that I seeded into MongoDB and deploy that app with the database by using MongoDB's cloud platform. If you would prefer it, I could attempt to rework my code to get the useQuery GQL hook working to use GraphQL to supply the data on the front end.

## Url

<a href="https://helpful-brignola.herokuapp.com/">deployed application</a>

## Usage

Browse the app to view color swatches. There are 100 color swatches so the swatches are paginated to display 20 at a time. The swatches are grouped by into reds, yellows, greens, blues, and purples. Use the button at the bottom of the page to generate a random color swatch and display the hexadecimal code.

## Goals

<ul>
    <h3>Core</h3>
    <li>The app is styled with the required Google font in the App.css for the body of the SPA.</li>
    <li>The app is styled using Bootstrap.</li>
    <li>The app includes a magical donger.</li>
    <li>The application paginates 100 colors.</li>
    <li>The colors are paginated to show 20 at a time and are grouped by color.</li>
    <li>The swatch color shows the hexadecimal number for the color, the name of color on the label, and is displayed along with the color itself.</li>
    <li>A button can be pressed to generate a random color which displays the color itself and the hex code.</li>
</ul>

<ul>
    <h3>Stretch</h3>
    <li>The app is mobile optimized by using Bootstrap.</li>
</ul>

## Technology

<ul>
    <li>React.js</li>
    <li>Bootstrap CSS</li>
    <h4>Unavailable in this repo</h4>
    <li>MongoDB</li>
    <li>GraphQL</li>
</ul>

## Issues

I initially began building this application with a Mongoose and GraphQL back end, but I had issues using the useQuery hook on the front end. The back end went through fine and I could use Apollo to query the Mongoose database in the browser. I will link here the initial repository that I made which has the GraphQL api code which does function, but as I said, I had issues fetching data from the API on the front end.

<a href="https://git@github.com:PrismaticDevs/helpful-human.git">git@github.com:PrismaticDevs/helpful-human.git</a>

This was a strange non issue. I tried to deploy the app using Netlify, but when you would use the pagination component to navigate, the url went so /!# and the page came up with a 404. I then pushed the code to Heroku and the /!# route works fine with no problems. Strange to say the least.

## Questions?

Contact me:
Github: [PrismaticDevs](https://github.com/PrismaticDevs) <br>
Email: matthewbrignola@gmail.com <br>
Phone: 719-351-5828 <br>
