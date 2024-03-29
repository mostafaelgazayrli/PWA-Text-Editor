# Just Another Text Editor (J.A.T.E)

## Description

P.T.E is a Progressive Web Application (PWA) that runs in the browser, offline and can be installed locally to your machine. This application features a number of data persistence techniques, insuring the application runs regardless of browser supported function. P.T.E uses an IndexedDB database and the idb package. This application is deployed to Heroku, to access it in production continue reading the documentation!

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Installation](#installation)
5. [License](#license)
6. [Technologies Employed](#technologies-employed)
7. [Future Development](#future-development)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Usage
### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation
This application is deployed to [Heroku](https://justanotherte.herokuapp.com/).

To run P.T.E locally:

1. Pull down and/or branch this repository
2. Run ```npm i``` to install all dependencies
3. Invoke application with ```npm run start```
</br>
The following animation demonstrates the application's functionality:



![J A T E Demo](https://user-images.githubusercontent.com/107900180/206565673-960dc4c8-1d0e-447e-9606-88ef539e1031.gif)

</br>

The following image shows the application's ```manifest.json``` file:
![manifest](https://user-images.githubusercontent.com/107900180/206566689-e37bb4b2-783b-4328-afe6-16664b20181b.png)

</br>
The following image shows the application's registered service worker:

![serviceworker](https://user-images.githubusercontent.com/107900180/206567108-41efd859-b8d6-480b-8dc2-d383c4a76d06.png)

</br>
The following image shows the application's IndexedDB storage:

![idb](https://user-images.githubusercontent.com/107900180/206567448-c4d0939a-4690-4b40-a597-476b1e1c0c19.png)


## License
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.<p/>For more information visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

## Technologies Employed
* Mini-CSS-Extract Plugin
* Webpack+Workbox
* Concurrently
* JavaScript
* IndexedDB
* Express
* NodeJS
* Babel


## Future Development
We would like to continue to add the following functionality to our application:
- Overhaul CSS

## Contributing
We'd love for you to contribute! In order to do so, fork this repository. Your pull request will need approval in order to merge to ```main```. <br/><br/> Take a look at our [Future Development](#future-development) section to see what we are looking to expand on (implemented features are denoted with a &check;). Feel free to implement your own ideas and merge request!

## Tests
No tests were run to complete this CMS.

- - -
© 2022 Just Another Text Editor (P.T.E): PWA by mostafaelgazayrli, Confidential and Proprietary. All Rights Reserved.
