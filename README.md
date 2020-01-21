import winsound

import time

def DOTBeepSoun():

    freq = 800
    duration = 400
    winsound.Beep(freq, duration)
    return
def DASHBeepSoun():

    freq = 800
    duration = 2500
    winsound.Beep(freq, duration)
    return

def LettersANDnumbers():

    def A():
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def B():
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def C():
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def D():
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def E():
        DOTBeepSoun()
        return

    def F():
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def G():
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def H():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def I():
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def J():
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def K():
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def L():
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def M():
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def N():
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def O():
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def P():
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def Q():
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def R():
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def S():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def T():
        DASHBeepSoun()
        return

    def U():
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def V():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def W():
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def X():
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def Y():
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def Z():
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def num1():
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def num2():
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def num3():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def num4():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def num5():
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def num6():
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun
        DOTBeepSoun()
        return

    def num7():
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    def num8():
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return
    def num9():
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        return

    def num0():
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return

    def dot():
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        return

    def colon():
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        return
    def questionmark():
        DOTBeepSoun()
        DOTBeepSoun()
        DASHBeepSoun()
        DASHBeepSoun()
        DOTBeepSoun()
        DOTBeepSoun()
        return

    try:
        UserInput = input(" \nEnter text which you want to transfer --->\n ")
    except :
        print(" This can not be transfered to MORS code")
        time.sleep(3)
        LettersANDnumbers()
    else:
        for i in UserInput:
            if i == "a" or i == "A":
                print("\na/A >>>     .- ")
                A()

            elif i == "b" or i == "B":
                print("\nb/B >>>     -... ")
                B()

            elif i == "c" or i == "C":
                print("\nc/C >>>     -.-. ")
                C()

            elif i == "d" or i == "D":
                print("\nd/D >>>      -.. ")
                D()

            elif i == "e" or i == "E":
                print("\ne/E >>>      . ")
                E()

            elif i == "f" or i == "F":
                print("\nf/F >>>      ..-. ")
                F()

            elif i == "g" or i == "G":
                print("\ng/G >>>      --. ")
                G()

            elif i == "h" or i == "H":
                print("\nh/H >>>      .... ")
                H()

            elif i == "i" or i == "I":
                print("\ni/I >>>      .. ")
                I()

            elif i == "j" or i == "J":
                print("\nj/J >>>      .--- ")
                J()

            elif i == "k" or i == "K":
                print("\nk/K >>>       -.- ")
                K()

            elif i == "l" or i == "L":
                print("\nl/L >>>       .-.. ")
                L()

            elif i == "m" or i == "M":
                print("\nm/M >>>       -- ")
                M()

            elif i == "n" or i == "N":
                print("\nn/N >>>       -. ")
                N()

            elif i == "o" or i == "O":
                print("\no/O >>>       --- ")
                O()

            elif i == "p" or i == "P":
                print("\np/P >>>       .--. ")
                P()
            elif i == "q" or i == "Q":
                print("\nq/Q >>>       --.- ")
                Q()

            elif i == "r" or i == "R":
                print("\nr/R >>>       .-. ")
                R()

            elif i == "s" or i == "S":
                print("\ns/S >>>       ... ")
                S()

            elif i == "t" or i == "T":
                print("\nt/T >>>       - ")
                T()

            elif i == "u" or i == "U":
                print("\nu/U >>>       ..- ")
                U()

            elif i == "v" or i == "V":
                print("\nv/V >>>       ...- ")
                V()

            elif i == "w" or i == "W":
                print("\nw/W >>>       .-- ")
                W()

            elif i == "x" or i == "X":
                print("\nx/X >>>       -..- ")
                X()

            elif i == "y" or i == "Y":
                print("\ny/Y >>>       -.-- ")
                Y()

            elif i == "z" or i == "Z":
                print("\nz/Z >>>       --.. ")
                Z()

            elif i == "1":
                print("\n1 >>>       .---- ")
                num1()

            elif i == "2":
                print("\n2 >>>        ..--- ")
                num2()

            elif i == "3":
                print("\n3 >>>        ...-- ")
                num3()

            elif i == "4":
                print("\n4 >>>        ....- ")
                num4()

            elif i == "5":
                print("\n5 >>>        ..... ")
                num5()

            elif i == "6":
                print("\n6 >>>        -.... ")
                num6()

            elif i == "7":
                print("\n7 >>>        --... ")
                num7()

            elif i == "8":
                print("\n8 >>>        ---.. ")
                num8()

            elif i == "9":
                print("\n9 >>>        ----. ")
                num9()

            elif i == "0":
                print("\n0 >>>        ----- ")
                num0()

            elif i == ".":
                print("\n. >>>        .-.-.- ")
                dot()

            elif i == ",":
                print("\n, >>>        --..-- ")
                colon()

            elif i == "?":
                print("\n? >>>        ..--.. ")
                questionmark()


    time.sleep(2)
    print(" \n<<<<<<<< If you have another text to transfer , Press y /// If not press n >>>>>>>> ")
    UserDeci=input(" You answer : ")
    if UserDeci == "y":
        LettersANDnumbers()
    else:
        print(" \n\n>> Thank you for using this program , the program will close :) . ")
        time.sleep(5)

    return
LettersANDnumbers()


