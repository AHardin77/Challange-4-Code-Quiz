# Challange 4 Code Quiz 📫 🚀 💡 

💡 Code quiz Challenge 4  What this codes does is  
An app will run in the browser, and will feature dynamically updated HTML and CSS powered by JavaScript code. 

When you click on the start button you will be prompted with a timer and presented with a question. 
Once you complete a question you will be presented with the next question with total of 5 questions in 10 minutes. 
When all questions are answered or the timer reaches 0 the quiz is done. 

You will see at the bottom of the page if you got the questions correct or incorrect. 

WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
## 🔗 Links
 🚀 Deployed application Link-

## Screenshots
📫 Links to screenshots below! 
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 🚀 Acknowledgements 

 - Technologies Used 
 - HTML
 - CSS
 - Javascript 
## 🚀 Resources Used 

💡Resources Sites used for referance and inperation. 

[HTML and CSS: Design and Build Websites 1st Edition](Author-Jon Duckett)
https://www.w3schools.com/js/ 
https://developer.mozilla.org/en-US/docs/Learn/MathML
## 🚀 Authors

-💡Authors @AHardin77

## 🚀 Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

