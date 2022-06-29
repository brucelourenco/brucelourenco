class myInfo():
    def __init__(self, name: str, age: int, langs: list) -> None:
        self.name  = name        
        self.age   = age
        self.langs = langs
    
    def show_me(self):
        print(self.name, self.age, self.langs)
    
myInfo('Bruce', 42, ['Brazilian Portuguese', 'Poor English']).show_me()
