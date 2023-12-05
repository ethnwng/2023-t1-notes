*Definition* Functions that when called recursively, take a sub piece of the original data, with each function call reducing the overall size of the data. Normally performed on lists.

#### Example
```Java
(define (fn-for-lon lon)
	(cond [(empty? lon) 0] ; base case
		  [else
			  (+ (first lon) (fn-for-lon (rest lon)))] ; reducing to (rest lon)
```
