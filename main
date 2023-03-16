#  진수 변환기 1.0.0 버전
# made by everytime 12 
import sys
a=True
while(a==True):
    b = 0
    c = 0
    d = 0
    f = 0
    g = 0
    print("해석에 필요한 타입 정수형으로 입력해주세요. (2,8,10,16진수) :")
    d=int(input())
    if(d==2):
        print("2진수를 입력하세요: 0b")
        b = int(input(),2)
        print(b)
    elif(d==8):
        print("8진수를 입력하세요:0o")
        b=int(input(),8)
        print(b)
    elif(d==10):
        print("양의정수를 입력해주세요 :(-1을 입력시 종료됩니다.)")
        b = int(input())
        if (b == -1 ):
            a==False
            break
        elif(b<0 and b>-1):
            print("잘못된 입력을 감지하였습니다.")
        elif(b<-1):
            print("잘못된 입력을 감지했습니다.")
        elif(b>=0):
            c=bin(b)
            g=oct(b)
            f=hex(b)
            print("2진수" , c , "8진수", g ,"16진수", f)
    elif(d==16):
        print("16진수를 입력하세요: 0x")
        b=int(input(),16)
        print(b)
