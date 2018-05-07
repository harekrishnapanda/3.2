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
