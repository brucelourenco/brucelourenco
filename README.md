```py
class myInfo():
    def __init__(self, name: str, age: int, hobby: list) -> None:
        self.name  = name        
        self.age   = age
        self.hobby = hobby
    
    def show_me(self):
        print(self.name, self.age, self.hobby)
    
myInfo('Bruce', 43, ['Reading', 'Play video game']).show_me()
```
