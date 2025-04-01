# if-else-elif

# ¿Por qué y para qué sirven los if, else y elif en Python?
Los condicionales en Python (if, else, elif) sirven para tomar decisiones en el código, ejecutando ciertas acciones según una condición lógica.

# ¿Por qué se usan?
Control de flujo: Permiten ejecutar diferentes partes del código según las condiciones.
Toma de decisiones: Hacen que el programa responda a diferentes situaciones.
Evitan código innecesario: Solo ejecutan lo necesario, optimizando el rendimiento.

# ¿Cómo funcionan?
Python evalúa una condición (True o False) y ejecuta el bloque de código correspondiente.

1 if: Evalúa una condición y ejecuta el código si es True

edad = 18

if edad >= 18:
    print("Eres mayor de edad.")

2. if - else: Ejecuta un bloque si la condición es True y otro si es False

edad = 16

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")

Si la condición de if no se cumple, el código dentro de else se ejecuta

3. if - elif - else: Múltiples condiciones

nota = 85

if nota >= 90:
    print("Tienes una A.")
elif nota >= 80:
    print("Tienes una B.")
elif nota >= 70:
    print("Tienes una C.")
else:
    print("Debes mejorar.")

El programa revisa las condiciones en orden hasta encontrar una True.

# Ejemplo.
temperatura = int(input("Ingresa la temperatura: "))

if temperatura > 30:
    print("Hace calor.")
elif temperatura < 10:
    print("Hace frío.")
else:
    print("El clima es agradable.")


#  Notas de ejemplo
