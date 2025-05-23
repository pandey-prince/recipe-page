# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Deployment](#deployment)



## Overview

In this project I have created a recipe page using HTML and CSS.
### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/pandey-prince/recipe-page)
- Live Site URL: [Add live site URL here](c:\Users\princ\Desktop\Web Development\frontend mentor\Recipe           page\recipe-page-main\recipe-page-main\design\desktop-design.jpg)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

In this project I learned about creating a recipe page.



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Page</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&
    family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Outfit:wght@100..900&
    family=Roboto:ital,wght@0,100..900;1,100..900&family=Young+Serif&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,
    300..900&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Outfit:wght@100.
    .900&family=Roboto:ital,wght@0,100..900;1,100..900&family=Young+Serif&display=swap" rel="stylesheet">
</head>
<body>
    <div class="recipe-container">
        <div class="recipe-img">
            <img src="/images/image-omelette.jpeg" alt="image-omelette">
        </div>
        <div class="recipe-details">
            <div class="header">
                <p class="heading">
                    Simple Omelettee Recipe
                </p>
                <p class="speciality">
                    An easy and quick dish, perfect for any meal.
                    This classic omelette combines beaten eggs cooked to perfeciton,
                    optinally filled with your choices of cheese,vegitables, or meats.
                </p>
            </div>
            <div class="time">
                <p class="prepation-time">Preparation time</p>
                <ul>
                    <li>
                        <span>Total: </span> Approximately 10 minutes
                    </li>
                    <li>
                        <span>Preparation:</span> 5 minutes
                    </li>
                    <li>
                        <span>Cooking:</span>5 minutes
                    </li>
                </ul>
            </div>
            <div class="ingredients">
                <p>Ingredients</p>
                <ul>
                    <li>2-3 large eggs</li>
                    <li>Salt, to taste</li>
                    <li>Pepper, to taskte</li>
                    <li>1 tablespoon of butter or optinally</li>
                    <li>
                        Optional fillings: cheese, diced vegitables, cooked meats,herbs
                    </li>
                </ul>
            </div>
            <div class="instructions">
                <p>Instructions</p>
                <ol>
                    <li>
                        <span>Beat the eggs:</span>
                        In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.
                        You can add a tablespoon of water or milk for a fluffier texture.
                    </li>
                    <li>
                        <span>Heat the pan:</span>
                        Place a non-stick frying pan over medium  heat and add butter or oil.
                    </li>
                    <li>
                        <span>Cook the omelette:</span>
                        Once the butter is melted and bubbling, pour in the eggs.
                        Tilt the pan to ensure the eggs evenly coat the surface
                    </li>
                    <li>
                        <span>Add fillings(optional):</span>
                        When the eggs begin to set at the edges but are still slightly runny in the middle,
                        sprinkel your chosen fillings over one half of the omelette.
                    </li>
                    <li>
                        <span>Fold and serve:</span>
                        As the omelette continues t cook, carefully lift on eedge and fold it 
                        over the fillings. Let it cook for another minutes, then slide it onto a plate.
                    </li>
                    <li>
                        <span>Enjoy:</span>
                        Serve hot, with additional salt and pepper if needed.
                    </li>
                </ol>
            </div>
            <div class="nutrituion">
                <p class="newpara">Nutrituion</p>
                <p class="newpara2">
                    The table below shows nutirtional values per serving without the additional fillings.
                </p>
                <table>
                    <tr>
                        <td class="col1">Calories</td>
                        <td class="col2">277kcal</td>
                    </tr>
                    <tr>
                        <td class="col1">Carbs</td>
                        <td class="col2">0g</td>
                    </tr>
                    <tr>
                        <td class="col1">Protein</td>
                        <td class="col2">20g</td>
                    </tr>
                    <tr>
                        <td class="col1">Fat</td>
                        <td class="col2">22g</td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
    
</body>
</html>
```
```css
body{
    background-color: hsl(30, 54%, 90%);
    display: flex;
    align-items: center;
    justify-content: center;
    padding-bottom:20px;
}
.recipe-container{
    display:flex;
    flex-direction: column;
    background-color:white;
    width:550px;
    align-items: center;
    border-radius: 8px;


}

.recipe-img img{
    margin-top:15px;
    border-radius: 8px;
    width:500px;
}



.recipe-details{
    display: flex;
    flex-direction: column;
    width:500px;
}

.heading{
    font-family: Young serif, Arial;
    font-weight: 700;
    color:hsl(24, 5%, 18%);
    font-size:24px;
    margin-bottom:20px;
}

.speciality{
    font-family:Outfit, Arial;
    font-weight: 400;
    color:hsl(30, 10%, 34%);
    margin-top:0;
}

.time{
    background-color:  hsl(330, 100%, 98%);
    font-family:Outfit, Arial;
    padding-left:18px;
}
.time p{
    color:hsl(332, 51%, 32%);
    font-weight: 700;
}


.time ul li {
    font-weight: 400;
}

.ingredients p,
.instructions p,
.newpara{
    font-family:Young serif, Arial;
    font-size:22px;
    color:hsl(14, 45%, 36%);
    font-weight: 500;
    margin-bottom: 0;
}

.ingredients ul,
.instructions ol,
.newpara2,
.col1{
    color:hsl(30, 10%, 34%);
    font-weight: 400;
    font-family:Outfit, Arial
}

.time ul span,
.instructions span
{
    font-weight: 500;
    color:hsl(24, 5%, 18%);
    
    
}

.col2{
    color:hsl(14, 45%, 36%);
    font-weight: 600;
    padding-left:150px;
}

.instructions,
.ingredients,
td{
    border-bottom: 1px solid hsl(30, 10%, 34%);
}


.instructions span{
    margin-left:5px;
}

table{
    margin-left:30px;
}

.instructions ol li{
    margin-bottom: 10px ;
}
```




### Deployment

-  I used vercel.com for the deployment.
