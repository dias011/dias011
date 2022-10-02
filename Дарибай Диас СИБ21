1)
my_list = [55,'Dias', True, 2.5]
def my_type(el):
    for el in range(len(my_list)):
        print(type(my_list[el]))
    return
my_type(my_list)
2) el_count = int(input("Тізім элементтерінің санын енгізіңіз "))
my_list = []
i = 0
el = 0
while i < el_count:
    my_list.append(input("Келесі тізім мәнін енгізіңіз "))
    i += 1

for elem in range(int(len(my_list)/2)):
        my_list[el], my_list[el + 1] = my_list [el + 1], my_list[el]
        el += 2
print(my_list)
3)
seasons_list = ['қыс', 'көктем', 'жаз', 'күз']
seasons_dict = {1 : 'қыс', 2 : 'көктем', 3 : 'жаз', 4 : 'күз'}
month = int(input("Айды нөмір бойынша енгізіңіз "))
if month ==1 or month == 12 or month == 2:
        print(seasons_dict.get(1))
        print(seasons_list[0])
elif month == 3 or month == 4 or month ==5:
    print(seasons_dict.get(2))
    print(seasons_list[1])
elif month == 6 or month == 7 or month == 8:
    print(seasons_dict.get(3))
    print(seasons_list[2])

elif month == 9 or month == 10 or month == 11:
    print(seasons_dict.get(4))
    print(seasons_list[3])
else:
        print("Мұндай ай жоқ")
4) my_str = input("введите строку ")
my_word = []
num = 1
for el in range(my_str.count(' ') + 1):
    my_word = my_str.split()
    if len(str(my_word)) <= 10:
        print(f" {num} {my_word [el]}")
        num += 1
    else:
        print(f" {num} {my_word [el] [0:10]}")
        num += 1
5) 
my_list = [7, 5, 3, 3, 2]
print(f"Рейтинг - {my_list}")
digit = int(input("Введите число (111 - выход) "))
while digit != 111:
    for el in range(len(my_list)):
        if my_list[el] == digit:
            my_list.insert(el + 1, digit)
            break
        elif my_list[0] < digit:
            my_list.insert(0, digit)
        elif my_list[-1] > digit:
            my_list.append(digit)
        elif my_list[el] > digit and my_list[el + 1] < digit:
            my_list.insert(el + 1, digit)
    print(f"текущий список - {my_list}")
    digit = int(input("Введите число "))

6) goods = int(input("Өнім санын енгізіңіз "))
n = 1
my_dict = []
my_list = []
my_analys = {}
while n <= goods:
    my_dict = dict({'атауы': input("тақырыпты енгізіңіз "), 'цена': input("Бағаны енгізіңіз "),
                    'саны': input('Санын енгізіңіз '), 'eд': input("Өлшем бірлігін енгізіңіз ")})
    my_list.append((n, my_dict))
    n += 1
    my_analys = dict(
        {'название': my_dict.get('аты'), 'бағасы': my_dict.get('бағасы'), 'сомасы': my_dict.get('сомасы'),
         'ед': my_dict.get('ед')})
print(my_list)
print(my_analys)
