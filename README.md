my_fav = {"apple","banana","grapes"}
friend_fav = {"banana","kiwi","orange"}  

print(my_fav | friend_fav) #union
print(my_fav & friend_fav) #intersection
print(my_fav - friend_fav) #difference

my_fav.add("Mango")
print(my_fav) #addds an element into the my_fav

lst = [1,1,2,2,3,3,4]
print(set(lst))#converts into set
