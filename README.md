
SECURITY CHECK

age = int(input('How old are you?'))

ticket_conf = str(input('Do you have a ticket? YES/NO')).lower().strip()

if ticket_conf == 'yes' and age >= 18:
    print('Go inside, you are welcome here') 


elif ticket_conf == 'yes' and age < 18:
    print('You are not welcome, you are not old enough')


elif ticket_conf == 'no' and age >= 18:
    print('You need a ticket to enter')

else:
    print('Youre too young and you dont have a ticket')
    




    

    









