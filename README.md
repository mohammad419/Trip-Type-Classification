# Project Description 
Walmart uses both art and science to continually make progress on their core mission of better understanding and serving their customers. One way Walmart is able to improve customers' shopping experiences is by segmenting their store visits into different trip types.
Whether they're on a last minute run for new puppy supplies or leisurely making their way through a weekly grocery list, classifying trip types enables Walmart to create the best shopping experience for every customer.

Currently, Walmart's trip types are created from a combination of existing customer insights ("art") and purchase history data ("science"). In their third recruiting competition, Walmart is challenging Kagglers to focus on the (data) science and classify customer trips using only a transactional dataset of the items they've purchased. Improving the science behind trip type classification will help Walmart refine their segmentation process

## Data Fields
##### TripType - a categorical id representing the type of shopping trip the customer made. This is the ground truth that you are predicting. TripType_999 is an "other" category.
##### VisitNumber - an id corresponding to a single trip by a single customer
##### Weekday - the weekday of the trip
##### Upc - the UPC number of the product purchased
##### ScanCount - the number of the given item that was purchased. A negative value indicates a product return.
##### DepartmentDescription - a high-level description of the item's department
##### FinelineNumber - a more refined category for each of the products, created by Walmar
