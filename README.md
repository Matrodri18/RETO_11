# RETO_11

### Métodos de Strings en Python

- **endswith:** Verifica si una cadena termina con el sufijo especificado. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "Solo millos"
  resultado = texto.endswith("millos")  # True
  resultado = texto.endswith("Nacional")  # False

- **startswith:** Verifica si la cadena comienza con el prefijo especificado. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "Millos el mejor"
  resultado = texto.startswith("Millos")  # True
  resultado = texto.endswith("Nacional")  # False

- **isalpha:** Verifica si todos los caracteres de la cadena son alfabéticos. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "Yooomenamoreeeeeeedemillonariosmeenamoreeee"
  resultado = texto.isalpha()  # True
  
- **isalnum:** Verifica si todos los caracteres de la cadena son alfanuméricos (letras y números). Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "Nacionalmurioel23dejuniodel2023"
  resultado = texto.isalnum()  # True

- **isdigit:** Verifica si todos los caracteres de la cadena son dígitos. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "230623"
  resultado = texto.isdigit()  # True

- **isspace:** Verifica si la cadena está en formato título (la primera letra de cada palabra es mayúscula). Devuelve `True` si es así, de lo contrario `False`.
  ```python
  ##Libertadores de nacional en 1989
  texto = "   "
  resultado = texto.isspace()  # True

- **istitle:** Verifica si la cadena está en formato título (la primera letra de cada palabra es mayúscula). Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "Club Deportivo Los Millonarios"
  resultado = texto.istitle()  # True

- **islower:** Verifica si todos los caracteres de la cadena están en minúsculas. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "pablito te la compro"
  resultado = texto.islower()  # True

- **isupper:** Verifica si todos los caracteres de la cadena están en mayúsculas. Devuelve `True` si es así, de lo contrario `False`.
  ```python
  texto = "MINUTO 85 LA MALA PARA SANTAFE" #FUTBOL EN PAZ
  resultado = texto.isupper()  # True
