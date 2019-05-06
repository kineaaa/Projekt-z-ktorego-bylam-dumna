# Projekt-z-ktorego-bylam-dumna

def pobierz_dane(liczba_cyfr):
    lista=[]
    for i in range(liczba_cyfr):
        podaj=int(input("Podaj cyfry: "))
        lista.append(podaj)
    return lista

nliczb=int(input("podaj z ilu cyf ma sie skladac lista: "))
wynik=pobierz_dane(nliczb)
print(wynik)
