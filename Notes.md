# CSS 
## Intro
![image](https://github.com/user-attachments/assets/c34172f7-b17c-4961-a16e-7de30bec1d2f)<br><br>
![image](https://github.com/user-attachments/assets/cc737ea2-8285-4d15-9ed2-1078dd727205)<br><br>
### Three ways to write CSS
**Inline CSS**<br>
Use the style attribute on any HTML tag. eg. `<body style="background-color: aqua;">`<br>
![image](https://github.com/user-attachments/assets/108f1837-5ea4-4401-9786-f2a6acd9f33a)<br><br>
![image](https://github.com/user-attachments/assets/87ebca7e-40da-45f1-aba2-60dc0a995b77)<br><br>

**Internal CSS**<br>
Use the  style tag inside the head tag. eg. `<style> body {background-color: red;} </style>`<br>
![image](https://github.com/user-attachments/assets/898bcf3f-822e-477f-9bb4-5e77a07d4ec2)<br><br>
![image](https://github.com/user-attachments/assets/0f66932e-bd1c-4318-ae5f-72623fbf70ce)<br><br>

**External CSS**<br>
Write a seperate .css file and link that to HTML document.  <br>
**HTML File**<br>
![image](https://github.com/user-attachments/assets/b2fe8ae9-a20b-46f5-b22e-e3000b682bb2)<br><br>

**CSS File**<br>
![image](https://github.com/user-attachments/assets/c009e4be-4707-415b-abf3-f266e88f3bf9)<br><br>

![image](https://github.com/user-attachments/assets/b0b2541c-06f3-4e23-9ce6-5912958e62a4)

### Target HTML elements
**Using tag name**<br>
For this, we simply use the tag name in our css. All the elements in our document with the same tag name will get those styles.<br>

**Using class name**<br>
For this, we simply write styles for a class. To write styles we use `.class_name{<styles>}`. Then we apply these styles on
HTML elements. All elements with the class name will get the styles. <br>

**Using id**<br>
For this, we write styles for an id given to an HTML element. We use it like `#id{<styles>}`.  Styles will be applied to the 
HTML element that has the id. <br>

**HTML**<br>
![image](https://github.com/user-attachments/assets/1ebc3ce4-1a71-417c-b849-b3fe370e8611)<br><br>

**CSS**<br>
![image](https://github.com/user-attachments/assets/12352c56-ccbb-4bea-b11c-affe0b69069b)<br><br>

## Fonts
Use the font family property to set fonts. 
We usually list more than one fonts in the font family property. If first font is not available, second font is applied and so on.  
### HTML
![image](https://github.com/user-attachments/assets/3aaf2bf3-0138-4332-b7b3-9a9e6cc15bf9)

### CSS
![image](https://github.com/user-attachments/assets/9f0f58b8-4e57-4bbb-b3bf-32cc4fb4a2e9)

## Borders
See the relation between border, margin and padding.  
![margin-border-padding](https://github.com/user-attachments/assets/f56d66b5-fd0c-4ee5-bbf9-aca5405b52a2)

### HTML
![image](https://github.com/user-attachments/assets/4681b1d2-bfe7-4e37-a2cb-50e2a6638381)

### CSS
![image](https://github.com/user-attachments/assets/4ee1d96e-3a9c-4d7e-9aed-7e8f18c15330)

## Backgrounds
![image](https://github.com/user-attachments/assets/0bc5afc1-2b9c-461b-aebe-2b16d75362ba)

## Margins
Margin is the space around an element. This is outsude the element/border.
Padding is the space between the element border and the content. 
### HTML
![image](https://github.com/user-attachments/assets/a6d0e203-f37b-4543-911c-1be0e6b8ca3e)

### CSS
![image](https://github.com/user-attachments/assets/d39be2d3-7dff-4eae-ab79-3cd490669558)

### Viewport
![image](https://github.com/user-attachments/assets/e0d5120a-fb59-4682-8c87-46ca5bd284e7)

## Float
### HTML
![image](https://github.com/user-attachments/assets/8a41a29c-ba97-4f13-b978-917f3b02c0ff)

### Without Float
![image](https://github.com/user-attachments/assets/db235a37-9c8c-477a-aaf8-698118bb29d4)

### With float: left
![image](https://github.com/user-attachments/assets/dc2dae02-b1f7-4729-93d3-416838ca41ca)

### With float: right
![image](https://github.com/user-attachments/assets/63b00f1b-5134-4895-871e-4d923eabc51d)

### CSS
![image](https://github.com/user-attachments/assets/d28aeb53-30c8-4368-947c-8d3e69f3f5c6)

## Pseudo Classes
Pseudo Classes are applied to element when they are in a special state.
For example, when you hover over a button, or click it or more.<br>
### HTML
![image](https://github.com/user-attachments/assets/5c08add2-68b5-434f-b8f9-174c329447c4)

### CSS
![image](https://github.com/user-attachments/assets/7b00af65-9a10-4cc4-95b1-74e5a9842ad3)

## Shadows
### HTML
![image](https://github.com/user-attachments/assets/645a059d-4c75-462f-8439-d818de24e7e2)

### CSS
![image](https://github.com/user-attachments/assets/62f32275-7208-42f9-98d6-e45fc1cf23a0)

### Output
![image](https://github.com/user-attachments/assets/5a077445-4ee9-47fa-ba36-bfda8de7fb72)

## Icons
We can use `https://fontawesome.com/` for free and good icons.  
### HTML
![image](https://github.com/user-attachments/assets/2591727c-a26e-4a69-80f6-5490ae176297)

### CSS
![image](https://github.com/user-attachments/assets/84213ba6-9896-43b3-ab44-44f8db59b8e7)

## Transform
### HTML
![image](https://github.com/user-attachments/assets/d1a737c3-4f73-499e-a438-0d73e343eedb)

### CSS
![image](https://github.com/user-attachments/assets/14a7be84-2629-4f0c-a58a-3ca3c07876d6)

## Animations
### HTML
![image](https://github.com/user-attachments/assets/d5503dc5-576b-4850-8f9d-86b2cf86cbcb)

### CSS
![image](https://github.com/user-attachments/assets/f9cbb223-0e10-4dc5-975b-eb7acc0d56f3)
