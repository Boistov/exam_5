## RULES:
## RULES:
> No interner, no help to each other!
> Send the exam to github
> You have 2 hours only

### 1 Question
Дар бораи рекурсия нависед.
recursiya ain funcsiya e ki dar daruni khudaash davr zadan megirad to zamone kii ba yak natija rasad 
ba monadnandi loops va pesh loops ho in recusiya paydo shudagi bud va baroi susut kor kardanash ziyod istifoda namebarand recursiyaro . 

### 2 Question
Closure(3амыкания) - ро бо мисолҳо фаҳмонед.
closure in dastrasi paydo kardan ba taghiryobandahoi daruni function bad az on ki fucntion ba itmom merasad . Yane badi ba anjom rasitani function metavonem taghiryobandahoin daruni functiona istifoda barem. rangi nested function niz kor mekunad.





### 3 Question
Контейнерҳоро ба хотир оварда онҳоро нависед. 
canteinerho in ba monandi array dar C++ meboshand . va dar injo boz namud mode va methodhoi khudro dorand. va dar injo boz ivaz shavanda meshavand va invaznashavanda muttable and immutible 
list
tupl
dictionary
set
string
Сет қавсҳои фигурни дорад, лист қавси чоркунҷа. Фарқи дигар ин ки мо ба элементҳои лист даст ёфта метонем. Неки ба элементҳои сет не. Чунки сет уникални аст ва ҳар бор якум элемента чизи дигар нишон медиҳад


Сет уникални индекс дорад. Дикшнерия худамон индекс мегузорем. Фарқияти асосишон ҳамин
inaz nashavandaho tuple,dictionaary
ivazshavandaho list,set,string meboshand,
list sust kor mekunad baroi on kii method bisyor dorand tuple boshad tez kor mekunad ivaznashavanda hast va method kam dorad




### 4 Question
Дар бораи lambda expression ва list comprehension нависед.
lambda in da programai computeri ki kategoriyai kodhoro doro meboshad

### 5 Question
Кадом методҳои модули datetime ва randome - ро медонед. Бо мисолҳо фаҳмонед.
.isoformat
.


### 1 Task
Write a Python program to insert an element at a specified position into a given list.
Напишите программу Python для вставки элемента в указанную позицию в заданный список.
[1, 1, 2, 3, 4, 4, 5, 1]
# input
    Enter an element: Sorbon
    Index: 3
# output
    [1, 1, 2, "Sorbon", 3, 4, 4, 5, 1]


my_list = [1, 1, 2, 3, 4, 4, 5, 1]

a = input("name")
b = int(input("number"))
my_list.insert(b, a)

print(my_list)





### 2 Task
Write a Python program to convert a list of multiple integers into a single integer.
Напишите программу на Python для преобразования списка из нескольких целых чисел в одно целое число.
# input
    Sample list: [11, 33, 50]
# output
    Expected Output: 113350


ansver:
my_list = input()
n = my_list.split()
total = int(''.join([str(num) for num in n))
print(total)


### 3 Task
Create a python program to read line number N from the following file.
Создайте программу Python для чтения строки номер N из следующего файла.
my_file.txt -> Hello world
               TEST
               Tajikistan
               An apple
# input
    3
# otput
    Tajikistan
name = "my_file.txt"
num = input()

with open(name) as file:
    for n, line in enumerate(file):
        if n + 1 == i:
            print(i, line)
            break
    else:
    print(i)


### 4 Task
Create a python program to generate a random password of the specified length.
Создайте программу Python для создания случайного пароля указанной длины.
# input
    Enter the desired password length: 12
# output
    Generated password: Xy#7pLm$9oR5
















### 5 Task
Build a program that converts currency from one denomination to another.
Создайте программу, которая конвертирует валюту одного номинала в другой.
# input
    Enter the amount in TJS: 1
# output
    Rub -> 0.1193
    USD -> 10.8656
    EUR -> 11.7837
    UZ_SUM -> 0.0856

ansver

exchange_rates = {
    "Rub": 0.1193,
    "USD": 10.8656,
    "EUR": 11.7837,
    "UZ_SUM": 0.0856
}
tj = float(input())

for cur, n in exchange_rates.items():
       i = tj * n
    print(i)









### 6 Task
Given a natural number N, find the sum of the numbers 1+1/1!+1/2!+1/3!+...+1/N!. The number of actions should be proportional to N.
По данному натуральному числу N найдите сумму чисел 1+1/1!+1/2!+1/3!+...+1/N!. Количество действий должно быть пропорционально N.
# input
    1
# output
    2

N = input()
s = input()

for i in range(1, N + 1):
    s += 1 / (i * (i - 1)) if i > 1 else 1

print(N, s)







### 7 Task
Write a Python program for binary search of an ordered list.
Напишите программу на Python для двоичного поиска в упорядоченном списке.
# Example
    Ordered_binary_Search([0, 1, 3, 8, 14, 18, 19, 34, 52], 3) -> True
    Ordered_binary_Search([0, 1, 3, 8, 14, 18, 19, 34, 52], 17) -> False
mlist = [0, 1, 3, 8, 14, 18, 19, 34, 52]
item = 3

a, b = 0, len(mlist) - 1
while a <= b:
    i = (a + right) // 2
    if olist[i] == item:
        print("Item found!")
        break
    elif olist[i] < item:
        a = i + 1
    else:
        b = i - 1
else:
    print("not")



### 8 Task
Write a Python program to replace each character of a word of length five and more with a hash character (#).
Напишите программу на Python, заменяющую каждый символ слова длиной пять и более символом решетки (#).
# input
    Count the lowercase letters in the said list of words:
# output
    ##### the ######### ####### in the said list of ######

text = input()
words = text.split()
javob = []
for word in words:
    if len(word) >= 5:
        javob.append("#" * len(word))
    else:
        javob.append(word)
num = " ".join(result)
print(num)


### 9 Task
Write a Python script to print a dictionary where the keys are numbers between 1 and N (both included) and the values are the square of the keys.
Напишите сценарий Python для печати словаря, в котором ключами являются числа от 1 до N (оба включены), а значениями являются квадраты ключей.
# input
    15
# output
    {1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64, 9: 81, 10: 100, 11: 121, 12: 144, 13: 169, 14: 196, 15: 225}

n = int(input())
num= {}
for i in range(1, n + 1):
    num[i] = i ** 2
print(num)






duyum rohash 
N = 15

my_dict = {i: i**2 for i in range(1, N + 1)}

print(my_dict)

### 10 Task
Given a list of elements of any data types. Create a Python program to separate elements by their types and save them into a new dictionary.
The keys of a dictionary must be of a data type, and its element must be data belonging to that type.
Дан список элементов любых типов данных. Создайте программу Python для разделения элементов по их типам и сохранения их в новый словарь.
Ключи словаря должны иметь тип данных, а его элементом должны быть данные, принадлежащие этому типу.
# input
    1 hello True 12 Muhammad
# output
    {"int": [1,12], "str": ["hello", "Muhammad"], "bool": [True]}



word = [1, "hello", True, 12, "Muhammad"]
result = {}
for word in word:
    i = type(word)
    if i not in result:
        result[i] = []
    result[i].append(word)

print(i)
