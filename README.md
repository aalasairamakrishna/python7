# python7
dictionary basic program
person={'name':'ASRK','age':22,'city':'mylavaram'}
print(person)
print("accessing and modifying the person age:")
person["age"]=23
print(person)
print("add and remove items")
person['email']= "aalasairamakrishna@gamil.com"
print(person)
del person['city']
print(person)
print("all keys and values")
print(person.keys())
print(person.items())
print(person.get('age'))


#dictionary touple with keys
location={
    (12.345,-67.890):"USA",
    (34.647,-67.755):"UK"}
print(location[(12.345,-67.890)])
