import time 
while True:
    if time.asctime == "Bad Time":
        print("Your Bad Time is going ")
    elif time.asctime == "Good Time":
        print("Your good time started ")
    else:
        print("Your nothing started")