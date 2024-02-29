# GolfRetail
 Full stack App for GolfRetail
 Created by Yifan Lin, Srikaleek, and Me

This website is a retail website for a driving range. The user is going to be able to checkout an assortment of range ball buckets which are offered in unlimited amounts. The user will also be able to rental golf clubs which have a limited inventory. The user will also be able to see a list of instructors but is not able to perform any actions regarding them.

The admin view will have add and update forms to perform those actions for range ball buckets, club rentals, and instructors. The delete button will perform a soft-delete in the backend. The add, update, and delete functionalities are not visible to the user. For update ability, the admin has view access to the product_id and they will have to manually input that into the form. If the admin wants to update the image, they will have to have the image within the correct images folder in the express application and just type in the image name.

After a user adds items to cart and clicks the submit button, the cart is automatically emptied for that user and the items are added to the order history that can be found on the home page.

Register page has form validation built in for user field to make sure a value is present. The password field has additional complexity rule validation. If a duplicate user is attempted to be created, the user is brought to a separate page for warning and they will have to redo their registration.
