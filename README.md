Brute froce in python per sbloccare un .rar,
ecco la spiegazione 
import subprocess

with open('lista di password.txt', 'r') as file:
    passwords = file.readlines()
    for password in passwords:
        subprocess.run(['C:\\Program Files\\WinRAR\\WinRAR.exe', 'x', '-p' + password.strip(), 'posizione del .rar '])
SOLO A SCOPO EDUCATIVO E DIDATTICO NON SONO RESPONSABILE IN CASO DI USI IMPROPRI.
