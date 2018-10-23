'''
Problem Statement 1:
Implement a Python program to generate all sentences where subject is in
["Americans", "Indians"] and verb is in ["Play", "watch"] and the object is in
["Baseball","cricket"].
Hint: Subject,Verb and Object should be declared in the program as shown below.
subjects=["Americans ","Indians"]
verbs=["play","watch"]
objects=["Baseball","Cricket"]
Output should come as below:
Americans play Baseball.
Americans play Cricket.
Americans watch Baseball.
Americans watch Cricket.
Indians play Baseball.
Indians play Cricket.
Indians watch Baseball.
Indians watch Cricket.
'''


# 3.2
class Svo:
   def __init__(self, subject, verb, object):
      self.subject = subject
      self.verb = verb
      self.object = object
   
   def displaySvo(self):
      print (self.subject, self.verb, self.object)
      
subjects=["Americans ","Indians"]
verbs=["play","watch"]
objects=["Baseball","Cricket"]
    
for x in subjects:
    for y in verbs:
        for z in objects:
            Svo1 = Svo(x, y, z)
            Svo1.displaySvo()
