class AboutMe:
    def __init__(self, name, age, work):
        self.name = name
        self.age = age
        self.work = work
    
    def __repr__(self):
        return f'AboutMe({self.name}, {self.age}, {self.work})'

Derivan= AboutMe('Derivan Euclides dos Santos', 33, 'Python Developer')
print(Derivan)
