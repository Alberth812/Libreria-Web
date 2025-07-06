 Libreria-Web
 
![WhatsApp Image 2025-07-04 at 18 19 31](https://github.com/user-attachments/assets/d6bef53a-f0c9-4cf3-b31b-8c40e9706540)

Esta librería proporciona un conjunto de funciones utilitarias para el manejo avanzado de fechas en aplicaciones web, resolviendo problemas comunes en la manipulación, formateo y validación de fechas en JavaScript.

Funcionalidades Detalladas
hoy()

Descripción técnica: Implementa un wrapper de new Date() con normalización ISO 8601
Salida: string en formato "yyyy-mm-dd"
Ejemplo: 2023-07-20
Complejidad: O(1)
Lista de Parámetros utilizados:

    fecha: string (ISO 8601) o objeto Date

    formato: string con tokens:

        "dd/mm/yyyy": Formato europeo

        "mm-dd-yyyy": Formato americano

        "yyyy/mm/dd": Formato japonés
Algoritmo: Utiliza Intl.DateTimeFormat para localización
Validaciones: Verifica formato de entrada
Ejemplo: formatearFecha('2023-07-20', 'dd/mm/yyyy') → "20/07/2023"
    Obtiene día de la semana (0-6) donde 0=domingo, 6=sábado

    Verifica día === 0 || día === 6

Optimización: Evita creación de objetos Date redundantes
Retorno: boolean
sumarDias(fecha, dias)
![imagen](https://github.com/user-attachments/assets/1134148e-6d6c-4cb2-aef2-467208562184)


 

![WhatsApp Image 2025-07-04 at 14 39 12](https://github.com/user-attachments/assets/70898770-2e3b-4e98-9cc9-ef4e6f8bd64d)

Se abre desde Visual studio y como se puede ver se crea primero un ejemplo de html

![image](https://github.com/user-attachments/assets/a6455441-67f7-4b68-8dbf-9e8eb01c856e)

en este apartado podemos observar como ponemos el URL 

![image](https://github.com/user-attachments/assets/52e63d89-5821-483b-a4e2-9c6771a0511f)

aqui se ve mejor el URL dee la libreria

![image](https://github.com/user-attachments/assets/a7c3c370-81d5-4a23-9f65-15b49240a23d)



y los ejemplos de como se relizaron

![WhatsApp Image 2025-07-04 at 14 41 57](https://github.com/user-attachments/assets/d241e642-e8c6-488c-b228-be6f1c2554b3)
![WhatsApp Image 2025-07-04 at 14 41 58 (3)](https://github.com/user-attachments/assets/1848b069-49df-42ac-8729-e6cbacf99fa5)
![WhatsApp Image 2025-07-04 at 14 41 58 (2)](https://github.com/user-attachments/assets/16e686a6-e339-4872-85db-f34f7c7c82ba)
![WhatsApp Image 2025-07-04 at 14 41 58 (1)](https://github.com/user-attachments/assets/0705f22d-d91c-4ad6-9f1f-002ce5411a16)
![WhatsApp Image 2025-07-04 at 14 41 58 (1)](https://github.com/user-attachments/assets/e5051b6a-1018-486b-bd68-dff85b435c0c)

Video:
https://youtu.be/zBXvptCvy78


