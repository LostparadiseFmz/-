import sys
import pyautogui as pya
count = 0
a = """HI I AM (your name)
I MADE THIS VIRUS 
This virus is just for studying
It is not harmful 2 your PC
If you want the code,visit the site "https://github.com/LostparadiseFmz/-"
"""
count1 = 0
while count < 100:
    count1 = count1 + 1
    pya.alert(a)
    pya.alert('But I\'ll  never tell you how too close this')
    pya.alert('You can do nothing')
    pya.alert('why don\'t you believe me')
    pya.alert('You have to click \'确定\' for 600 times so as to finish the loop')
    pya.alert('Enjoy!')
    if count1 == 100:
        sys.exit()
    else:
        pass
