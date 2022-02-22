


# fillter() 用法
filter(function, sequence)
Parameters:
function: function that tests if each element of a 
sequence true or not.
sequence: sequence which needs to be filtered, it can 
be sets, lists, tuples, or containers of any iterators.
Returns:
returns an iterator that is already filtered.

### function that filters vowels
def fun(variable):
	letters = ['a', 'e', 'i', 'o', 'u']
	if (variable in letters):
		return True
	else:
		return False


### sequence
sequence = ['g', 'e', 'e', 'j', 'k', 's', 'p', 'r']

### using filter function
filtered = filter(fun, sequence)

print('The filtered letters are:')
for s in filtered:
	print(s)

# flatmap() 用法

https://www.geeksforgeeks.org/scala-flatmap-method/?ref=gcse

In Scala, flatMap() method is identical to the map() method, but the only difference is that in flatMap the inner grouping of an item is removed and a sequence is generated. It can be defined as a blend of map method and flatten method. The output obtained by running the map method followed by the flatten method is same as obtained by the flatMap(). So, we can say that flatMap first runs the map method and then the flatten method to generate the desired result.
Note:

It has a built-in Option class as an Option can be expressed as a sequence which has at most one element i.e, either its empty or has only one element.
The flatten() method is utilized to disintegrate the elements of a Scala collection in order to construct a single collection with the elements of similar type.

# Collect() – Retrieve data from DataFrame

https://www.geeksforgeeks.org/pyspark-collect-retrieve-data-from-dataframe/?ref=gcse

