# 4.12-Automobile-service-invoice
Zybook partner project
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12')
total1 = 0
total2= 0
print()

service_1 = input('Select first service:\n')
service_2 = input('Select second service:\n')

print()

print("Davy's auto shop invoice")
print()

if service_1 == 'Oil change':
    total = 35
    print('Service 1: Oil change, $35')
elif service_1 == 'Tire rotation':
    total = 19
    print('Service 1: Tire rotation, $19')
elif service_1 == 'Car wash':
    total = 7
    print('Service 1: Car wash, $7')
elif service_1 == 'Car wax':
    total = 12
    print('Service 1: Car wax, $12')
else:
    print('Service 1: No service')
    
if service == 'Oil change':
    total2 = 35
    print('Service 2: Oil change, $35')
elif service_2 =='Tire rotation':
    total2 = 19
    print('Service 2: Tire rotation, $19')
elif service_2 =='Car wash':
    total2 = 7
    print('Service 2: Car wash, $7')
elif service_2 =='Car wax':
    total2 = 12
    print('Service 2: Car wax, $12')
else:
    print('Service 2: No service')
print()
print('Total: $'+ str(total + total2))
