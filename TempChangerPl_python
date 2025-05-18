# Prosty programik przeliczający temperaturę w Celsjuszach na Fahrenheity, i odwrotnie.

a = float(input('Podaj temperaturę w Celsjuszach : '))
b = float(input('Podaj temperatur w Fahrenheitach : '))
def temp_changerC(a):
    degrees_celsius = a
    degrees_fahrenheit = round((9 / 5 * degrees_celsius + 32),1)
    return degrees_fahrenheit


def temp_changerF(b):
    degrees_fahrenheit = b
    degrees_celsius = round((5 / 9 * (degrees_fahrenheit - 32)),1)
    return degrees_celsius


degrees_fahrenheit = temp_changerC(a)
degrees_celsius = temp_changerF(b)
print(f'Po przeliczeniu temperatura w Fahrenheitach wynosi {degrees_fahrenheit} F')
print(f'Po przeliczeniu temperatura w Celsjuszach wynosi {degrees_celsius} C')
