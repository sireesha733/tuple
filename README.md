# tuple
#Touple:Orderd sequence of elements,It enclosees elements with  round bracket;
tuple_a=(1,2,3,4,True)
print(tuple_a[3])
#It is immutable
#Unpackage
a,b,c,d,e=tuple_a
print(d)
#sets:UnOrderd sequence of elements,It enclosees elements with curly brackets

set_a={23,34,56,7,54}
print(set_a)
#add()
set_a.add("siri")
print(set_a)
#update()
set_a.update([4,21,23])
print(set_a)
#remove()
#it will raise error if value not found
set_a.remove("siri")
print(set_a)

#discard()
#it will not raise the error
set_a.discard(23)
print(set_a)


