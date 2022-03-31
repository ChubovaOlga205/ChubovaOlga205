print("Привет всем участникам интенсива")
#
# Переменные:
speaker = "Мишаня"
duration = 140 # Длительность в минутах
intensive_name = "Знакомство с Python"
# ptint - это команда которая выводит сообщение на экран
print(intensive_name)
# Если перед первой кавычкой поставить f
# То строка станет форматированной
print(f"Сегодня ведущий: {speaker}")

duration_hours = duration / 60

print(f"Длительность: {duration} минут / {duration_hours} часа")

if duration > 120:
  print("Запасайтесь печеньками и чипсами, эфир будет длинный")
else:
  print("эфир будет короткий, заварите чайку")
  
  # len - считает кол-во символов в строке
  print (len(intensive_name))
  
  # Давайте сохраним все данные в одной переменной - словаре
  intensive_dats = {
  "name": "Знакомство с Python",
  "speaker": "Мишаня"
  "duration": 12,
  }
  
  print (intensive_data["name"])
  
  
  
  
  # Структура одного сообщения
  chat_msg_1 = {
  "text": "Всем приветы в этом чате",
  "sender": "Васисуалий",
  "date": "31-01-22 21:00",
  }
  
   chat_msg_2 = {
  "text": "Йо Йо, какие дела?",
  "sender": "Мишаня",
  "date": "31-01-22 22:00",
  }
  
  messages_list = 
  
  def print_message(message):
  print(f"[{message['sender']}]: {message['text']} / {message['date']}")
  ptint("-" * 50)
  
  
  
  [] [
      ["сегодня", "хорошая", "погода"],
      ["хорошая", "погода", "была"],
      ["памурно", "питер", "погода", "дождь"]
      ]
      corpus = {"сегодня", "хорошая", "погода", "была", "пасмурно", "питер", "дождь"}
      len(corpus)
      
      
      
      # 1. Искать "неточное" совпадение
import nltk
def mathText(text1,text2): # Создаем функцию, которая посчитает похожи ли два текста
  distance = ntlk.edit_distance(text1,text2) # Посчитаем расстояние между текстами (насколько они отличаются)
  average_lenght = (len(text1) + (text2)) / 2 # Посчитаем среднюю длину текстов
  distance / average_lenght # Примерно насколько тексты отличаются в процентах
question = "Как дела?" # Вопрос, который мы задаем боту
if question == "Как дела":
  print("Дела нормально")

if question == "Как тебя зовут":
   print ("Меня зовут Скиллбот3000")
  prin("А как зовут тебя?")

if question == "Какого цвета небо?":
   print("Небо цвета голубого")
   





[tool.poetry]
name = "python-template"
version = "0.1.0"
description = ""
authors = ["Your Name <you@example.com>"]

[tool.poetry.dependencies]
python = ">=3.8.0,<3.9"
numpy = "^1.22.2"

[tool.poetry.dev-dependencies]

[build-system]
requires = ["poetry-core>=1.0.0"]
build-backend = "poetry.core.masonry.api"

      
  
  
  
  
  
  
  
  
  
  
  
  
  
  
   

