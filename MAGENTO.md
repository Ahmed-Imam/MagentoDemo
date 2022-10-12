
PartsLogic Magento Integration
======
To install the PL components, it will require a combination of accessing the Magento Admin Panel and uploading/editing files via SFTP for the backend files.
## Table of Contents

* [Prerequisites](#prerequisites)
* [Setup account to use REST API](#rest-api)
* [Install PL javascript library](#install-pl-javascript-library)
* [Install PL CSS](#install-pl-css)
* [Usage](#usage)
   - [Search Bar](#search-bar)
   - [Search Result Page](#search-result-page)
   - [Fitment Selector](#fitment-selector)


## Prerequisites

-  To use the PL Search Engine you will need an active PL account. If you don’t have an account you can sign up [here](https://partslogic.com/pricing/](https://partslogic.com/request-demo/)). See plans and pricing [here](https://partslogic.com/pricing/).
- Create the required API key for the PartsLogic ETL process in the Admin Panel, this step is typically executed by our developers once the API is ready.

## REST API

For Magento, PartsLogic needs the following RESTful API to provide you with optimized search experience:

- Get products endpoint 
- Get Categories enpoint 
- For fitments PL needs CSV file that includes (PRODUCT_ID, Year, Make, Model)


## Install PL Javascript Library

First thing first, we need to install the following libraries:
- [React dom](https://unpkg.com/react-dom@17.0.2/umd/react-dom.production.min.js)
- [React](https://unpkg.com/react@17/umd/react.production.min.js)
- [PartsLogic](https://unpkg.com/@partslogic/ui@0.0.17-alpha.0/build/index.umd.js)

after installing the above libraries, navigate to your Magento app `app/design/frontend/<Theme Name>/theme/web/js` and upload the above files so we can access them in the next step

## Install PL CSS
This template follows a very simple project structure:
- `src`: This folder is the main container of all the code inside your application.
  - `api`: This folder contains all endpoints that are used in the app.
  - `assets`: Asset folder to store all images, vectors, etc.
  - `components`: Folder that contains all resuable application components.
      - `MyComponent.js`
      - `styles.js`
      - `index.js`
  - `utils`: Folder to store any kind of helper that are need to be used all over the app.
  - `store`: This folder contains all the application state and its actions to update them`
  - `navigation`: Folder to setup the navigation/routes across the app.
  - `screens`: Folder that contains all the screens of the app.
  - `App.js`: Main component that starts your whole app.
- `index.js`: Entry point of your application as per React-Native standards.

# Usage
  ## Search Bar
  ## Search Result Page
  ## Fitment Selector


