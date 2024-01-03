# Analisis_Datos_Whatsapp
Proyecto personal hecho en python con las librerias:
pandas, regex, collections, wordcloud, nltk

### Instalar estas dependencias para poder compilar codigo:
!pip install pandas
!pip install requests
!pip install emoji

### En la tercera celda del codigo cambiar el directorio:
from google.colab import drive
drive.mount('/content/drive')
%cd /content/drive/MyDrive/xxxxx/
!ls

### En la cuarta celda importa el chat exportado desde whatsapp en formato .txt:
file_path = 'yyyyy.txt'

#¿Qué podemos apreciar en este análisis?
* Primer y último mensaje en el chat
* Total de mensajes, multimedia, emojis, links, mensajes eliminados y encuestas
* Emojis más usados
* Pie de emojis en %
* Miembros que contribuyen en el chat con su total de mensajes enviados
* Ratio de los mensajes
* Media de mensajes en intervalos de tiempo
* Día con más mensajes enviados
* WordCloud
