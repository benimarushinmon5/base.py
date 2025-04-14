with open('C:/Users/darry/OneDrive/Documents/vs code/darryl/python.py/Mr. Nelson/file.txt', "r") as file:
    for line in file:
        print(line)


    while True:
        line = file.readline()
        if(line == ""):
            break
        print(line)
