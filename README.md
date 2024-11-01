
#9
"""
def main():
    print("Вы пробуждаетесь в главной комнате замка.")
    print("Вы можете пойти в 'зал', 'кухню' или 'подземелье'.")

    while True:
        choice = input("Куда вы хотите пойти? ").lower()

        if choice == "зал":
            print("В зале вы видите охранника, который охраняет ключ.")
            action = input("Вы хотите (1) обойти охранника или (2) напасть на него? ")

            if action == "1":
                print("Вы удачно проскользнули мимо охранника и взяли ключ!")
                print("Теперь вы можете пойти в 'подземелье'.")
                continue
            else:
                print("Охранник тревожится и вызывает сигнал тревоги. Игра окончена.")
                break

        elif choice == "кухня":
            print("Вы на кухне и находите еду, восстанавливающую ваши силы.")
            print("Однако выхода нет. Вам нужно вернуться в главную комнату.")
            continue

        elif choice == "подземелье":
            if 'ключ' in locals():
                print("Вы открываете дверь и выбираетесь на свободу! Поздравляем!")
                break
            else:
                print("Дверь закрыта. Вам нужен ключ, чтобы выбраться.")
                continue
        else:
            print("Неверный выбор. Попробуйте снова.")

if _name_ == "_main_":
    main()
"""
#10
"""
def main():
    print("Вы путешественник и желаете дойти до магического озера.")
    print("Перед вами три пути: 'лес', 'гора' и 'река'.")

    while True:
        choice = input("Куда вы направитесь? ").lower()

        if choice == "лес":
            time = input("Сколько времени потребуется, чтобы пройти через лес (в часах)? ")
            if time == "3":
                print("Поздравляем! Вы нашли карту, указывающую путь к озеру.")
                break
            else:
                print("К сожалению, вы потерялись в лесу. Игра окончена.")
                break
        elif choice == "гора":
            answer = input("Если 3 яблока упадут с дерева, сколько яблок останется на дереве? ")
            if answer == "0":
                print("Верно! Маг дал вам магический амулет для защиты на пути к озеру.")
                continue
            else:
                print("Неверный ответ. Маг выбрасывает вас из своего гнезда. Игра окончена.")
                break
        elif choice == "река":
            puzzle = input("Вы должны переправиться через реку, расстояние которой равно 6 км.\n У вас есть лодка, которая может вместить не более двух человек.\n Вы можете использовать какую угодно комбинацию людей:\n 1 человек проходит реку за 1 час, 2 человека - за 30 минут, 3 человека - за 20 минут. Введите, сколько времени потребуется, чтобы все добрались до другой стороны (в минутах): ")
            if puzzle == "40":
                print("Поздравляем! Вы нашли путь к магическому озеру!")
                break
            else:
                print("К сожалению, вы потерялись в реке. Игра окончена.")
                break
        else:

            print("Неверный выбор. Попробуйте снова.")
"""
#11
"""
def find_treasure(door_number):
    if (door_number % 3 == 0) and (door_number != 1) and (door_number != 2):  # Не красная (1) и не синяя (2)
        return "Сокровища находятся за дверью номер", door_number
    else:
        return "Ловушка!"
"""
#12
"""
def attack_dragon(player_health, dragon_attacks_first):
    if player_health < 50:
        if player_health > 30 or dragon_attacks_first:
            return "Атакуем дракона магией!"
        else:
            return "Используем меч!"
    else:
        return "Используем меч!"
"""
#13
"""
def brew_potion(drops_ingredient_1, drops_ingredient_2):
    if drops_ingredient_1 % 5 == 0 and drops_ingredient_2 % 7 == 0:
        if drops_ingredient_1 % 3 == 0 and drops_ingredient_2 % 3 == 0:
            return "Зелье взорвалось!"
        else:
            return "Зелье успешно приготовлено!"
    else:
        return "Зелье не удалось!       
 """


