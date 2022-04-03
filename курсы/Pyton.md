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
   
   
   
Как написать первое приложение

# For loop on a list
>>> numbers = [2,4,6,8,]
>>> product = 1
>>> for number in numbers:
...    product = product * number
... 
>>> print ('The product is:', product)
The product is: 384

https://replit.com/@OlghaChubova/FrighteningWellinformedProfessionals#main.py


print ('https://replit.com/@Leveshov/hask')

def good_password_generator(length):
    alhabet =  (
      '0123456789'
      'amncqcncqlcnbrjrymtlulllu'
      'BVFCVYHCFUVIUVFIYFIVHJBUI'
    )
    result = ''
    length (например 10) раз повторить:
      symbol = random.choise(alphabet)
      result += symbol
  return result


  # good_password_generator
  #bad_password_generator

  #def funk(a,b,c):
  #print(a)
  #result = b * c
  #return result
  #result = funk(1, 2, 3)
  #print(result)
  
  
  
  https://replit.com/@OlghaChubova/FrighteningWellinformedProfessionals#main.py
  print ('https://replit.com/@Leveshov/hask')

def good_password_generator(length):
    alhabet =  (
      '0123456789'
      'amncqcncqlcnbrjrymtlulllu'
      'BVFCVYHCFUVIUVFIYFIVHJBUI'
    )
    result = ''
    length (например 10) раз повторить:
      symbol = random.choise(alphabet)
      result += symbol
  return result


  # good_password_generator
  #bad_password_generator

  #def funk(a,b,c):
  #print(a)
  #result = b * c
  #return result
  #result = funk(1, 2, 3)
  #print(result)



for pair in database:
  if matchTaxt(question, pair[question]) < 0.4:
    answer = random.choice(pair["answer"])
    print(answer)

  Все шикарно

BOT_CONFIG = {
  "intents": { # Намерения пользователя
      "hello": { # Поздороваться
        "exmples": ["Привет", "Добрый день", "Шалом", "Здрасте", "Здравствуйте", "Доброе время суток"],
        "Responses": ["Привет, человек", "И вам здрасте", "йоу",]
     },
    "bye":{
      "examples": ["Пока", "До свидания", "Если что-возвращайтесь"]
    },
    "responses": ["Маюсь фигней", "Учу Phyton", "Смотрю вебинары Скиллбокс"],    
  },
},
"failure_phrases": ["Йа ничо не понял", "Что-то не понятно", "Я всего лишь бот, сформулируйте попроще"]
}


def isMatching(text1, text2): # Создаем функцию, которая посчитает похожи ли два текста
  text1 = normalize(text1)
  text2 = normalize(text2)
  distance = nltk.edit_distance(text1, text2) #     Посчитаем расстояние между текстами (насколько они отличаются)
     average_length = (len(text1) + len(text2)) / 2 # Посчитаем среднюю длину текстов
     return distance / average_length < 0.4

def getIntent(text): # Понимать намерение по тексту
  all_intent = BOT_CONFIG["intents"]
  for name, data in all_intents.items(): # Пройти по всем намерениям и положить название в name, и остальное в переменную data
      for example in data["examples"]: # Пройти по всем примерам этого интента, и положить текст в переменную example
        if isMathing(text, example): # Если текст совпадает с примером
  


      
  
  
  
  
  
  
  
  
  
  
  
  
  
  
   

