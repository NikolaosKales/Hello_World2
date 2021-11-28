# Hello_World2

## Function Parameters not Directly Declared

def printAll(*args): # All the arguments are 'packed' into args which can be treated like a tuple
    print("Number of arguments:", len(args))
    print()
    for argument in args:
        print(argument)
#printAll with 3 arguments
printAll('1','2','3')
#printAll with 4 arguments
printAll('1','2','3','4')
