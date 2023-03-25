from tkinter import *

# button = you click it, then it does stuff

def click():
    print("You did it!")


window = Tk()

button = Button(window,
text="Click",
command=click)
button.pack()

window.mainloop()
