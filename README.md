# ticket = int(input"Введите количество билетов:"))
KID_PRICE = 0.00
YOUNG_PRICE = 990.00
ADULT_PRICE = 1390.00
KID_LIMIT = 0-17
YOUNG_LIMIT = 18-25
ADULT_LIMIT = >25
total = 0
line = input("Введите возраст посетителя (пустая строка для окончания ввода): ")
while line != "":
age = int(line)
if age <= KID_LIMIT:
total = total + KID_PRICE
elif age <= YOUNG_LIMIT:
total = total + YOUNG_PRICE
elif age <= ADULT_LIMIT:
total = total + ADULT_PRICE
elif ticket > 3:
PRICE=PRICE-((PRICE/100)*10)
print("Сумма посещения онлайн-конференции руб.(с учетом скидки 10%,т.к зарегистрировано больше 3-х чел.) $%.2f" % total)
