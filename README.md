

class Student:

    def __init__(self, name = None, age = None, track = None, score = None):
        self.name = name
        self.age = age
        self.track = track
        self.score = score

    def setTrack(self, track,):
            self.track = track

    def setScore(self, Score):
            self.score = score

    def display(self):
            print("student name is: ", self.name)
            print("student age is: ", self.age)
            print("student track is: ", self.track)
            print("student score is: ", self.score)


std = Student("Bob", 26)
std.track = ("FB/BE")
std.score = (20.90)
std.display()
std = Student("Peter", 34)
std.track = ("GB/GC")
std.score = (40.7)
std.display()




