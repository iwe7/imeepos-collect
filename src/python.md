## classmethod(function)

> classmethod 是用来指定一个类的方法为类方法，没有此参数指定的类的方法为实例方法

```python
class Data(object):
    @classmethod
    def funcname(self, parameter_list):
        return self(parameter_list)
```
