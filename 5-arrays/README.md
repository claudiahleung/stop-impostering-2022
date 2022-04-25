* When working with arrays you should take advantage of the fact that you can operate efficiently on both ends; array problems often have simple brute-force solutions that use O(n) space, but there are subtler sollutions that *use the array itself* to reduce space complexity to O(1)
* Filling an array from the array is slow; check to see if it's possible to write values from the back
* Overwrite > deleting (because deleting requires moving all entries to the left) 
* Don't worry about preservering the integrity of the array (sortedness, keeping equal entries together) until it is time to return

