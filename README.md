# PytonTest


import random

# Генерируем случайное число от 1 до 10
secret_number = random.randint(1, 10)

# Запрашиваем у пользователя число
guess = int(input("Угадайте число от 1 до 10: "))

# Проверяем ответ
if guess == secret_number:
    print("Поздравляю! Вы угадали число.")
else:
    print(f"Вы не угадали. Загаданное число было {secret_number}.")
