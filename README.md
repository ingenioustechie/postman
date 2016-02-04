# Postman Chrome Extension Legacy Version
This repository is a fork from legecy code base. 

## Quick links


## About Postman

Postman helps you be more efficient while working with APIs. Postman is a scratch-your-own-itch project. The need for it arose while one of the developers was creating an API for his project. After looking around for a number of tools, nothing felt just right. The primary features added were a history of sent requests and collections.

## Features

### Create requests quickly.

- Compact layout
- HTTP requests with file upload support
- Formatted API responses for JSON and XML
- HATEOAS support
- Image previews
- Request history
- Basic Auth and OAuth 1.0 helpers
- Autocomplete for URL and header values
- Key/value editors for adding parameters or header values. Works for URL parameters too.
- Use environment variables to easily shift between settings. Great for testing production, staging or local setups.
- Keyboard shortcuts to maximize your productivity

### Document and share APIs.

- Use collections to organize requests.
- Document requests inside collections. You can even store entire HTML notes. Postman uses Bootstrap so you can use it too to style your notes.
- Download and share collections with your team of developers.

## Installation

### Installing from the zip file

If you downloaded the Postman zip file here is what you need to do to install it as a developer extension:

1. Go to Tools > Extensions inside Chrome by clicking on the wrench icon on top right.
2. Select "Load unpacked extension"
3. Select the "chrome" folder with manifest.json in it's root
4. Postman will be installed as a developer extension. 

The installation from the Chrome Web Store will remain independent with all your data.

### Building and installing from source

1. Install the dependencies `sudo npm install -g grunt grunt-cli`.
2. Generate the template.js and request.js files by running grunt. You can watch the folder for changes using `grunt watch`.
3. For miscellaneous grunt tasks, look at grunt.js.

## Submitting bugs for this legacy version of Postman Client

If you are using this legacy version locally, you may submit bugs on GitHub itself. Please include Postman and Chrome version along with your operating system.

> Report Issues at: [https://github.com/postmanlabs/postman-chrome-extension-legacy/issues](https://github.com/postmanlabs/postman-chrome-extension-legacy/issues)


## Important Notes

### If JavaScript is disabled for all sites

If JavaScript is disabled for all sites, in order to use the Postman packaged app, you will need to set an exception for it. In chrome settings, go to _Privacy > Content Settings > JavaScript > Manage Exceptions_ and add the following exception `chrome-extensions://<postman_extension_id>/`.

Postman packaged app's' extension ID can be found at `chrome-extensions://`.  Ensure **developer mode** is enabled and look for the ID under `Postman - REST Client`.

