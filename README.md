print('What is your name?')
name_ans = input()
print("Here is your first Question-")
list_Questions = ['How many days are in a week ?','7','4','8','5','How many minutes are there in an hour ?','60','59','59:59','70']
for i in list_Questions:
    print(i)
    if i==list_Questions[4]:
        while True:
            z = input("Enter your answer here : ")
            if True:
                ans = int(input("Kya aapka answer lock kiya jaaye?(For,Yes Type-'1'),(For,No Type-'2') : "))
            if ans==1:
                break
            else:
                continue
        if z == list_Questions[1]:
            print(name_ans,"win 7 Crore")
        else:
            print(name_ans,"lose 7 Crore ")
    if i==list_Questions[4]:
        a = int(input("Kya aap aage iss game ko continue karna chahenge ? Note = For 'Yes' Type(1),For 'No' type(2) : "))
        if a==1:
            continue
        else:
            print("Here is your second Question")
        if a!=1:
            break
    if i==list_Questions[9]:
        while True:
            z = input("Enter your answer here : ")
            if True:
                ans = int(input("Kya aapka answer lock kiya jaaye?(For,Yes Type-'1'),(For,No Type-'2') : "))
            if ans==1:
                break
            else:
                continue
        if z == list_Questions[6]:
            print(name_ans,"win 7 Crore")
        else:
            print(name_ans,"lose 7 Crore")
