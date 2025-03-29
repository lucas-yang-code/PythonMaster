# Python Master

## Chapter 1 Programmation Orienté objet
### 1. Classes et objets
```python
# Concevoir la classe Student
class Student:
    name = None # Enregistrer le nom de l'élève

# Création d'objets basés sur des classes
stu_1 = Student()
stu_2 = Student()

# Affectation des propriétés de l'objet
stu_1.name = "Alex"
stu_2.name = "Mika"
print(stu_1.name)
print(stu_2.name)
```
### 2. Méthodes des membres
 - Définition et utilisation des classes
```python
class Student:
    name = None
    age = None

    def say_hi(self):
        print(f"Bonjour à tous, je m'appelle {self.name} et j'ai {self.age} ans.")

stu_1 = Student()
stu_1.name = "Alex"
stu_1.age = 14
stu_1.say_hi()

stu_2 = Student()
stu_2.name = "Mika"
stu_2.age = 15
stu_2.say_hi()
```
```python
stu_1 = Student()
```
### 3. Self

- Le mot-clé self, bien que figurant dans la liste des arguments, peut être ignoré lors du passé

```python
class Student:
    name = None
    age = None

    def say_hi(self):
        print(f"Bonjour à tous,  je m'appelle {self.name} et j'ai {self.age} ans.")

    def say_hi2(self, message):
        print(f"Bonjour à tous, {message}")

# Création d'un objet basé la classe Student
stu = Student()
stu.name = "Alex"
stu.age = 18
stu.say_hi()
stu.say_hi2("enchanté.")
```

