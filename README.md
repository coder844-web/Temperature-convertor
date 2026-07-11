print("_______________________________________________________________________________________________________")
print("hello ! Dear user this is temperature converter. Chose any action you want to perform : ")

import time 

while True :
    print("-------------------------------------------------------------------------------------------------------------")
    time.sleep(2)
    print(" 1) celcius to farhenheit converter \n 2) farhenheit to celcius convertor \n 3) EXIT ")

    x= int(input(" Enter your choice : "))


    if x== 1 :
        def convc_f(c):
            print(f"{c} celcius is {c*9/5 + 32} farheneit ")

        n = int(input("enter the value in degree celcius : "))
        convc_f(n)

    elif x== 2:
        def convf_c(f) :
            print(f"{f} farhenheit is {5/9*(f-32)} celcius ")

        a= int(input("enter the value in degree farhenheit : "))
        convf_c(a)
        
    elif x==3 :
        print("THANKU YOU !")
        break

    else :
        print("Please Enter a valid choice")
