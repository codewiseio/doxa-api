# Contributing to the API documentation

Clone the repository from: 

    git clone https://github.com/codewiseio/doxa-api.git

Install the prerequisites

	npm install


## Development Server

You can now run the development server locally to view the documentation.

	npm start

View the documentation at http://localhost:9000/

Making changes to the specification file will refresh the page in the browser to
display the latest version.


## OpenAPI Spec

The API specification exists in ./src/openapi.yaml. Edit this file.

This document currently follows the Swagger 2.0 specification. 


## Publishing

Build the distribution files. This will generate files in the "docs" folder.

	npm run build

These documents will be served on Github pages:

	git add -A
	git commit -m "..."
	git push

