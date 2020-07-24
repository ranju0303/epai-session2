# Something
    The syntax for a derived class definition looks like the class Something(object):Something is class name which inherits the property of an object(inheritance).When the class object is constructed, the base class is remembered. This is used for resolving attribute references.It doesnt require any oarameter to be passed while creating the object of the class.
# SomethingNew
    The syntax for a derived class definition looks like the class SomethingNew(object):SomethingNew is class name which inherits the property of an object(inheritance).When the class object is constructed, the base class is remembered. This is used for resolving attribute references.It requires an explicit parameter to be passed if necessary, of type Something.It also has an argument i whose default value is set to 0
# add_something
    This is a function whic takes list and i as a parameter.This method specifically responsible for creating cyclic reference in the program by setting somehting.somehting_new to Somehting_new which inadvertently points to Something.Its creates a list of object of type Something. 
# clear_memory
    This function is used for clearing the memory and any cyclic reference if present using the garbage collection.Garbage collection periodically frees and reclaims blocks of memory that no longer are in use.
# critical_function
    This fucntion creates the reference to Somehting and thereby adds the object of type Something to the list.It then calls clear_memory fucntion to remove unsed refrences and remove cyclic refrences as well.
# compare_strings_old
    Here its suboptimally testing whether two strings are exactly same or not.After that its trying to see if there is a particular character in that string or no.The use of == and list is majorly responsible for suboptimal behaviour of the function.
# compare_strings_new
     Here its optimally testing whether two strings are exactly same or not by using the intern string and using 'is' operator to check the equality instead of '=='.After that its trying to see if there is a particular character in that string or no by using set instead of list and thereby breaking the loop as soon as the character is found.
# sleep
    Python time sleep function is used to add delay in the execution of a program. We can use python sleep function to halt the execution of the program for given time in seconds. Notice that python time sleep function actually stops the execution of current thread only, not the whole program.
# char_list
    This creates the list/set of character in a string. 
# collection
    This contains list of refrence to object of type Something.
# __init__
    This acts as a constructor.
