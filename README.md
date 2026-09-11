# code-13

list1=input().split()
list2=input().split()
set2=set(list2)
common_elements=[]
seen=set()
for item in list1:
    if item in set and item not in seen:
        common_elements.append(item)
        seen.add(item)
if common_elements:
    print(*(common_elements))
else:
    print("No Common Element")
