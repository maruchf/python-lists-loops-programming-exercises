# `13.1` Filter list

Este es otro ejemplo usando la función filter en python

Este algoritmo filtra la lista all_numbers y retorna una nueva lista sólo con los números pares

```py
all_numbers = [23,12,35,5,3,2,3,54,3,21,534,23,42,1]

def my_function(numb):
    return numb % 2 == 0

odd_numbers = list(filter(my_function, all_numbers))
print(odd_numbers)
```



# 📝Instrucciones
1. Complete el código para filtrar la lista resulting_names solo con los nombres que empiezan con la letra "R"
2. Use la función filter

```py
La consola debería mostrar:
['Romario', 'Roosevelt']
```
