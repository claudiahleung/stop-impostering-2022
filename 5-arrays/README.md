* When working with arrays you should take advantage of the fact that you can operate efficiently on both ends; array problems often have simple brute-force solutions that use O(n) space, but there are subtler sollutions that *use the array itself* to reduce space complexity to O(1)
* Filling an array from the array is slow; check to see if it's possible to write values from the back
* Overwrite > deleting (because deleting requires moving all entries to the left) 
* Don't worry about preservering the integrity of the array (sortedness, keeping equal entries together) until it is time to return

### List — key operations
`len(A)` //  `A.append(a)` // `A.remove(42)` // `A.insert(42)` // `A.insert(42)` 
- Binary Search for sorted lists — `bisect.bisect(A, 6)` // `bisect.bisect_left(A, 6)` // `bisect.bisect_right(A, 6)`
- `A.reverse()` // `A.sort()` (in-place)
- `A.reversed()` (returns an iterator)
- `del A[i]` (deletes the i-th element); `del A[i:j]` (removes the slice)

### Tips
- Use slicing to **rotate a list** (e.g. `A[k:] + A[:k]` rotates `A` by `k` to the left)
- List comprehension — succinct way of creating lists (clearer than `map()` and lambda functions, and supports multiple levels of looping), but don't use more than two nested comprehension + indentation in conventional nested for loops makes the programme easier to read

#TODO:  
- [ ] deep copy vs shallow copy
- [ ] 
