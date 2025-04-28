import pyautogui as pt 
import time
limit = input("enter limit")
msg = input("enter messge:")
i = 1

time.sleep(6)

while i <= int(limit):

pt.typewrite(msg)
pt.press("enter")

i+=1
