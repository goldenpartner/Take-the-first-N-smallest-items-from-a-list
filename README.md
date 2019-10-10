### Quick Insertion

#### This method first uses quick sort to sort the first n elements in a given array and then save the sorted part.
#### Then for the rest elements, if it is less than the largest element in the sorted part, 
#### it will be inserted into the sorted part and the the last element of sorted part is dumped.

#### Comparing to numpy's sort method, this new method is faster than np's sort most of time.
