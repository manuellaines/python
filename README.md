# recherche lineaire de t'test' dans le tableau 'la'
la = [3, 6, 5, "test", "spam", 10.00, 2+8j]
i=0
while i<len(la) :
	if la[i]=="test":
		print('test')
		i=len(la)
	else:
		i=i+1
