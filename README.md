# HelloState
# a house buying software using python


yrs=int(input('Enter your yearly salary in $ : '))

elg=100000
price=1000000

Y_or_N=(input('''Do you have a crminal record?
'Y' for Yes and 'N' for No: '''))

if Y_or_N.upper()=='N' and yrs<=elg:
    print('You can Buy the house')
    down_payment=.1*price
    print(f'Your Downpayment is : {down_payment}')

elif Y_or_N.upper() == 'Y':
    print("You can't buy the house")

elif yrs>elg:
    down_payment=.2*price
    print(f'Your downpayment is: {down_payment}')
