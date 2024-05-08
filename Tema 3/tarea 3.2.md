# Tarea 3.2 Caso practico Automata Finito

Los autómatas finitos son modelos matemáticos utilizados en informática y teoría de la computación para representar sistemas de estados finitos que pueden cambiar de un estado a otro en respuesta a una entrada. Estos dispositivos abstractos son útiles para entender y diseñar sistemas de control, reconocedores de lenguajes formales y analizar la complejidad de algoritmos.

## Caso de uso: Reconocimiento de Comandos de Voz

### Aplicación:

El reconocimiento de comandos de voz es un caso de uso común de los autómatas finitos. Se utiliza en una variedad de sistemas, como asistentes virtuales, sistemas de navegación en automóviles, dispositivos IoT, aplicaciones móviles, etc. La aplicación principal es permitir que los usuarios interactúen con dispositivos electrónicos utilizando su voz, lo que ofrece una experiencia de usuario más natural y conveniente.

### Implementación:

**_1. Definición del autómata:_**

- Se define un autómata finito para cada comando de voz que se desea reconocer. Cada autómata representa una palabra o frase específica que el sistema debe reconocer.
- El autómata incluye estados que representan partes de la palabra o frase y transiciones entre estos estados.

**_Captura de audio:_**

- El sistema captura el audio del usuario utilizando un micrófono.
  
**_Preprocesamiento del audio:_**

- El audio capturado se preprocesa para extraer características relevantes, como frecuencias de sonido, características espectrales, etc.

**_Reconocimiento de patrones:_**

- Se utiliza el autómata finito para reconocer patrones en las características extraídas del audio.
- El sistema compara las características extraídas con las transiciones definidas en el autómata finito para determinar si se ha reconocido una palabra o frase.

**_Acción correspondiente:_**

- Una vez que se reconoce una palabra o frase, se realiza la acción correspondiente. Por ejemplo, si se reconoce el comando "iniciar música", el sistema puede comenzar a reproducir música.

**_Ejemplo:_**

Consideremos un sistema de reconocimiento de comandos de voz para un asistente virtual en un teléfono inteligente. El sistema debe ser capaz de reconocer comandos como "llamar a casa", "enviar mensaje a Juan", "abrir la aplicación de música", etc.

1. Se define un autómata finito para cada uno de estos comandos. 
2. Cuando el usuario emite un comando de voz, el sistema captura el audio y lo preprocesa.
3. Luego, utiliza los autómatas finitos correspondientes para reconocer el comando de voz.
4. Una vez que se reconoce el comando, el sistema realiza la acción correspondiente, como llamar a un contacto, enviar un mensaje de texto o abrir una aplicación.

Este caso de uso muestra cóaplicaciones del mundo real, como el reconocimiento de comandos de voz, para mejorar la interacción hombre-máquina.

**_Referencias:_**

Li Deng, Dong Yu, "Deep Learning: Methods and Applications", Morgan & Claypool Publishers, 2014.
