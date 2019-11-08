---
layout: page
permalink: /method
title: "Metodología de Trabajo"
description: "Documentación del trabajo del equipo CeMAS"
---
{% highlight python %}
def probando(n):
  if n > 2:
    print("Haciendo espacio para ver como se ve inserción de código en este diseño")
  else:
    print("Estoy inventado que cosas poner, intentaré con un código python largo")

# Testing

class Testing:
  def __init__(self, user, age, date):
    self.user = user
    self.age = age
    self.date = date
  
  def set(self, attr, arg):
    if attr == "age":
      self.age = arg
    elif attr == "date":
      self.date = arg
    else:
      print("Attribute doesn't exist.")

  def get(self, attr, arg):
    if attr == "age":
      return self.age
    elif attr == "date":
      return self.date
    else:
      print("Attribute doesn't exist.")

  def information(self, user):
    print("Information about user %s" %(user))
    print()
    print("Age: %s" %(age))
    print("Date: %s" %(date))
{% endhighlight %}