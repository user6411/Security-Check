# Security-Check
#This program checks if you are eligible to enter the club or not.

age = int(input('How old are you?'))
if age >= 18:
    print('Good!')
else:
    print('Entrance not allowed. You are not old enough')

ticket_conf = str(input('Do you have a ticket? YES/NO')).lower().strip()
if ticket_conf == 'yes' and age >= 18:
    print('Go inside, you are welcome here') 

elif ticket_conf == 'yes' and age < 18:
    print('You are not welcome, you are not old enough')

else:
    print('Youre too young and you dont have a ticket')

