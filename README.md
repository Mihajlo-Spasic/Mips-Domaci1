# Mihajlo-Spasic-MIPS-Domaci1
Mihajlo Spasic 632-2021
RTSI

Zadatak domaceg:
NapravitiSTM32 konfiguraciju sa jednom LED diodom koja se ukljucuje i koja je povezana prema sledecim uslovima:

Port diode zavisi od kolicine broja suglasnika i samoglasnika, u slucaju da je br samoglasnika u imenu i prezimenu veci koristimo Port A u suprotnom Port B, ako su jednaki Port C. (Kod mene je slucaj Porta B)
Pin diode se bira prema sumi slova imena i prezimena po modulu 6 ( Mihajlo Spasic (7+6 = 13 | 13 % 6 = 1 | Uzimamo prvi pin) 

Dioda radi na dva takta ciji rad je specifiran prema:
1. Takt: Sirina impula je broj ms jedank broju slova u imenu : 7ms
         Sirina pauze je broj ms jedank broju slova u prezimenu : 6ms
2. Takt: Sirina impula je broj ms jedank broju slova u prezimenu : 6ms
         Sirina pauze je broj ms jedank broju slova u imenu : 7ms
   
[![Demonstracija projekta  - Click me ]()](https://youtu.be/ApsiCL7Y_HI)
