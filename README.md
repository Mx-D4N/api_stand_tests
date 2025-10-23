# Pruebas para el Proyecto Urban Grocers Sprint 7 1era Parte

- Descripción:
- Introducción a testing de APIs
- Trabajo con requests HTTP (GET, POST, PUT, DELETE)
- Validación de respuestas JSON
- Testing automatizado con Python
- Uso de pytest para estructurar tests

- Objetivos:
- Testing de endpoints de usuarios (/api/v1/users/)
- Validación de productos y kits (/api/v1/products/kits/)
- Manejo de logs (/api/logs/main/)
- Trabajo con archivos CSV (user_model.csv)

- 1. Gestión de Usuarios:
- Crear usuarios con diferentes parámetros
- Validar campos obligatorios vs opcionales
- Probar límites de caracteres en nombres
- Validar formatos de email y teléfono

2. Testing de Kits de Productos:
- Obtener lista de kits disponibles
- Validar estructura de respuesta JSON
- Verificar información de productos

3. Manejo de Logs:
- Acceder a logs del sistema
- Verificar registros de transacciones

Tipos de pruebas:
Pruebas Positivas:
- Crear usuario con datos válidos
- Obtener kits exitosamente
- Verificar códigos de estado 200/201

Pruebas Negativas:
- Crear usuario sin campos obligatorios
- Enviar datos inválidos
- Verificar códigos de error 400/422

### Herramientas utilizadas:
- Python - Lenguaje principal
- requests - Para llamadas HTTP
- pytest - Framework de testing
- JSON - Manejo de respuestas
- CSV - Datos de prueba


2025 - Tripleten Sprint 7
