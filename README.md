# Conversor de Monedas

Este es un programa en Java que permite convertir montos entre diferentes monedas utilizando la API de ExchangeRate-API. 

## Características

- Conversión entre las principales monedas internacionales (EUR, USD, JPY, GBP, CHF, AUD, etc.).
- Posibilidad de convertir entre cualquier otra combinación de monedas introducida manualmente.
- Utiliza una API externa para obtener tasas de conversión actualizadas.
- Implementado con una estructura modular para facilitar la escalabilidad.

## Estructura

├── Principal.java          // Clase principal del programa
├── ConsultarMoneda.java    // Clase para interactuar con la API de ExchangeRate-API
├── ConvertirMoneda.java    // Clase con lógica para convertir monedas
└── Moneda.java             // Clase que representa el modelo de datos de una moneda
