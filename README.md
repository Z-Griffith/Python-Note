


## fillter 用法
filter(function, sequence)
Parameters:
function: function that tests if each element of a 
sequence true or not.
sequence: sequence which needs to be filtered, it can 
be sets, lists, tuples, or containers of any iterators.
Returns:
returns an iterator that is already filtered.

# function that filters vowels
def fun(variable):
	letters = ['a', 'e', 'i', 'o', 'u']
	if (variable in letters):
		return True
	else:
		return False


# sequence
sequence = ['g', 'e', 'e', 'j', 'k', 's', 'p', 'r']

# using filter function
filtered = filter(fun, sequence)

print('The filtered letters are:')
for s in filtered:
	print(s)
