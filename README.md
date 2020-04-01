# STL
std::make_heap(begin(numbers), end(numbers))
// makes heap out of a sequence of number

std::push_heap(begin(numbers),end(numbers))
//pushes the heap to its proper position in the heap

//we use heap to get maximum number in a very less time
//inorder to remove the max element
std::pop_heap(begin(numbers), end(numbers))
numbers.pop_back()

//Types of sorting
/*
#1)Normal sort
#2)Partial sort-->Sort until a point
#3)N sorting --> The element is at the correct position of the elements were sorted
#4)sort heap
#5)Inplace merge-->Incremental step in merge sort

#6)Partitioning--All blue ones at begining and not blue ones at the end 
#7)Partition point the border between the blue and non-blue

#8)Rotate -->put the elements at the beginning to the end 
#9)Shuffle-->Arranges the elements in random order
We can define order 
#10)Reverse that would reverse the elements collection


#11)Partitioning sort heap

#stable ---> 12)stable_sort
#			13)stable partition (check it not cleared )


#is ---> 14)is_sorted
#		15)is_partitioned
#		16)is_heap
Returns boolean

#is_*_until -->17)is sorted_until
#			  18)is partitioned_until
#			  19)is heap until

	Returns an iterator of the first position from where the predicate does not hold true, 
	easy to understand from the wordings of the above functions
#20) Count
#21) Accumulate
#22)Sum from beginning to the current point
#23)exclusive scan does not include the number 
#24)inner_product--->multiplication of the 2 arrays or elements and sum the whole thing
#25)adjacent_difference-->makes difference difference btwn every 2 neighburs in collection
#26)sample -->randomly geneates some number(check web not clear)

#27)All_of returns true if all elements satisfy the predicate
#28)any_of
#29)none_of


#30)Compare exact same content and same size--stood equal
same element but in different order -->Permutation and also returns boolean
#31)lexographical collection returns true if the first one is smaller 
#32)Mismatch -->stop wheneever the path differes,returns the pointer tp the partwhere the matchig differs

Searching valueu

Not Sorted
#33)Find returns the iterator pointing to that value
#34) Adjacent find returns the first position where 2 adj value occur in a row

Sorted
#35)equal_range-->returns subrange sicnce they would be together (look web_)
#36)lowe_bound
#37)upper bound
#38)Binary search -->boolean


#39)We can look for range of values ; look for a range in a big range--->Search
#40)Starts from the end to search the sub range --->find_end
#41)find first of 
#42)MAX ELE, MIN ELE,MINMAX ELE



Sets set_difference returns elements in the first set and not in the second set
Here both inout and output are sorted
Also there are set_union, set_intersection, and set_difference and set_symmetric_differeccne means 
the intersection between the two sets

Icnlude returns booloeadn all ele in B in A or not?

copy, move, swap_ranges(google)

copy_backward, move_backward
fill puts same values everywhere

generate(google)

iota(takes value puts in beginning and increments the values in the collection)

replace values in collection 
so repace every 42 by 56

Remove will pull up everything that is left after deleting a number and use erase to delete the blank memeory

Unique --> removes adjancet duplicates in collection and pull up the values 

copy also has many fucntions check them
Similaly if has many fucntions 

Transform applies function to every element in the collection 
A function could also take two parameters where 2 collections 
are feeded into ficntion and u gett the o/p
ex addition of 2 nos and + is the fucntion


For each applies function for side effects (google it)

Rare cases not explained 
