i = '1'
k = '2'
b = input('Что выберете: 1)Пройти тест 2) Вероятность проишествий для МЧС: ')
if b == i:
    from colorama import init

    init()
    from colorama import Fore, Back, Style

    print(Fore.RED)

    print('                                            На сколько хорошо вы знаете трэп аутистов')

    print(Fore.RESET)

    A1 = input('Сколько фильмов у треп аутистов?  1)5; 2)2; 3)827342394; 4)6: ')
    a1 = '1'
    if A1 == a1:
        print(Fore.GREEN)
        print('Хорош')
    else:
        print(Fore.RED)
        print('тупой, ответ 4')
    print(Fore.RESET)
    A2 = input(
        "Какой самый популярный ролик у треп аутистов?  1)ТРЕП АУТИСТЫ:ВОЗМЕЗДИЕ СЛАВЫ МЕРЛОУ; 2)Trap Auti$ti -#ДимаСнимиМаску 3)Coolio-Gangsta's Paradise (feat. L.V.) (Lyrical video); 4) LOL 6: ")
    a2 = '3'
    if A2 == a2:
        print(Fore.GREEN)
        print('Хорош')
        print(Fore.RESET)
    else:
        print(Fore.RED)
        print('тупой, ответ 1')
        print(Fore.RESET)

    A3 = input('Кто первый начал говорить о треп аутистах?  1)Сухов; 2)Вертеев; 3)Клепиков; 4)Кривых: ')
    a3 = '1'
    if A3 == a3:
        print(Fore.GREEN)
        print('Хорош')
        print(Fore.RESET)
    else:
        print(Fore.RED)
        print('тупой, ответ 1')
        print(Fore.RESET)

    A4 = input('Сколько хромосом у Славы мэрлоу?  1)отсутвуют; 2)1; 3)82; 4)46: ')
    a4 = '4'
    if A4 == a4:
        print(Fore.GREEN)
        print('Хорош')
        print(Fore.RESET)
    else:
        print(Fore.RED)
        print('тупой, ответ 4')
        print(Fore.RESET)

    A5 = input('Сколько вселенных в фильмах от трэп аутистах  1)10; 2)2; 3)84; 4)∞: ')
    a5 = '2'
    if A5 == a5:
        print(Fore.GREEN)
        print('Хорош')
        print(Fore.RESET)
    else:
        print(Fore.RED)
        print('тупой, ответ 2')
        print(Fore.RESET)

    if A1 == a1 and A2 == a2 and A3 == a3 and A4 == a4 and A5 == a5:
        print(Fore.GREEN)
        print('Ты мега красавчик, ответил на 5/5')
    elif A1 == a1 and A2 == a2 and A3 == a3 and A4 == a4:
        print(Fore.CYAN)
        print('Хорош, ответил на 4/5')
    elif A1 == a1 and A2 == a2 and A4 == a4 and A5 == a5:
        print('Хорош, ответил на 4/5')
    elif A1 == a1 and A4 == a4 and A3 == a3 and A5 == a5:
        print('Хорош, ответил на 4/5')
    elif A4 == a4 and A2 == a2 and A3 == a3 and A5 == a5:
        print('Хорош, ответил на 4/5')
    elif A1 == a1 and A2 == a2 and A3 == a3:
        print(Fore.YELLOW)
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A1 == a1 and A2 == a2 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A1 == a1 and A5 == a5 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A5 == a5 and A2 == a2 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A1 == a1 and A2 == a2 and A5 == a5:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A1 == a1 and A3 == a3 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A5 == a5 and A3 == a3 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A2 == a2 and A3 == a3 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    elif A1 == a1 and A3 == a3 and A4 == a4:
        print('Ну чел нормально знаешь, ответил на 3/5')
    else:
        print(Fore.RED)
        print('ебать ты даун')
    input()
elif b == k:
    import random

    a= random.randint (1, 100)
    if a <= 4:
        q = print('Произошло ограбление на ул.Ленино')
    elif a <= 19:
        w = print('Произошёл пожар на ул.Ленино')
    elif a <= 20:
        e = print('Произошло убийство на ул.Ленино')
    elif a <= 50:
        q = print('Произошло ограбление на ул.Марса')
    elif a <= 55:
        w = print('Произошёл пожар на ул.Марса')
    elif a <= 57:
        e = print('Произошло убийство на ул.Марса')
    elif a <= 74:
        q = print('Произошло ограбление на ул.Бажова')
    elif a <= 94:
        w = print('Произошёл пожар на ул.Бажова')
    elif a <= 100:
        e = print('Произошло убийство на ул.Бажова')


input()
