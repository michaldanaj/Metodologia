# Metodologia


1.  Wiemy jak wszystkie poniższe przekształcenia zamienić na kod w:

    * SAS
    * Java

1.  Przekształcenia zmiennych

    1.  Linearyzacj zmiennych

        * Aproksymacja lokalna funkcjami stopnia 0
        * Funkcja sklejana, wielomianami stopnia 1
        * Przekształcenia funkcjami ciągłymi: boxa-coxa, log

    1.  Braki danych
        * Podstawienie stałej wartości za wszystkie braki danych
        * Wygenerowanie dummy variable dla braków
        * Oba naraz, lub tylko pierwsze z nich jeśli podstawienie jest zrobione tak, że nie potrzeba tego robić

    1.  Wartości spoza zakresu próby uczącej/dyskretyzacji
        * Zastąpienie wartości najbliższą jaka była na próbie uczącej
 
    1.  Mapowanie
        * Mapowanie jednych wartości na drugie: implementacja IF-a

1.  Modele:
    * Regresja logistyczna
    * Drzewo
    * Las
    * Boostingi


