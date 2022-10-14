from datetime import *

before = datetime.now()

text = "Kartal kalkar dal sarkar, dal sarkar kartal zor kalkar"
print("Yazacağınız Cümle: {}".format(text))

if text == input(": "):
    after = datetime.now()
    
    speed = after - before
    seconds = speed.total_seconds()
    
    print("Tebrikler!")
    print("Saniye cinsinden süreniz: {} saniyedir.".format(seconds))
else:
    print("You failed.")
