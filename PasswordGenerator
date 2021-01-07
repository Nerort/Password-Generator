import random


class GoodPasswordGenerator:
    """
    Генератор паролей
    """

    def __init__(self):
        """Инициализация генератора"""
        self.alphabet = '1234567890' \
                        'qwertyuiopasdfghjklzxcvbnm' \
                        'QWERTYUIOPASDFGHJKLZXCVBNM' \
                        '!@#$%^&*()_+'

    def next(self, length=10):
        """Получение пароля"""
        password = ''
        for i in range(length):
            c = random.choice(self.alphabet)
            password += c
        return password


generator1 = GoodPasswordGenerator()
print(generator1.next())
