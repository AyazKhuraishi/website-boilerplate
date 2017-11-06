# website-boilerplate

A simple boilerplate for creating a website, with a live reloading development environment. Uses live-server for the development webserver.

## Running the server

Assuming you have Node.js already installed:

1. Clone this repository: `git clone https://github.com/LWTechGaming/website-boilerplate.git` (Or download the [ZIP package](https://github.com/LWTechGaming/website-boilerplate.git/archive/master.zip))
2. Browse to the repository folder, and run `npm install`.
3. If you wish, change the settings in `config.json`. For information about the values, see [Configuration](#configuration).
4. Run `npm start` and start editing your files. Whenever you save a file in the `public` folder, the browser window will be reloaded.

## Configuration

**Note:** Don't use this webserver to display the website online, use a proper webserver like Apache or Nginx for that!

The following values can be changed.

| Value | Description | Type | Default |
| ----- | ----------- | ---- | ------- |
| port | Port to run the webserver on. | Number | 8000 |
| host | Host URL to run the webserver on. | String | localhost |
| docRoot | Directory from which to serve the website. | String | ./public |
| openBrowser | Open a browser window when the webserver launches. | Boolean | true |
| notFoundFile | File to display when the user attempts to access a resource that doesn't exist on the server[*](https://github.com/tapio/live-server/issues/225). | String |  |
| waitBeforeReload | Amount of time in milliseconds to wait before reloading the browser window. | Number (ms) | 500 |
| logLevel | The level of logging output to display in the console. 0 = errors only, 1 = only important, 2 = everything. | Number | 2 |
