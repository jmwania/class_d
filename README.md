class Dog:
   # class attribute
  species = 'mammal'

  def __init__(self, name, age):
    self.name = name
    self.age = age

dip = Dog("dip", 4)
mtote = Dog("mtote", 6)

print("{} is {} and {} is {}.".format(dip.name, dip.age, mtote.name, mtote.age))

# Is dip a mammal
if dip.species == "mammal":
  print("{} is a {}!".format(dip.name, dip.species))
   