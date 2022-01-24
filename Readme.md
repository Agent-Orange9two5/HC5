Pentru examen va trebui sa pregatiti pe echipe de 3-4 studenti un program (aplicatie) creat intr-un limbaj de programare 
la alegere (NU excel, Mathcad, Mathlab, etc.). Acesta poate fi la alegere:

	
Un program care sa calculeze temperaturile intr-un element de anvelopa (utilizatorul sa poata alege daca este perete sau planseu, 
nr. de straturi, materiale dintr-o mica baza de date sau sa se poata defini materiale noi, conditii de temperatura) 
si sa realizeze graficul de temperatura. 

se citesc de la tastatura 2 temperaturi : ti si te 

se alege nr de straturi 
in functie de straturi, se face d1/l1, d2/l2 .... dn/ln => rezistente 
RT=RSI+ r1+ r2+...+rn + RSE 
(rsi si rse sunt 2 constante)

dupa se calculeaza theta-urile 

theta SI = ti - (rsi * (ti - te)) / rt;
theta 1 = ti - ((rsi + r1) * (ti - te)) / rt;
theta 2 = ti - ((rsi + r1 + r2) * (ti - te)) / rt;
theta 3 =  ti - ((rsi + r1 + r2 + r3) * (ti - te)) / rt;
theta 4 = ti - ((rsi + r1 + r2 + r3+ r4) * (ti - te)) / rt;
.........
theta SE = ti - ((rsi + r1 + r2 + r3 + r4+....+rn) * (ti - te)) / rt;

d1 = grosime strat 1 => avem 2 dungi paralele cu distante de x METRII intre ele 
... 

theta si - temperatura din interior pana la stratul 1 
theta 1 - temperatura in stratul 1 
..... 
theta se temperatura din statul n spre exterior 


