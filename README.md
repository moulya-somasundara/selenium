# selenium


This program implements three functions:

- login(username,password): This function uses selenium to login to Yelp.  

 

- submitReview(rev_text, rev_rating, restaurantID): this function submits a review for the restaurant with id restaurantID. The parameter rev_text is the review's text. The parameter rev_rating is the review's star rating. 
 

- vote(userID): this  function goes to the Yelp profile of the user with id=userID, and marks the first review  (the one at the top of the page) as "useful". 

 

- test(username,password,rev_text, rev_rating, restaurantID, userID): This function calls and tests the other 3 functions. 
