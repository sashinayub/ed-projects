
 
  <h3 align="center">Портфолио</h3>

  <p align="center">
        <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
   


<!-- Оглавление -->
<details>
  <summary>Оглавление</summary>
  <ol>
    <li><a href="#about-the-project">О портфолио</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- О портфолио -->
## О портфолио

В портфолио нет проектов из коммерческого опыта в бизнес-аналитике/системной аналитике, но есть работы решения задач, приближенных к задачам реального бизнеса.

Выполнены практические работы по основным модулям:
* сбор, документирование и анализ требований
* анализ, оптимизация, моделирование бизнес-процессов, работа в BusinessStudio
* создание диаграмм в нотациях CFFC, EPC, BPMN, IDEF0 для описания бизнес-процессов
* UML, User Story, Use Case, ER-диаграммы для описания ПО
* работа с инструментами Miro, Draw.io, Figma, BPMN.io, BusinessStudio
* работа с библиотеками Pandas, NumPy, SciPy, Matplotlib, PyMongo, SQLAlchemy, Seaborn
* операции с файлами csv, xlsx, коллекциями MongoDB, DataFrame
* базы данных и SQL (начальный уровень)
* работа в Anaconda (Jupiter Notebook), Google Colab, MS SQL, MySQL, PostgreSQL
* API
* подготовка данных и создание дашбордов в PowerBI 


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example **steps**.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Создание диаграмм в нотациях CFFC, EPC, BPMN, UML, IDEF0 -->
## Создание диаграмм в нотациях CFFC, EPC, BPMN, IDEF0 для описания бизнес-процессов

В зависимости от поставленной задачи исследования бизнес-процесса были составлены диаграммы в нотациях CFFC, EPC, BPMN, IDEF0. В ряде диаграмм представлены модели бизнес-процессов AS IS и далее они изменены в учетом целей оптимизации бизнес процесса - модель TO BE. Эти модели отражают бизнес-процессы, системы и архитектурные решения, обеспечивая их визуализацию и анализ. Каждая диаграмма выполнена с учетом специфики нотации. Использовались инструменты визуализации Miro, Draw.io, Figma, BPMN.io, BusinessStudio.
<img width="1220" height="588" alt="image" src="https://github.com/user-attachments/assets/5a54e7f5-213b-4718-8285-57548a03d153" />
<img width="624" height="606" alt="image" src="https://github.com/user-attachments/assets/6d1c6c0e-cab4-4366-b8da-e00d6bd3c301" />
<img width="1199" height="854" alt="image" src="https://github.com/user-attachments/assets/a2c460e6-49b9-41b6-983b-ce8c4debf3d9" />




