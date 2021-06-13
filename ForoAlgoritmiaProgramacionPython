
print("              -------------------------")
print("              | LA RUTA MAS EFICIENTE |")
print("              -------------------------")

print("""
	| Debido a la pandemia una empresa de transporte quiere resolver el    | 
	| inconveniente que, dado cuatro localidades a recorrer, debe hallar   |
	| la ruta que le permita llegar todas las localidades una exclusiva    |
	| vez, dando por seguro que la distancia que recorra sea mínima. 	   |
	| El transporte no recorre la misma ruta todos los días por lo que la  | 
	| distancias entres los lugares varia.								   |
	|																	   |
	| Por ejemplo, se tiene este conjunto de puntos a recorrer con sus     |
	| respectivas distancias.											   |
	|																	   |
	| Para Ud. ¿Cuál sería el algoritmo solución y código fuente en Python |
	| si los valores de las distancias varían?							   |
	""")


 
print("						      B       ")
print("						     /|\      ")
print("						    / | \     ")
print("						   /  |  \    ")
print("						  F --|-- J   ")
print("						   \  |  /    ")
print("						    \ | /     ")
print("						     \|/      ")
print("						      A       ")
 
print("")
print("")
print("\nIngresa las distancias de: ")
d_BA = int(input("-> B a A: "))
d_BJ = int(input("-> B a J: "))
d_AJ = int(input("-> A a J: "))
d_FB = int(input("-> F a B: "))
d_FJ = int(input("-> F a J: "))
d_FA = int(input("-> F a A: "))


 
total = 0 #El total cominza con "0", porque aun no se recorre.
 
print("\nIndicar punto de inicio:")
print("-----------------------------------------------")
print("\nOJO, indicar con letra mayuscula")
print("-----------------------------------------------")
inicio = input("\n-> F / B / J / A: ")


"""Seguidamente las distancias se comparan, para conocer la distancias optimas, con 
las sentencias if y elif"""
 
#-----------INICIO A----------------------
 
if inicio == "A":
    if d_FA <= d_BA and d_FA <= d_AJ and d_FJ <= d_FB:
        total = d_FA + d_FJ + d_BJ + d_BA
        print("\nRuta a seguir: A -> F -> J -> B -> A")
 
    elif d_AJ <= d_BA and d_AJ <= d_FA and d_FJ <= d_BJ:
        total = d_AJ + d_FJ + d_FB + d_BA
        print("\nRuta a seguir: A -> J -> F -> B -> A")
 
    elif d_BA <= d_FA and d_BA <= d_AJ and d_FB <= d_BJ:
        total = d_BA + d_FB + d_FJ + d_AJ
        print("\nRuta a seguir: A -> B -> F -> J -> A")
 
    elif d_BA <= d_FA and d_BA <= d_AJ and d_BJ <= d_FB:
        total = d_BA + d_BJ + d_FJ + d_FA
        print("\nRuta a seguir: A -> B -> J -> F -> A")
 
    elif d_FA <= d_BA and d_FA <= d_AJ and d_FB <= d_FJ:
        total = d_FA + d_FB + d_BJ + d_AJ
        print("\nRuta a seguir: A -> F -> B -> J -> A")
 
    elif d_AJ <= d_BA and d_AJ <= d_FA and d_BJ <= d_FJ:
        total = d_AJ + d_BJ + d_FB + d_FA
        print("\nRuta a seguir: A -> J -> B -> F -> A")


#-----------INICIO F----------------------

