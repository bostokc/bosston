print("자판기 만들기")


i = input("What kind beverage do you want?:\n\n1.Cola 2.Sprite 3.OrangeJuice 4.Water")

Money = int()   # 돈을 미리 입력해놓으면 int로 정수로 변환할 필요 없이 되지만
                # Money = [] 리스트로 해놓을 수도 잇지만 아래처럼 Money 를 정수로 int_money = int(Money)바꿔줘야한다.
cola = 1000
sprite = 1000
orangejuice = 1200

if i == "1":
    Money = input("Please press put your money:")
    int_money = int(Money)
    if int_money < cola:
        print("Not enough money.")
    elif int_money > cola:
        print("Your cola is coming, your change is %d won" %(int_money - cola))

if i == "2":
    Money = input("Please press put your money:")
    money = int(Money)
    if money < sprite:
        print("Not enough money.")
    elif money > sprite:
        print("Your sprite is coming, your change is %d won" %(money - sprite))   # 아래도 위와같이 변환해보시오~


if i == "3":
    q = input("The price of orange juice is 1200 because it's made of real fresh orange, are you sure to continue?:")
    if q == "y":
        Money = input("Please put your money in:")
        money = int(Money)
    if money < orangejuice:
        print("돈이 부족합니다.")
    elif money > orangejuice:
        print("Your orangejuice is coming, your change is %d won" %(money - orangejuice))

if i == "4":
    print("Please press put your money:")
    if Money < water:
        print("돈이 부족합니다.")
    elif Money > water:
        print("Your water is coming, your change is %d won" %(Money - water))

print("Thank you and have good day~")