Больше диаграмм в ["Диаграммы бизнес-процессов (различные нотации)"](https://github.com/sashinayub/ed-projects/tree/bc53e6a761a129aac003ed7d2c635237665eb1c0/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D0%B2%20(%D1%80%D0%B0%D0%B7%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D0%B5%20%D0%BD%D0%BE%D1%82%D0%B0%D1%86%D0%B8%D0%B8))

<!-- Pandas, PyMongo, чтение и запись данных, мат.статистика -->
## Pandas, PyMongo, Numpy и другие библиотеки, чтение и запись данных, базовая математическая статистика

- [x] работа в Google Colab с **Pandas и библиотекой для визуализации данных Matplotlib**, создание и объединение данных о температуре воздуха в различных городах в DataFrame, работа с файлами csv, xlsx, форматирование столбцов, даты, разделителей
<img width="624" height="538" alt="image" src="https://github.com/user-attachments/assets/0cb6d271-4b1f-464d-b76c-f3a0c43804c0" />

- [x] в Jupiter Notebook **с применением urllib.request были получены данные о погоде с сайта weatherapi.com** в формате json, данные отформатированы, получен почасовой прогноз погоды, загружен в DataFrame и сохранен в формате csv

<img width="624" height="332" alt="image" src="https://github.com/user-attachments/assets/d35ffb64-7149-4f02-a4d9-b44cfaeb0def" />

- [x] с исользованием **SQLAlchemy и psycopg2** из БД PostgreSQL загружены и сохранены в виде xlsx данные с аналитикой рейтинга фильмов
<img width="624" height="556" alt="image" src="https://github.com/user-attachments/assets/134f9909-4fa8-422d-80ef-047e0903ff4f" />

- [x] c применением Pymongo проведена работа **с коллекциями MongoDB**: чтение, подчсет количества доступных коллекций и документов, преобразование списка документов в Pandas DataFrame, сохранение в xlsx
<img width="624" height="416" alt="image" src="https://github.com/user-attachments/assets/599bee9c-10b8-4a9d-95ea-e37b0d39676f" />

- [x] в рамках изучения базовой математической статистики для Data Scientist с использованием библиотек Pandas, Numpy, SciPy, Matplotlib, Seaborn проведен **анализ метрик данных сервиса по аренде велосипедов**: построены гистограммы распределения, найдены статистические показатели, сделаны выводы о наличии аномалий, построен доверительный интервал, создана корреляционная матрица и heatmap по метрикам, сделаны выводы о наличии связей

<img width="624" height="572" alt="image" src="https://github.com/user-attachments/assets/2ec5b9e4-a03a-468d-8a8a-86588fb00004" />
<img width="624" height="695" alt="image" src="https://github.com/user-attachments/assets/0b88fba9-f60c-4097-ae7b-ab21b4f8b719" />

- [x] проведен **анализ эффективности маркетинговой акции для клиентов онлайн-игры** через сравнение метрик тестовой и контрольной группы игроков на 3 платформах с помощью доверительных интервалов от средних значений с точностью 95%. Исходные данные содержатся в 5 таблицах в формате csv. Были использованы библиотеки Pandas, Numpy, Matplotlib.pyplot, Seaborn, Scipy. Предварительно из данных были удалены данные по читерам (игроки, которые с помощью взлома игры начисляют себе большие объёмы внутриигровой валюты). После всех вычислений в Power BI были построены графики сравнения метрик по дням и матрица с ARPU по группам и платформам. Сделаны выводы, стоит ли проводить маркетинговую акцию в дальнейшем.
 
* _Код для создания DataFrame cheaters и удаления выявленных читеров:_
 ```sh
df_chiters = pd.read_csv('Cheaters.csv')
df_chiters = df_chiters.loc[(df_chiters['cheaters'] == 1)] #фильтруем по 1
list_of_chiters = df_chiters['user_id'].tolist() #создадим список с id
print(len(set(list_of_chiters))) #в списке 353 выявленных читера
 ```

* _Код для построения графиков (на примере платформы PC):_
 ```sh
plt.hist(df_pc_test['cash'], bins=40, alpha=0.3, label='test') 
plt.hist(df_pc_control['cash'], bins=40, alpha=0.3, label='control')

plt.axvline(ci_test[0], color='blue', linewidth=1) 
plt.axvline(ci_test[1], color='blue', linewidth=1)
plt.axvline(ci_control[0], color='orange', linewidth=1)
plt.axvline(ci_control[1], color='orange', linewidth=1)

plt.title('Сравнение cash в тестовой и контрольной группах пользователей PC')
plt.ylabel('Frequency') 
plt.xlabel('Cash')
plt.legend(loc='upper right') 
plt.savefig('pc.png')
plt.show()
 ```
<img width="741" height="523" alt="image" src="https://github.com/user-attachments/assets/d5497678-4c2e-4a79-bd5e-7e936ebb3224" />

<img width="624" height="170" alt="image" src="https://github.com/user-attachments/assets/3f1e26d8-f937-4cb0-b382-c14028d9b09f" />

<img width="624" height="171" alt="image" src="https://github.com/user-attachments/assets/4a614c59-0fd1-4a23-80b3-da76267461d0" />

Подробнее в ["Pandas, PyMongo, чтение и запись данных, мат.статистика, PowerBI"](https://github.com/sashinayub/ed-projects/tree/1fafda1685315d366234babb5c6d2f96fffdaf9b/Pandas%2C%20PyMongo%2C%20%D1%87%D1%82%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%2C%20%D0%BC%D0%B0%D1%82.%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0%2C%20PowerBI) 



<!-- Python -->
## Python

Уровень опыта работы с Python включает знание основ синтаксиса, работу с переменными и типами данных, использование условных операторов и циклов. Также освоены функции, работа с коллекциями и базовые модули для обработки файлов и исключений. 
1. Функции
2. Возврат значений из функции return, алгоритмы с заданной точностью для расчёта
3. Вложенные циклы
4. Float, round, math
5. Open a Pull Request

* _Задача "Среднее на отрезке": напишите программу, которая считывает с клавиатуры три числа a, b и c, считает и выводит на консоль среднее арифметическое всех чисел из отрезка [a; b], кратных числу c._
 ```sh
a = int(input('Введите первое число (a): '))
b = int(input('Введите второе число (b): '))
c = int(input('Введите третье число (c): '))
summ = 0
count = 0
for number in range(a + 1, b):
  if number % c == 0:
    summ += number
    count += 1
if summ == 0:
  print('Чисел из отрезка [a; b], кратных числу c, не найдено. Запустите программу снова.')
else:
  print('Среднее арифметическое всех чисел из отрезка а:b: ', summ/count)
 ```

* _Задача "Сумма ряда"
Дано натуральное число N. Напишите программу для вычисления суммы N элементов последовательности по формуле (−1)n∙12n , где n — это порядковый номер элемента (расчёт начинается с нуля)._
 ```sh
n = int(input('Введите №: '))
summ = 0
for number in range(0, n):
  elem = ((-1)**number) * ((1/2)**number)
  summ += elem
print('Ответ:', summ)
 ```

* _Задача "Число наоборот": пользователь вводит два числа: N и K. Напишите программу, которая заменяет каждое число на число, которое получается из исходного записью его цифр в обратном порядке, затем складывает их, снова переворачивает и выводит ответ на экран._
 ```sh
def turn_over(num):
  count = 0
  while num > 0:
    count = count * 10 + num % 10
    num = num // 10
  return count
n = int(input('Введите первое число: ')) 
k = int(input('Введите второе число: ')) 
summ = turn_over(n) + turn_over(k)
print('Первое число наоборот:', turn_over(n))
print('Второе число наоборот:', turn_over(k)) 
print('Сумма:', summ) 
print('Сумма наоборот:', turn_over(summ))
 ```

* _Задача "Текстовый редактор": напишите код, который считает, сколько раз в тексте встречается любая выбранная буква или цифра. Напишите функцию count_letters(), которая принимает на вход текст и подсчитывает, какое в нём количество цифр K и букв N._ 
 ```sh
text = input('Введите текст: ')

def count_letters(text, number, letter):
  count_number = 0
  count_letter = 0

  for i in text:
    if i == number:
      count_number += 1
    elif i == letter:
      count_letter += 1
  print('Количество цифр ', number, ':', count_number)
  print('Количество букв ', letter, ':', count_letter)

number = input('Какую цифру ищем? ')
letter = input('Какую букву ищем? ')
count_letters(text, number, letter)
 ```
Ссылка на папку с работами ["Python"](https://github.com/sashinayub/ed-projects/tree/47021c3ff6ed45bfe98d08142ad12bb21718d8b4/Python)

<!-- CONTACT -->
## Contact

Сашина Юлия - [@IuliiaSash](https://twitter.com/@IuliiaSash) - sashinayub@gmail.com

Дополнительная ссылка на портфолио на GoogleDisc: [портфолио](https://drive.google.com/drive/u/0/folders/1L3FnoYx98lNab2a6SJjh6Fnkux_SrnDB)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 













решения задач, приближенных к задачам реального бизнеса:
• написание различных SQL-запросов (MS SQL, MySQL, PosgreSQL) для извлечения необходимых данных для аналитики:
Select со всеми его возможностями…
Объединение данных из различных таблиц, в т.ч. Join
Применение оконных функций при количества…
Построение таблицы продаж товаров
Решение бизнес-кейсов на языке Python
Аналитика активности пользователей платформы
Создала дашборд в PowerBI (подключила базу данных ____ к PowerBI, написала SQL—запросы для построения визуализаций, собрала дашборд «Анализ…, сформулировала гипотезы и провела их тестирование, результаты тестирования»
ТЗ
спецификации
