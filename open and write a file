print("파일 열고 쓰고 닫기")         # 특정경로 지정해서 파일 쓰고 닫기

f = open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt", "w")    # w 는 쓰기
f.write("hello i'm justin good to see you man~\n")

f = open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt", "a")    # w 는 쓰기
f.write("it's cool~!\n")
f.close()
f = open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt", "r")    # r 은 읽기
r = f.read()
print(r)

f.close()
f = open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt", "a")    # a 는 추가
f.write("brovo~!\n")
f = open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt", "r")
r = f.read()
print(r)

f.close()

with open("C:\\Users\\houhh\\OneDrive\\바탕 화면\\wow.txt","r", encoding = "utf-8") as f:    # with open 은 f.close 를 안써도 자동으로 닫히고
    while True:                                                                             # 아래처럼  f.readline()을 쓰게되면 한줄씩 읽어준다.
        read_data = f.readline()
        if not read_data:
            break
        print(read_data)                    # print(read_data, end="")    # 끝에 end=""를 붙이면 바로다음줄 줄간격을 한줄씩 붙여서 가져옴
print(f.closed)                                                # 하지만 붙이지 않았기에 띄어서 가져온다.

# print(f.closed) 를 쓰게되면 파일이 닫힌걸 확인가능하다
