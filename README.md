# gmail-AutomaticMassiveSender
Envía el mismo correo de manera automática a gran cantidad de destinatarios

1. Abrir archivo config, y cambiar las variables:
    - user_name por la dirección de correo electrónico con el que enviarás el correo
    - password por la contrasenya del correo electrónico
    - subject por el asunto del correo
    - message por el mensaje que contendrá el correo

2. Poner en el excel las direcciones de correo a las que enviaremos el correo:
    IMPORTANTE, escribir todas las direcciones en la misma columna y debajo de la primera fila

3. Ejecutar el archivo python empresas_to_txt.py desde la terminal con el siguiente comando:
    python3 empresas_to_txt.py
    
4. Ejecutar el archivo gmail_massive_email_sender.py desde la terminal con el siguiente comando:
    python3 gmail_massive_email_sender.py
