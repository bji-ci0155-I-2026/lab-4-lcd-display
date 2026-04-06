# lab-4-lcd-display

## Referencias

- Cableado y programas básicos: <https://docs.arduino.cc/learn/electronics/lcd-displays/>
- Caractéres personalizados: <https://naylampmechatronics.com/blog/34_tutorial-lcd-conectando-tu-arduino-a-un-lcd1602-y-lcd2004.html>
- Números aleatorios: <https://docs.arduino.cc/language-reference/en/functions/random-numbers/randomSeed/>

Citas APA de IA:

- Anthropic. (2024). *Claude* [Modelo de Lenguaje Grande]. <https://claude.ai>
- Microsoft / GitHub. (2024). *GitHub Copilot* [Asistente de código de IA]. <https://github.com/features/copilot>

## Declaración de Uso de Inteligencia Artificial (IA)

Con el fin de cumplir con las normativas de transparencia y ética en el uso de herramientas generativas, a continuación se documenta el uso de IA en este proyecto:

### 1. Herramientas Utilizadas

- **Claude (Anthropic):** Utilizado para la generación de la lógica principal y animaciones del archivo `casino_slots.ino`.
- **GitHub Copilot:** Utilizado para la redacción y estructuración de esta declaración de uso de IA en el archivo `README.md`.

### 2. Propósito y Momento de Uso

La IA de Claude fue utilizada durante la fase de desarrollo para generar el borrador inicial del código del juego de tragamonedas, establecer la lógica de la matriz del LCD y crear la animación de victoria, basándose en la configuración de pines existente. GitHub Copilot fue utilizado al final del proyecto para documentar este proceso.

### 3. Entradas (Prompts) y Contexto Proveído

**Para la generación de `casino_slots.ino` (Claude):**

- **Contexto adjunto:** Se proporcionó el archivo `lcd_display_autoscroll.ino` para dar contexto exacto sobre el cableado y la configuración de los pines del Arduino.
- **Prompt utilizado:**

  > *"Estoy trabajando con un arduino y probando el modulo de display lcd, tengo las conexiones iguales a como están en el archivo adjunto. Ayudame a crear un nuevo sketch con una animación de una máquina de slots de casino, donde se generen los números y si el jugador gana (digamos que 3 simbolos iguales) entonces una animación de ("YOU WIN!!") se reproduce. Introduce una variable que permita hacer que el jugador siempre gane (para pruebas)"*

**Para la redacción de esta documentación (GitHub Copilot):**

- **Prompt utilizado:** Se proporcionó el reglamento de evaluación completo, el contexto sobre cómo se usó Claude previamente, y se solicitó estructurar esta sección del README cumpliendo todos los lineamientos.

### 4. Uso de Resultados, Verificación y Responsabilidad

El código generado por Claude fue integrado en el archivo `casino_slots.ino`. Antes de su implementación final, el código fue analizado, validado lógicamente y probado en el circuito físico para comprobar que la lógica de pines, probabilidades y manejo de memoria del LCD fueran correctos y no presentaran errores. El código sirve como apoyo a la implementación, complementado por revisión y validación propia.
