 studentclass Student:
    def __init__(self, id, name):
        self.id = id
        self.name = name

students = []

def add_student(id, name):
    students.append(Student(id, name))
    print("Student added")

def show_students():
    for s in students:
        print(s.id, s.name)

add_student(1, "Priya")
add_student(2, "Ravi")
show_students()