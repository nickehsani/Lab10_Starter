# Lab 10 - Starter
[canny.io](https://cse110-lab10-nickehsani.canny.io/) page\
[]()\
[]()\
Explanation: For the second feature flag, instead of blue-background, I made a feature called btn-border, which changes the color of the "Press to Talk" button of the speech synthesizer. Instead of accessing the body and changing the entire background, I used querySelector to access the button and then access its style attribute, and of that I changed the borderColor attribute and changed its value to be purple. This happens 50% of the time when the flagValue variable is true. 