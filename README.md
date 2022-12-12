```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Engineer:

    def __init__(self):
        self.name = "Ben Clancy"
        self.role = "Platform Engineering"
        self.location = "London"
        self.languages = ["python", "terraform", "bash"]

    def welcome(self):
        print("Welcome to my Github Profile")


me = Engineer()
me.welcome()
```
