# Stella1
print('籠內動物總隻數?')
num_animal=input()
print('籠內動物總腳數?')
num_feet=input()
num_chickens=((int(num_animal)*4-int(num_feet))//2)
num_rabbits=(int(num_animal)-int(num_chickens))
print('There are',str(num_rabbits), 'rabbits and', str(num_chickens), 'chickens in the cage.')

