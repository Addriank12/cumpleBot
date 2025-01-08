# cumpleBot

### 1. Crear un entorno virtual

python -m venv cumpleBot 

### 2. Activar el entorno virtual

- En Windows:

```bash
.\cumpleBot\Scripts\activate
```

- En macOS/Linux:

  ```bash
  source cumpleBot/bin/activate

### 3. Instalar las dependencias

Con el entorno virtual activado, ejecuta:

pip install -r requeriments.txt

### 4. Crear archivo cumples.csv que es donde se almecenaran los cumpleaños ###


#### Bot de Telegram que te recuerda los cumpleaños.

Tiene 4 comandos:
+ start -> Que inicializa el bot
+ nuevo -> Añade un cumpleaños(no se permiten nombres repetidos)
+ borrar -> Elimina un cumpleaños dado el nombre de la persona
+ mostrar -> Muestra todos los cumpleaños guardados
