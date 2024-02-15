# lama
import tkinter as tk

def button_click():
    print("Button clicked!")

# Create the main window
root = tk.Tk()
root.title("Button Example")

# Create a button widget
button = tk.Button(root, text="Click Me!", command=button_click)
button.pack(pady=20)

# Run the Tkinter event loop
root.mainloop()
