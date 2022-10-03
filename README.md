# Hackathon_MAIS_2022
![wordBay](https://user-images.githubusercontent.com/97472150/193475409-91da0c5a-a6f6-4424-bfbc-6908d958bc79.jpg)

<b>What it does:</b>
WordBay offers a platform for people who often read long and complicated texts online. It allows its users to quickly and easily find the definition to any word on a website by using a simple keyboard shortcut. By highlighting a word and using the shortcut, the user is presented with a beautiful graphical interface listing out the best definition, synonyms, examples and links related to the selected word. To avoid inconsistent data, we made sure that any string that contains spaces is not considered in the word search.

<b>How we built it:</b>
To build WordBay, we had to use a variety of technologies and programming languages.

Firstly, we had to figure out that the chrome extension was the best idea for this project. It quickly became a realization that it was the best solution as it offered us the possibility of injecting html, css and javascript into any webpage of our choice.

We then had to structure the application into its respective aspects:
Frontend
  Content/content.js
  Content/content.css
Backend
  Backgrounds/background.js
  Python_backend/main.py
Using python and flask for the backend was the best way to communicate between our app components using a REST API. We essentially communicated the selected words and some definitions to the python API which handles the AI and returns the predicted data.

<b>Built with:</b>
api,
chrome,
css3,
flask,
html5,
javascript,
natural-language-processing,
python,
rest,
spacy,
web-dev,

![example1](https://user-images.githubusercontent.com/97472150/193475662-8dbd948b-ac2e-49d5-b1e5-ae4e47f582c9.jpg)
![example1 1](https://user-images.githubusercontent.com/97472150/193475668-f5c478f1-23a3-49bd-bdd1-fff45b295237.jpg)

