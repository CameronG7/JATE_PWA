# JATE_PWA

## Description

![alt text](https://img.shields.io/badge/License-MIT-blue )

In this project I have developed a single page application that serves as a in-browser text editor. The primary purpose of this application is to demonstrate the use of caching assets using the browsers cache and the IndexedDb. 
This caching allows the app to run correctly with out a network connection after the app had been loaded once while online.
With the inclusion of webpack, babel and workbox, we are also able to use a ```manifest.json``` file to make the application a PWA. This allows the app to be installed to the local machine and open in a browser environment allowing it to be used offline and outside of the browser.
This project was a big jump in understanding the basic technologies behind frameworks like React, Angular and Vue, that utilize webpack to enable their use in older browsers. 

## Installation

No installation necessary, just open the link to the app.
To utilize the apps PWA functionity, click the install button in the top left and accept the prompt that shows up.
If you decline, simply reload the page to enable the functionality again.


## Usage

![image](https://github.com/CameronG7/JATE_PWA/assets/122698132/89660f17-93da-4f7d-aed5-a0fdb8876936)

[app link](https://salty-temple-36941-0e4bb5ef543d.herokuapp.com/)

When you type in the text editor the text is saved to local storage, then when the editor loses focus the text is saved to the IndexedDB.
To properly cache the page, refresh after the initial load.


## Credits

This app was built using express, idb , babel, webpack and workbox along with some starter code provided to me by the UCB bootcamp.

## License

MIT License

Copyright (c) [2023] [Cameron Gardner]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## How to Contribute

My github account is [CameronG7](https://github.com/CameronG7/),  you can reach me at cameron.gardner777@gmail.com

To contribute, please contact me.

## Tests

No tests to run.
