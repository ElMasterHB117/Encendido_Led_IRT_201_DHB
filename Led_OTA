import machine
import time

# Define el pin del LED (asegúrate de que coincida con tu conexión)
led_pin = 2

# Configura el pin como salida
led = machine.Pin(led_pin, machine.Pin.OUT)

while True:
    # Enciende el LED
    led.value(1)
    time.sleep(1)

    # Apaga el LED
    led.value(0)
    time.sleep(1)
