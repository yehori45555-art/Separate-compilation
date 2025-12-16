# Separate-compilation
Є три файли: frstfile.cpp, scndfile.cpp та thrdfile.cpp.
Ми компілюємо їх за допомогою таких команд:

g++ -c frstfile.cpp
g++ -c scndfile.cpp
g++ -c thrdfile.cpp

В результаті ми отримуємо три об'єктні файли: frstfile.o, scndfile.o та thrdfile.o.
Щоб створити остаточну виконувану програму, я виконав таку команду:

g++ -c frstfile.o scndfile.o thrdfile.o -o finalprogram
