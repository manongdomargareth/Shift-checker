# shift-checker

print("   HELLO STUDENTS!")
print("")
print("   What shift are you?")
print("   A. Shift A")
print("   B. Shift B")
print("   C. Shift C")
print("")
choice = input("    => ")
if choice == 'A':
    print("")
    print("   What day is Today?")
    print("""
    A. Monday
    B. Tuesday    
    C. Wednesday 
    D. Thursday
    E. Friday
    F. Saturday
    G. Sunday""")
    print("")
    today = input("    => ")
    print("")
    if today == 'A'  or today == 'B':
        print("   Did you wear your School uniform and Id?")
        print("")
        print("   1. yes or 2. no ")
        print("")
        z = input("     => ")
        print("")
        if z == '1':
            print("   You may now enter the School Campus")
        elif z == '2':
            print("   You are not allowed to enter the School Campus")
        else:
            print("   Invalid input")
    elif today == 'C':
        print("   Did you wear your washing day outfit and Id?")
        print("")
        print("   1. yes or 2. no ")
        print("")
        z = input("     => ")
        print("")
        if z == '1':
            print("   You may now enter the School Campus")
        elif z == '2':
            print("   You can still enter the School Campus")
        else:
            print("   Invalid input")
    elif today == 'D' or today == 'E' or today == 'F' or today == 'G':
        print("   You are not allowed to enter the School")
    else:
        print("   Invalid input")               
elif choice == 'B':
    print("")
    print("   What day is today?")
    print("""
    A. Monday
    B. Tuesday    
    C. Wednesday 
    D. Thursday
    E. Friday
    F. Saturday
    G. Sunday""")
    print("")
    today = input("    => ")
    print("")
    if today == 'D'  or today == 'E' or today == 'F':
        print("   Did you wear your School uniform and Id?")
        print("")
        print("   1. yes or 2. no ")
        print("")
        z = input("     => ")
        print("")
        if z == '1':
            print("   You may now enter the School Campus")
        elif z == '2':
            print("   You are not allowed to enter the School Campus")   
        else:
            print("   Invalid input")   
    elif today == 'A' or today == 'B' or today == 'C' or today == 'G':
        print("   You are not allowed to enter the School Campus")
    else :
        print("   Invalid input") 
elif choice == 'C':
    print("   What day is today?")
    print("""
    A. Monday
    B. Tuesday    
    C. Wednesday 
    D. Thursday
    E. Friday
    F. Saturday
    G. Sunday""")
    print("")
    today = input("   => ")
    print("")
    if today == 'G':
       print("   Did you wear your Washing day outfit and Id?")
       print("")
       print("   1.yes or 2. no ")
       z = input("     => ")
       print("")
       if z == '1':
          print("   You may enter the School Campus")
       elif z == '2':
           print("   You are not allowed to enter the School Campus")   
       else:
           print("   Invalid input")
    elif today == 'A' or today == 'B':
        print("  Did you wear your School uniform and Id?")
        print("")
        print("   1. yes or 2. no ")
        z = input("     => ")
        print("")
        if z == '1':
           print("   You may enter the School Campus")
        elif z == '2':
            print(" You are not allowed to enter the School Campus")
        else:
            print("  Invalid input")
    elif today == 'C' or today == 'D' or today == 'E' or today == 'F':
        print ("   You are not allowed to enter the School Campus")
    else:
        print("  Invalid input")        
else:
    print("")    
    print("   Not valid")
