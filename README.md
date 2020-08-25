
<!------# quiz

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
=======
------>
# Quiz-WebApp-Vue.js

🤓 Fact: I'm learning Vue.js. This app will be growing while my knowledge in Vue grows. My next challenge is to integrate Typescript. 

📝 Quiz WebApp displays a maximum of 20 'general knowledge' questions and gives the user multiple choice answers.

🔨 It's being built using Vue.js, Bootstrap-vue and an external API. 

🎙 The readme will be updated as the app grows and I start to implement new features. 


## Client-side details


GET/api/values

Response Body:


```JSON

{
    "response_code": 0,
    "results": [
        {
            "category": "General Knowledge",
            "type": "multiple",
            "difficulty": "medium",
            "question": "When was the Declaration of Independence approved by the Second Continental Congress?",
            "correct_answer": "July 4, 1776",
            "incorrect_answers": [
                "May 4, 1776",
                "June 4, 1776",
                "July 2, 1776"
            ]
        },
        {
            "category": "General Knowledge",
            "type": "multiple",
            "difficulty": "medium",
            "question": "What is the defining characteristic of someone who is described as hirsute?",
            "correct_answer": "Hairy",
            "incorrect_answers": [
                "Rude",
                "Funny",
                "Tall"
            ]
        },
         {
            "category": "General Knowledge",
            "type": "multiple",
            "difficulty": "easy",
            "question": "Area 51 is located in which US state?",
            "correct_answer": "Nevada",
            "incorrect_answers": [
                "Arizona",
                "New Mexico",
                "Utah"
            ]
        }
        ]
        
 
 ```

- API values that currently are dynamic:

  ⚡️ Difificulty: It's been set up that serves a random level (Easy, Medium or Hard)
  
  