if inicio == "F":
    if d_FB <= d_FJ and d_FB <= d_FA and d_BA <= d_BJ:
        total = d_FB + d_BA + d_AJ + d_FJ
        print("\nRuta a seguir: F -> B -> A -> J -> F")
 
    elif d_FA <= d_FJ and d_FA <= d_FB and d_BA <= d_AJ:
        total = d_FA + d_BA + d_BJ + d_FJ
        print("\nRuta a seguir: F -> A -> B -> J -> F")
 
    elif d_FJ <= d_FB and d_FJ <= d_FA and d_BJ <= d_AJ:
        total = d_FJ + d_BJ + d_BA + d_FA
        print("\nRuta a seguir: F -> J -> B -> A -> F")
 
    elif d_FJ <= d_FB and d_FJ <= d_FA and d_AJ <= d_BJ:
        total = d_FJ + d_AJ + d_BA + d_FB
        print("\nRuta a seguir: F -> J -> A -> B -> F")
 
    elif d_FB <= d_FJ and d_FB <= d_FA and d_BJ <= d_BA:
        total = d_FB + d_BJ + d_AJ + d_FA
        print("\nRuta a seguir: F -> B -> J -> A -> F")
 
    elif d_FA <= d_FJ and d_FA <= d_FB and d_AJ <= d_BA:
        total = d_FA + d_AJ + d_BJ + d_FB
        print("\nRuta a seguir: F -> A -> J -> B -> F")


#-----------INICIO B----------------------       
 
if inicio == "B":
    if d_FB <= d_BA and d_FB <= d_BJ and d_FJ <= d_FA:
        total = d_FB + d_FJ + d_AJ + d_BA
        print("\nRuta a seguir: B -> F -> J -> A -> B")
 
    elif d_BJ <= d_BA and d_BJ <= d_FB and d_FJ <= d_AJ:
        total = d_BJ + d_FJ + d_FA + d_BA
        print("\nRuta a seguir: B -> J -> F -> A -> B")
 
    elif d_BA <= d_FB and d_BA <= d_BJ and d_AJ <= d_FA:
        total = d_BA + d_AJ + d_FJ + d_FB
        print("\nRuta a seguir: B -> A -> J -> F -> B")
 
    elif d_BA <= d_FB and d_BA <= d_BJ and d_FA <= d_AJ:
        total = d_BA + d_FA + d_FJ + d_BJ
        print("\nRuta a seguir: B -> A -> F -> J -> B")
 
    elif d_BJ <= d_BA and d_BJ <= d_FB and d_AJ <= d_FJ:
        total = d_BJ + d_AJ + d_FA + d_FB
        print("\nRuta a seguir: B -> J -> A -> F -> B")
 
    elif d_FB <= d_BA and d_FB <= d_BJ and d_FA <= d_FJ:
        total = d_FB + d_FA + d_AJ + d_BJ
        print("\nRuta a seguir: B -> F -> A -> J -> B")


#-----------INICIO J----------------------        
 
if inicio == "J":
    if d_BJ <= d_FJ and d_BJ <= d_AJ and d_BA <= d_FB:
        total = d_BJ + d_BA + d_FA + d_FJ
        print("\nRuta a seguir: J -> B -> A -> F -> J")
 
    elif d_AJ <= d_FJ and d_AJ <= d_BJ and d_BA <= d_FA:
        total = d_AJ + d_BA + d_FB + d_FJ
        print("\nRuta a seguir: J -> A -> B -> F -> J")
 
    elif d_FJ <= d_BJ and d_FJ <= d_AJ and d_FB <= d_FA:
        total = d_FJ + d_FB + d_BA + d_AJ
        print("\nRuta a seguir: J -> F -> B -> A -> J")
 
    elif d_FJ <= d_BJ and d_FJ <= d_AJ and d_FA <= d_FB:
        total = d_FJ + d_FA + d_BA + d_BJ
        print("\nRuta a seguir: J -> F -> A -> B -> J")
 
    elif d_BJ <= d_FJ and d_BJ <= d_AJ and d_FB <= d_BA:
        total = d_BJ + d_FB + d_FA + d_AJ
        print("\nRuta a seguir: J -> B -> F -> A -> J")
 
    elif d_AJ <= d_FJ and d_AJ <= d_BJ and d_FA <= d_BA:
        total = d_AJ + d_FA + d_FB + d_BJ
        print("\nRuta a seguir: J -> A -> F -> B -> J")


 
 #Sumatoria total del recorrido optimo

print("Ruta eficiente:", total, "km. ")
