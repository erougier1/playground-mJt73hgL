# Un premier essai
Affecter 1 à la variable a
```python runnable
from random import sample

de = [1,2,2,3,3,3]
resultat1 = 0
resultat2 = 0
resultat3 = 0
nb_lancers = eval(input('Nombre de lancers : '))

for i in range(nb_lancers):
	lancer = sample(de,1)[0]
	if lancer == 1:
		resultat1 = resultat1 + 1
	if lancer == 2:
		resultat2 = resultat2 + 1
	if lancer == 3:
		resultat3 = resultat3 + 1
	
print('Fréquence de 1 : ', resultat1/nb_lancers)
print('Fréquence de 2 : ', resultat2/nb_lancers)
print('Fréquence de 3 : ', resultat3/nb_lancers)	

```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
