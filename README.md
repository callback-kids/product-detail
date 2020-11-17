# The Proto Company
<img src="https://fec-image-bucket.s3-us-west-2.amazonaws.com/Screen+Shot+2020-10-05+at+8.33.31+PM.png" />
## Table of Contents

- [Product Overview](#product-overview-page)
- [Features](#features)
- [Feedback](#feedback)
- [Build Process](#build-process)
- [Tech Stack](#tech-stack)

## Product Overview Page
The product overview page displays relevant information for a single product in the catalogue. The Proto Company catalogue is organized by *products*. One single product can be associated with many sizes and styles which each result in unique SKUs (stock keeping units). The product overview page presents items at the product level. Further breakdown by style or size is only reflected within the product detail page.

The same product detail page is displayed for every product in the catalogue. Upon navigating to the product detail page, using the searchbar to find a product, or selecting a new product to display, the contents of the page updates to show information relevant to the selected product. 

## Features

The item detail page is comprised of distinct modules. Each module displays information related to the product being displayed.   
The Overview module is the top-most module on the Product Detail page of The Proto Company website. The functionality contained within this module can be divided into several pieces:

	1. Image gallery 
		1. Default View
			* Dynamic Image
			* Overlay of Dynamic Thumbnails
			* Navigation Arrows for Thumbnails and main Image
			* Magnifying Glass
		2. Expanded View
			* Dynamic Image Overlay
			* Navigation Arrows
			* Image Icons
			* Zoom In / Zoom Out Icons
	2. Product information
		1. Star Rating
			* Average Rating
			* 5 Stars
			* Reviews Link
		2. Product Category
		3. Product Title
		4. Price
			* Dynamic Price
			* Prices Linked to SKUs
			* Default Price / Style
			* Idea: Enter promo code to see adjusted price
		5. Product Overview
			* Text Field
		6. Social Share
			* Pinterest
			* Twitter
			* Facebook
			* Email
	3. Style Selector
		* Thumbnails
		* Rows
		* Default First Style / Price
		* Selected Style Checkmark Overlay
	4. Add to Cart
		1. Size Dropdown
			* Default Text “Select Size”
			* In Stock / Out of Stock
		2. Quantity Selector
			* Range from 1 to max  in stock
			* If no size selected “-“
			* If size selected 1
		3. Button
			* Places item into cart
			* If the default ‘Select Size’ is currently selected: Clicking this button should open the size dropdown, and a message should appear above the dropdown stating “Please select size”
			* If there is no stock: This button should be hidden
			* If both a valid size and valid quantity are selected: Clicking this button will add the product to the user’s cart.

## Feedback

Feel free to [file an issue](https://github.com/callback-kids/product-detail/issues/new). Feature requests are always welcome. If you wish to contribute, please submit a [pull request](https://github.com/callback-kids/product-detail/issues)

## Build Process
## Build Process

To learn React, check out the [React documentation](https://reactjs.org/).

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Tech Stack
- JavaScript
- HTML5
- CSS3
- ReactJS and React Hooks
- NodeJS
- ExpressJS
- Jest
- Enzyme
- React-Bootstrap
