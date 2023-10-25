# Library
Programul meu  modelează o bibliotecă  cu cărți, fiecare carte cu câte un autor. Iată mai jos o scurtă prezentare a codului meu:
Am creat în programul meu 3 clase. 
Clasa Autor are ca atribute un nume privat  și anul nașterii.Prin urmare clasa oferă un constructor, un constructor de copiere, un operator de atribuire și un destructor.
Clasa carte conține un titlu și un autor, care este o instanță a clasei Autor. Similar cu clasa Autor, oferă un constructor, un constructor de copiere, un operator de atribuire și un destructor.
Clasa Biblioteca este cea  care conține o colecție de cărți.În aceasta avem un membru privat, colectie, care este un vector al obiectelor Carte. Clasa oferă metode pentru a adăuga o carte în bibliotecă, pentru a afișa toate cărțile din bibliotecă, dar și pentru a căuta o carte după titlu.
În funcția principală, sunt creați doi autori  și două cărți . Aceste cărți sunt apoi adăugate în bibliotecă (biblioteca). Cărțile bibliotecii sunt afișate folosind afiseazaCarti(), iar o anumită carte („Harry Potter”) este căutată și afișată folosind cautaCarteDupaTitlu().

Practic programul creează doi autori, „JK Rowling” și „JRR Tolkien”, cu anii de naștere respectivi.
Se creează două cărți, „Harry Potter” și „Stapanul inelelor”, fiecare asociată cu un autor, după care
o bibliotecă (biblioteca) și în care se adaugă cele două cărți.Apoi se afișează cărțile din bibliotecă, folosind afiseazaCarti()metoda.
Acesta caută o carte cu titlul „Harry Potter” folosind cautaCarteDupaTitlu(), iar dacă este găsită, afișează informațiile despre carte.
Ieșirea programului va afișa detaliile celor două cărți din bibliotecă și apoi va afișa cartea „Harry Potter” atunci când este căutată.
