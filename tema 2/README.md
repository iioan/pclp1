// nume: Ioan Teodorescu
// grupa: 313CB
Pentru Task-ul 1, citesc sirul cu cuvinte magice si prin intermediul functiei strtok, voi lua fiecare cuvant si il voi prelucra, in functie de tipul cuvantului (care incepe cu a, b, sau c). Dupa rezolvarea fiecarui caz, voi efectua miscarile din traseu, mai precis, in matricea M. 

Programul de la Task-ul 2 este impartit in 3 parti pentru fiecare tip de criptare. La cifrul Caesar, iau fiecare caracter si in functie de caz (litera mare, mica, sau cifra), decriptez cu cheia K, pana cand ajung la forma initiala a cuvantului. La Vigenère, folosesc o tehnica asemanatoare cifrului anterior, dar in cazul acesta, sunt mai multi K, in functie de fiecare litera din cheia, care se repeta in mod circular. Astfel, descrifrez fiecare caracter cu litera careia ii corespunde. Iar la Addition, incep cu eliminarea cifrelor de 0 de la inceputul fiecarui string (N1, N2), dupa care folosesc functia findsum. Aceasta incepe procesul de adunare de la capatul ambelor stringuri, luand caracter cu caracter, adaugand-ul in 'str' si pastrand cifra zecilor in carry (in cazul in care suma caracterelor va fii mai mare decat 10). 