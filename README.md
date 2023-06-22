# Agilo storefront

## Description

This is a storefront made using React (Typescript), Next.js, Medusa.js, Stripe and Tailwind CSS. The store uses the Medusa.js backend to fetch products and handle the checkout process. The storefront is branded around the Agilo brand and is meant to be used as a template for other stores. The project is structured very rigidly to make it easy to add new pages and components, without being too opinionated and complex to structure.

The project ultimately took around two weeks to complete, having a lot of time saved by using the Medusa.js CLI to generate a lot of the boilerplate code.

The most challenging implementation was the user account page / user dashboard, while the implementation that I'm most proud of is the product page, which is very flexible and scalable and can be used for a lot of different types of products.

## How to run

To run the project, just clone the repo and run `yarn dev` in the root directory. The project will be available at `localhost:8000`.
Before visiting the site, fire up a Medusa.js server with the products you want to be available on the storefront. The storefront will fetch the products from the Medusa.js server.

### Made by Tonči Crljen
