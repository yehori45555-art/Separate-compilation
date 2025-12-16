# Separate-compilation
Є три файли: one.cpp, two.cpp та three.cpp.
Ми компілюємо їх за допомогою таких команд:

'g++ -c one.cpp'
'g++ -c two.cpp'
'g++ -c three.cpp'

В результаті ми отримуємо три об'єктні файли: one.o, two.o та three.o.
Щоб створити остаточну виконувану програму, я виконав таку команду:

'''g++ -c one.o two.o three.o -o finalprogram'''
