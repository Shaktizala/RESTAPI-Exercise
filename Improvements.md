I have gone through all the files and there is room for improvements.

* Used plural for resources always instead singular
	* Example
		* Correct: 
			* /customers/{customerId}/orders/{orderId}/
		* Incorrect:
			* /customer/{customerId}/order/{orderId}/
* Wrap parameters between curly braces
	* Example
		* Correct: 
			* /customers/{customerId}/orders/{orderId}/
		* Incorrect:
			* /customers/<customerId>/orders/<orderId>/
* Used lowercase always
	* Example
		* Correct: 
			* /customers/{customerId}/orders/{orderId}/
		* Incorrect:
			* /Customer/{CustomerID}/Orders/{OrderID}/
			* /CUSTOMERS/{CustomerID}/ORDERs/{OrderID}/
			* /customers/{CustomerID}/orders/{OrderID}/
			* /customers/{CUSTOMERID}/orders/{ORDERID}/
* Do not use space between variable names
	* Example
		* Correct: 
			* /customers/{customerId}/orders/{orderId}/
		* Incorrect:
			* /customers/{customer Id}/orders/{order Id}/
			* /customers/{customer id}/orders/{order id}/
			* /customers/customer id/orders/order id/
* Add resources name before it's parameter
	* Example
		* Correct: 
			* /customers/{customerId}/orders/{orderId}/
		* Incorrect:
			* /customers/{customerId}/{orderId}/
* Never repeat resources name in payload
	* Example 
		* Correct
			* POST /hotels/    
          ```
          {   
            id : 1,   
            name : abc,   
            rating : 3,   
          }  
          ```
      * Incorrect
        * POST /hotels/ 
          ```
          {   
            hotelId : 1,   
            hotelName : abc,  
            hotelRatings : 3,   
          }
          ```
