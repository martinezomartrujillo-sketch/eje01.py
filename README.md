# eje01.py
# EJERCICIO 1: Verificador de Mayoría de Edad
edad = int(input("Ingresa tu edad: "))
if edad >= 18:
    print("¡Eres mayor de edad! Tienes derecho a votar. 📦")
else:
    print("Eres menor de edad. Aún no puedes votar. 🔴")

# EJERCICIO 2: El Semáforo Inteligente
color = input("¿De qué color está el semáforo? (rojo/amarillo/verde): ")
if color.lower() == "rojo":
    print("¡Alto! Detén el vehículo. 🔴")
elif color.lower() == "amarillo":
    print("Precaución: Reduce la velocidad. 🟡")
elif color.lower() == "verde":
    print("Adelante: Puedes avanzar. 🟢")
else:
    print("Color no reconocido. Revisa el semáforo. ⚠️")

# EJERCICIO 3: Calculadora de Descuentos
monto_compra = float(input("Ingrese el total de su compra ($): "))
if monto_compra > 20.00:
    descuento = monto_compra * 0.10
    total_final = monto_compra - descuento
    print("¡Aplica descuento del 10%! A pagar: $", total_final)
else:
    print("No aplica descuento. Total a pagar: $", monto_compra)

# EJERCICIO 4: Verificación de Usuario y Clave
usuario = input("Ingresa tu usuario: ")
clave = input("Ingresa tu clave: ")
if usuario == "estudiante" and clave == "2026":
    print("¡Acceso concedido! Bienvenido al sistema. ❇️")
else:
    print("Usuario o contraseña incorrectos. ❌")

# EJERCICIO 5: Clasificador de Números
numero = float(input("Escribe cualquier número: "))
if numero > 0:
    print("El número es POSITIVO. ➕")
elif numero < 0:
    print("El número es NEGATIVO. ➖")
else:
    print("El número es CERO. 0️⃣")
