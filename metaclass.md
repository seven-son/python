python既是一门函数式语言也是一门面向对象语言,所以有着一切皆对象和所有的东西都可以作为参数和返回值的思想.
1. python中的类也是对象,在其他语言中类是声场对象的模板,在python中类也是一种对象.只不过是这个对象有创建对象的能力

```

class ObjectCreator(object): #创建了一个类
    pass
my_object = ObjectCreator()  #生成一个对象

def funcreator():
    pass
    
print(type(funcreator))
print(type(type(funcreator)))
print(type(my_object))
print(type(ObjectCreator))
print(type(type))

不管是函数还是对象最后的类都是type


````

2. 你可以将他赋值给变量,你可以拷贝他,



3. 你可以给他增加属性




4. 你可以将他作为函数的函数进行传递






