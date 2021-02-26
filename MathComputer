#超級計算機
#版本:Formal 13.1.7.2.0 正式版
#開發者:王建葦
#所有權人:王建葦
#程式架構:Python4
#****版權所有****
print("超級計算機")
print("版本:Formal 13.1.7.2.0 正式版")
print("開發者:王建葦")
print("所有權人:王建葦")
print("程式架構:Python4")
print("****版權所有****")
class Input():
    def One(s1,s2):
        x = eval(input(s1+s2+" "))
        return x
    def Two_alone(s1,s2):#單獨
        x =eval(input(s1+"= "))
        y =eval(input(s2+"= "))
        return x ,y
class Math():
    def log(s1,s2):
        import math
        x=math.log10(Input.One(s1,s2))
        return x
    def distance():
        import math
        x1 ,y1 = map(eval,input("x1 ,y1 (使用空白鍵將數值分開) = ").split())
        x2 ,y2 = map(eval,input("x2 ,y2 (使用空白鍵將數值分開) = ").split())
        xy=math.pow(math.pow(x2-x1,2)+math.pow(y2-y1,2),0.5)
        return xy
    def two():
        x1 ,y1 = map(eval,input("x1 ,y1 (使用空白鍵將數值分開) = ").split())
        x2 ,y2 = map(eval,input("x2 ,y2 (使用空白鍵將數值分開) = ").split())
        twox=(x1+x2)/2
        twoy=(y1+y2)/2
        return twox,twoy
    def m():
        x1 ,y1 = map(eval,input("x1 ,y1 (使用空白鍵將數值分開) = ").split())
        x2 ,y2 = map(eval,input("x2 ,y2 (使用空白鍵將數值分開) = ").split())
        m=(y2-y1)/(x2-x1)
        return m
    def mathpow_1(s):
        import math
        x = Input.One(s)
        mathpow=math.pow(x ,0.5)
        return mathpow
    def mathpow_2(s1,s2):
        import math
        x ,y = Input.Two_alone(s1, s2)
        mathpow=math.pow(x ,y)
        return mathpow
errorchake=None
user = None
password = None
system = None
function = None
userchake = None
userreturn = ""
erroruserpassword = None
while(True):
    try:
        import sys
        print("*功能選單 : ")
        print("""*(1)常用對數 
 (2)次方
 (3)根號
 (4)兩點距離
 (5)兩點斜率
 (6)兩點中點
 (7)離開""")
        function=Input.One("*請選擇功能" ,":")
        if(function == 1):
            print("Log:",Math.log("底數" ,"="))
        elif(function == 2):
            print("值 : ",Math.mathpow_2("底數","指數"))
        elif(function == 3):     
            print("值:",Math.mathpow_1("底數" ,"="))
        elif(function == 4):
            print("兩點距離:",Math.distance())
        elif(function == 5):        
            print("斜率: ",Math.m())
        elif(function == 6):
            print("兩點中點 : ",Math.two())
        elif(function == 7):
            while(True):
                exitcode=int(input("您確定要離開嗎？ (1)是 (2)否 : "))                   
                if(exitcode == 1):
                    system=True
                    print()
                    print("感謝您使用本系統")
                    sys.exit(None)
                elif(exitcode == 2):
                    break
                else:
                    print("--------------------------------ERROR--------------------------------")
                    print("                       錯誤類型：您輸入的選項錯誤")
        elif(function == 9453 ):
            system=True
            sys.exit("程式結束")
        else:
            print("--------------------------------ERROR--------------------------------")
            print("                       錯誤類型：您輸入的選項錯誤")
            errorchake=True   
        print("*********************************************************************")1
    except:                
        if(system == True and function == 9453):
            sys.exit()
        if(system == False or system == None):
            print()
            print("--------------------------------ERROR--------------------------------")
            print("                          錯誤類型：參數錯誤")
            print()
        else:
            print("                             System End")
            print("*********************************************************************")
            print()
            sys.exit("程式結束")
#程式結束
