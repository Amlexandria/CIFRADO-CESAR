# Cifrado César
#### *Devolviendo un mensaje encriptado según el algoritmo de Cifrado César.*



Se crea una web que pide (por medio de un *prompt*) una frase al usuario, y devuelve el mismo mensaje encriptado según el algoritmo de *cifrado césar*, con un parámetro de 33 espacios hacia la derecha.


#### Input:
```javascript
[
  "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
]
```
#### Output:
```javascript
[
  "HIJKLMNOPQRSTUVWXYZABCDEFG"
]
```

#### Consideraciones Específicas:
- El programa es capaz de cifrar y descifrar tanto letras mayúsculas como minúsculas, gracias a la aplicación de la fórmula para descifrar: (x - n) % 26.

- El código está compuesto por 2 funciones con los siguientes nombres: **_cipher_** y **_decipher_**.

- El usuario no puede ingresar un campo vacío o que contenga números.


#### Pseudocódigo:

- Obtener una frase del usuario.
- Encriptar la frase utilizando código Ascii y la fórmula de Cifrado César.
- Devolver la frase encriptada.

#### Diagrama de Flujo:
![Diagrama de flujo de cifrado cesar](assets/img/DiagramaCifradoCesar.png)
