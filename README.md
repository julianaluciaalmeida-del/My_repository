# Diccionario de palabras modernas
meme_dict = {
    "lol": "Una respuesta a algo gracioso",
    "cringe": "Algo raro o embarazoso",
    "rolf": "Una respuesta a una broma",
    "sheesh": "Ligera desaprobación",
    "creepy": "Aterrador o siniestro",
    "aggro": "Ponerse agresivo o enojado"
}

# Saludo e instrucciones
print("¡Bienvenido al Diccionario de Palabras Modernas!")
print("Puedes escribir una palabra en MAYÚSCULAS para conocer su significado.")
print("Tendras 5 intentos.\n")

# Bucle para preguntar 5 palabras
for i in range(5):
    word = input("Escribe una palabra que no entiendas: ")

    # Verificar si la palabra existe en el diccionario
    if word in meme_dict.keys():
        print("Significado:", meme_dict[word])
    else:
        print("Esa palabra no está en el diccionario.")

    print()  # Espacio entre respuestas
