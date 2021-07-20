# program-to-find-the-population-of-states-in-Nigeria-

# Get the population of given states in nigeria 

statesInNigeria = {'Abia':'172828', 'Benue':'238930', 'Cross River': '30212',\
                   'Brono': '1612', 'Delta': '1175', 'Ebonyi': '1726',\
                    'Edo': '1179', 'Ekiti': '1729', 'Enugu': '1730',\
                    'Gombe': '1731', 'Imo': '1732', 'Jigawa': '1733',\
                    'Kaduna': '1734', 'Kano': '1735', 'Katsina': '1736',\
                    'Kebbi': '1737', 'Kogi': '1738', 'Kwara': '1739',\
                    'Lagos': '1740', 'Nasarawa': '1741', 'Niger': '1742',\
                    'Ogun': '1743', 'Ondo': '1744', 'Osun': '1745',\
                    'Oyo': '1746', 'Plateau': '1747', 'Rivers': '1748',\
                    'Sokoto': '1749', 'Taraba': '1750', 'Yobe': '1751',\
                    'Zamfara': '1752'}
while True:
    userState = input('Enter the state in Nigeria: ')
    if userState == '':
        break

    if userState in statesInNigeria:
        population = statesInNigeria[userState]
        print('The population of', userState, 'is', population)


        
    
