🏋️‍♀️ Optimization challenge as a part of Le Wagon's Data Science course

## Objective

Analyze a dataset provided by an e-commerce marketplace called Olist to answer the CEO’s question: How could Olist increase its profit?

## Description
Olist is a leading e-commerce service that connects merchants to main marketplaces in Brazil. They provide a wide range of offers including inventory management, dealing with reviews and customer contacts to logistic services.

Olist charges sellers a monthly fee. This fee is progressive with the volume of orders.

Here are the seller and customer workflows:

Seller:

Seller joins Olist
Seller uploads products catalogue
Seller gets notified when a product is sold
Seller hands over an item to the logistic carrier
👉 Note that multiple sellers can be involved in one customer order!

Customer:

Browses products on the marketplace
Purchases products from Olist.store
Gets an expected date for delivery
Receives the order
Leaves a review about the order

## Problem

>❓ How many underperforming sellers should Olist remove to improve its profit, given that it has:
> - some revenues per sellers per months
> - some revenues per orders
> - some reputation costs (estimated) per bad reviews
> - some operational costs of IT system that grows with number of order items, but not linearly (scale effects)


## Dataset

The dataset consists of ~100k orders from 2016 and 2018 that were made on the Olist store, available as csv files
