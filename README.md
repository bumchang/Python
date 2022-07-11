# Python 1일차
a = 3
b = 3
print(a+b)

print(a*b)
print(a**b)
print(7%3)
print(7//4)

a = "python"
print(a*2)

a = "Life is too short, You need Python"
print(a[3])

print(a[-2])

b = print(a[0] + a[1] + a[2] + a[3])

print(a[0:5])
print(a[19:]) # 시작 번호부터 끝 번호까지 뽑아냄
print(a[:17]) # 번호를 생략하면 문자열의 처음부터 끝 번호까지 뽑아냄
print(a[:]) # 전체 모두 뽑아냄

a = "20010331Rainy"
data = a[:8]
weather = a[8:]
print(data)
print(weather)

# 문자열 포매팅
print("I eat %d apples." %3)
print("I eat %s apples." %"five")

# 숫자를 넣기 위해서는 %d, 문자를 넣기 위해서는 %s

# 2개 이상의 값 넣기
number = 10
day = "three"
print("I ate %d apples. so i was sick for %s days." %(number, day))


a = "hobby"
print(a.count('b'))

a = "python is best choice"
print(a.find('b'))

a = ","
print(a.join('abcd'))
a = "hi"
print(a.upper())
print(a.lower())
a="hi"
print(a.lstrip())
print(a.rstrip())

a = "life is too short"
print(a.replace("life", "your leg"))

a = "life is too short"
print(a.split()) # 공백 기준으로 나눔
a = "a:b:c:d"
print(a.split(':'))

print("I eat {0} apples".format(3))

number = 3
print("I eat {0} apples".format(number))
print("I eat {0} apples. so i was sick for {1} days.".format(number, day))

print("{0:=^10}".format("hi"))
print("{0:!<10}".format("hi"))
print("{{and}}".format())

odd = [1, 3, 5, 7, 9]
a = [1, 2, 3]
print(a)

a= [1,2 ,3]
b = [4, 5, 6]
print(a+b)

print(a*3)

a[2] = 4
print(a)
a[1:3] = []
print(a)

a = [1, 2, 3]
a.append(4)
print(a)

a.append([5, 6])
print(a)

a = [1, 4, 3, 2]
a.sort()
print(a)

a = ['a', 'c', 'b']
a.reverse()
print(a)
a = [1, 2, 3]
print(a.index(3))
a = [1, 2, 3]
a.insert(0, 4)
print(a) #a[0] 위치에 4를 넣으세요
a = [1, 2, 3, 1, 2, 3]
a.remove(3)
print(a)

a = [1, 2, 3]
a.pop()
print(a) # pop()은 리스트의 맨 마지막 요소를 돌려 주고 그 요소는 삭제하는 함수
a = [1, 2, 3]
a.pop(1)
print(a)

a = [1, 2, 3]
a.extend([4, 5])
print(a)
