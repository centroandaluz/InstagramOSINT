# Herramienta OSINT de Instagram

Esta herramienta OSINT de Instagram saca información de una cuenta de Instagram que no podría obtener
con solo mirar su perfil

La información incluye:

1. Nombre de usuario
2. Nombre del perfil
3. URL
4. Seguidores
5. Siguiendo
6. Número de publicaciones
7. Bio
8. URL de la imagen de perfil
9. ¿Cuenta comercial?
10. ¿Conectado a una cuenta de FB?
11. URL externa
12. ¿Se unió recientemente?
13. Nombre de la categoría comercial
14. ¿Es privado?
15. ¿Está verificado?
16. Descarga fotos públicas

# Uso
Nota: debe usar python3.6 o superior al uso de cadenas "f"

1. `pip3 install -r requriments.txt`
2. `python3 main.py --username USERNAME`


Tenga en cuenta que InstagramOSINT.py es para importar como módulo python, esto es para usar en aplicaciones personalizadas



# Salida

El formato de salida es un dict / json dentro de un archivo txt en el directorio creado para el perfil que escaneó


# Uso de la API InstagramOSINT.py

Esto es útil cuando se trata de aplicar esta base de código a cualquier proyecto. La API es realmente fácil de usar y usa Python

ejemplos:

`from InstagramOSINT import *`
`instagram = InstagramOSINT(username='USERNAMEHERE')`
`print(instagram.profile_data)`
`print(instagram['Username'])`
`instagram.print_profile_data()`
`instagram.save_data()`
`instagram.scrape_posts()`


# Descargo de responsabilidad

No soy responsable de nada con esta herramienta que pueda considerarse ilegal. ¡No infrinjas la ley!
