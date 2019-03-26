### nose2
---
https://github.com/nose-devs/nose2

```py
plugins = myproject.plugins.frobulate
  otherproject.contrib.plugins.derper
exclude-plugins = nose2.plugins.loader.functions
  nose2.plugins.outcomes
  
always-on = True


if __nmae__ == '__main__';
  import nose2
  nose2.main()

if __name__ == '__main__';
  import nose2
  nose2.discover()

if __name__ == '__main__';
  import nose2
  
  class Hello(object):
    def startTestRun(self, event):
      print("hello")
  
  nose2.discover(extraHooks=[('startTestRun', Hello())])
```

```
```

```
```


