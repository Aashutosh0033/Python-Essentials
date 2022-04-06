## Useful Functions

-> ***abs(number)*** : Returns absolute value<br>
-> *all(iterable)* : Returns if all  items in iterable object are True<br>
-> *bool([x])* : Returns bool value<br>
-> *chr(number)* : Returns character from specified unicode<br>
-> *ord(char)* : Returns ASCII value<br>
-> *dict(iterable)* : Returns dictionary of an iterable<br>
-> *list(iterable)* : Returns list of an iterable<br>
-> *tuple(iterable)* : Returns tuple of an iterable<br>
-> *set(iterable)* : Returns set of an iterable<br>
-> *int(var)/float(var)/str(var)* : Type Conversion<br>
-> *divmod(a, b)* : Returns remainder and quotient<br>
-> *map(func, iterable)* : Applies function to each element of iterable<br>
-> *filter(func, iterable)* : considers elements for which function returns true<br>
-> *reduce(func, iterable)* : Generates single value by applying function of 2 elements<br>
-> *len(iterable)* : Returns length<br>
-> *iter(object, sentinel)* : Returns iterable object - next(iterable_object)<br>
-> *enumerate(iterable, start = index)* : Provides index to Data Structure<br>
-> *max() & min()* : Returns maximum and minimum element in an iterable<br>
-> *pow(x,y)* : Returns x raised to y<br>
-> *repr(var)* : Returns strings representation of an object<br>
-> *reversed(iterable)* : Returns reversed iterable<br>
-> *round(number)* : Rounds a number<br>
-> *sorted(iterable)* : Returns a sorted iterable<br>
-> *sum(iterable)* : Sums items of an iterable<br>
-> *type(object)* : Returns type of data<br>
-> *zip(iterable1, iterable2, iterable3, ...)* : Returns iterator from 2 or more iterator<br>


## Special methods of Data Structures 
### String
-> *capitalize(string)* : capitalizes first character<br>
-> *lower(string)* : lowers string <br>
-> *count(iterable)* : Returns number of value repeated <br>
-> *endswith(char)* : Returns true if string ends with a value <br>
-> *find(char)* : search value and return its index <br>
-> *split(seperator)* : splits string at a specified seperator & returns list <br>
-> *upper(string)* : uppercases a string <br>
-> *title(string)* : Returns string with first letter of each word capital <br>
-> *casefold(string)* : lowers string<br>
-> *replace(old, new , count)* : replaces specified phrase with another specified phrase <br>
-> *swapcase()* : Returns uppercase letters lowercase and vice versa <br>
-> *"seperator".join(iterable)* : Takes all items in an iterable & joins them in one string we have to specify string as seperator <br>

### List
-> *append(value)* : Appends value at the end <br>
-> *clear(list)* : empty's whole list <br>
-> *copy(list)* : returns copy of list  <br>
-> *count(value)* : return number of elements with specified value  <br>
-> *extend(iterable)* : Joins two list <br>
-> *insert(pos, 'element')* : Adds element at a specified position  <br>
-> *pop(pos)* : Removes element at a specified position  <br>
-> *remove(value)* : Removes first element with specified value  <br>
-> *index(value)* : Returns index of first element with specified value <br>
-> *reverse(list)* : Reverse items <br
-> *sort(list)* : Sorts list <br>
### Tuple
-> *count(value)* : return number of elements with specified value  <br>
-> *index(value)* : Returns index of first element with specified value <br>
-> *tuple(iterable)* : Returns tuple of an iterable<br>
-> *len(iterable)* : Returns length<br>
-> *max() & min()* : Returns maximum and minimum element in an iterable<br>
-> *sum(iterable)* : Sums items of an iterable<br>
-> *sorted(iterable)* : Returns a sorted iterable<br>
### Dictionary 
-> *clear(dict)* : empty's whole dictionary <br>
-> *copy(dict)* : returns copy of dictionary  <br>
-> *fromkeys(x,y)* : Returns dict with specified keys and value  <br>
-> *get(key)* : returns value from specified key  <br>
-> *items()* : returns list containing tuple for each key value pair <br>
-> *keys()* : returns  list of keys  <br>
-> *pop(key)* : Removes element with specified key <br>
-> *popitem()* : Removes last key value pair  <br>
-> *update({key,value})* : Updates a key value pair  <br>
-> *values()* : List of all values  <br>
-> *setdefault(value)* : Returns key with specified value if key does not exists inserts key-value <br>
### Set 
-> *clear(seq)* : empty's whole set<br>
-> *copy(seq)* : returns copy of set <br>
-> *discard(value)* : removes a particular value  <br>
-> *add(value)* : adds a particular value  <br>
## File methods
-> *open("filename", "mode")* : opens a file for reading/writing/appending  <br>
-> *with open("filename", "mode") as file obj:* : opens a file for reading/writing/appending and creates a file object  <br>
-> *read()* - Returns file content<br>
-> *readlines()* - list of lines<br>
-> *readline()* - returns one line from content<br>
-> *tell()* - Returns file position<br>
-> *seek()* - changes file position<br>
-> *write()* - writes a specified string<br>
-> *writelines()* - writes list of string<br>

