# MORScode
#implementation of MORS code in python

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


    UserInput = input(" \nEnter text which you want to transfer --->\n ")
    for i in UserInput:
        if i == "a":
            print(" .- ")
            A()

        elif i == "b":
            print(" -... ")
            B()

        elif i == "c":
            print(" -.-. ")
            C()

        elif i == "d":
            print(" -.. ")
            D()

        elif i == "e":
            print(" . ")
            E()

        elif i == "f":
            print(" ..-. ")
            F()

        elif i == "g":
            print(" --. ")
            G()

        elif i == "h":
            print(" .... ")
            H()

        elif i == "i":
            print(" .. ")
            I()

        elif i == "j":
            print(" .--- ")
            J()

        elif i == "k":
            print(" -.- ")
            K()

        elif i == "l":
            print(" .-.. ")
            L()

        elif i == "m":
            print(" -- ")
            M()

        elif i == "n":
            print(" -. ")
            N()

        elif i == "o":
            print(" --- ")
            O()

        elif i == "p":
            print(" .--. ")
            P()
        elif i == "q":
            print(" --.- ")
            Q()

        elif i == "r":
            print(" .-. ")
            R()

        elif i == "s":
            print(" ... ")
            S()

        elif i == "t":
            print(" - ")
            T()

        elif i == "u":
            print(" ..- ")
            U()

        elif i == "v":
            print(" ...- ")
            V()

        elif i == "w":
            print(" .-- ")
            W()

        elif i == "x":
            print(" -..- ")
            X()

        elif i == "y":
            print(" -.-- ")
            Y()

        elif i == "z":
            print(" --.. ")
            Z()

        elif i == "1":
            print(" .---- ")
            num1()

        elif i == "2":
            print(" ..--- ")
            num2()

        elif i == "3":
            print(" ...-- ")
            num3()

        elif i == "4":
            print(" ....- ")
            num4()

        elif i == "5":
            print(" ..... ")
            num5()

        elif i == "6":
            print(" -.... ")
            num6()

        elif i == "7":
            print(" --... ")
            num7()

        elif i == "8":
            print(" ---.. ")
            num8()

        elif i == "9":
            print(" ----. ")
            num9()

        elif i == "0":
            print(" ----- ")
            num0()

        elif i == ".":
            print(" .-.-.- ")
            dot()

        elif i == ",":
            print(" --..-- ")
            colon()

        elif i == "?":
            print(" ..--.. ")
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


