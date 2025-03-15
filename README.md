lst = [1,1,1,1,1, 2,2,2,  3,3, 4, 5]
lst1 = []

for i in lst:
    if i not in lst1:
        lst1.append(i)
for i in lst1:
    print(f"{i}: {lst.count(i)*'*'}")
    
