# The Old Money Outfit Landing Page

Welcome to The Old Money Outfit landing page! This is a simple and elegant webpage that showcases the timeless elegance of old money outfits. Feel free to explore the features, installation instructions, and show your support by starring the GitHub repository.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation / Fork](#installation--fork)
4. [Star the GitHub Repo](#star-the-github-repo)
5. [Code of the Website](#code-of-the-website)

## Introduction

The Old Money Outfit landing page is designed to highlight the sophistication, understated luxury, and refined sense of style that old money outfits represent. The webpage features a clean layout, muted colors, and high-quality images that capture the essence of timeless fashion.

<img src="https://drive.google.com/uc?export=view&id=1WTbdjiP7cJbIwFM6LA2ox411kC8XKtP4" alt="Gojo Satoru Image" style="width: 100%; max-width: 600px; height: auto; margin: 20px 0;">
<a href="https://ramxcodes.github.io/The-Old-Money-Landing-page" target="_blank" style="display: inline-block; padding: 10px 20px; background-color: #3498db; color: #fff; text-decoration: none; border-radius: 5px; font-weight: bold; font-size: 16px; margin-bottom: 20px;">Visit Website ↗</a>


## Features

- Clean and elegant design
- Responsive layout for various screen sizes
- Details section showcasing the characteristics of old money outfits
- Interactive color display

## Installation / Fork

To run or contribute to this project, follow these steps:

1. Fork the repository.
2. Clone the forked repository to your local machine.
   ```bash
   git clone https://github.com/ramxcodes/old-money-outfit-landing-page.git
   ```
3. Open the `index.html` file in your preferred web browser.

## Star the GitHub Repo

If you find this project interesting or useful, show your support by starring the GitHub repository. Click on the "Star" button at the top-right corner of the page.

## Code of the Website

The HTML and CSS code for the landing page is provided below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The old money outfit landing page</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css"
    rel="stylesheet"
/>
</head>
<body>
    <div id="main">
        <div id="left">
            <h1>The Old <br>Money.</h1>
            <div id="bottom-left">
                <div id="color">
                    <h5>colors</h5>
                    <div id="color1"></div>
                    <div id="color2"></div>
                </div>
                <h2>Details</h2>
                <p>Old money outfits exude timeless elegance, characterized by tailored 
                    silhouettes, muted colors, and high-quality fabrics. They reflect a 
                    heritage of sophistication, understated luxury, and a subtle, 
                    refined sense of style.</p>
            </div>
        </div>
        <div id="right">
            <div id="right-top">
                <h4>$999</h4>
                <h5>Rating <i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i></h5>
            </div>
            <img src="https://i.pinimg.com/736x/fb/ac/2a/fbac2a82424818fbe5f757be1693d274.jpg" alt="img">
            <div id="black">
                <h5>add to bag</h5>
            </div>

            <h2 id="rotated">
                The Ultimate Outfit
            </h2>
        </div>
        <footer>
            <p>Made with ❤️ <a target="_blank" href="https://github.com/ramxcodes">Ram</a></p>
        </footer>
    </div>
</body>
</html>

```

```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'montserrat';
}

html, body{
    height: 100%;
    width: 100%;
}

#main{
    height: 100%;
    width: 100%;
    /* background-color: red; */
    display: flex;
    align-items: flex-end;
    /* justify-content: space-between; */
    padding: 0px 90px;
    padding-top: 170px;
    gap: 80px;
}

#left{
    height: 100%;
    width: 45%;
    /* background-color: red; */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-bottom: 50px;
}


#left h1{
    /* font-size: 125px; */
    font-size: 7.3vw;
    font-weight: 500;
    font-family: work sans;
    line-height: 7.5vw;
}

#bottom-left{
    width: 100%;
    /* background-color: yellow; */
}

#color{
    /* background-color: blue; */
    width: fit-content;
    padding: 8px 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50px;
    border: 1px solid black;
}
#color h5{
    font-size: 20px;
    margin-right: 10px;
    font-weight: 500;
}

#color1{
    height: 20px;
    width: 20px;
    background-color: #b3883f;
    border-radius: 50%;
    margin: 3px;
}

#color2{
    height: 20px;
    width: 20px;
    background-color: #e7bc88;
    border-radius: 50%;
}

#left h2{
    margin-top: 50px;
    /* font-size: 30px; */
    font-size: 1.5vw;
    margin-bottom: 10px;
}

#left p{
    font-size: 1vw;
    width: 60%;
    font-weight: 600;
    color: #444;
    line-height: 1.5vw;
}


#right{
    height: 90%;
    width: 33%;
    /* background-color: blue; */
    position: relative;
}

#right-top{
    height: 50px;
    width: 100%;
    /* background-color: red; */
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-right: 20px;
}

#right-top h4{
    font-size: 30px;
    font-weight: 600;
    font-family: work sans;
}
#right-top h5{
    font-size: 16px;

}
#right-top h5 i{
    color: goldenrod;
}

#right img{
    width: 100%;
    height: 88%;
    object-fit: cover;
    border-radius: 10px;
}

#black{
    position: absolute;
    height: 150px;
    width: 150px;
    background-color: rgb(9, 6, 37);
    color: white;
    border-radius: 50%;
    right: -18%;
    top: 20%;
    display: flex;
    align-items: center;
    justify-content: center;
}

#black h5{
    font-size: 20px;
    font-weight: 400;
}

#rotated{
    position: absolute;
    left: -8%;
    bottom: 2%;
    /* background-color: red; */
    rotate: -90deg;
    transform-origin: 0 0;
    font-size: 30px;
    font-weight: 600;
}

@media (max-width:600px) {
    #main{
        height: 100%;
        width: 100%;
        /* background-color: red; */
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
        flex-direction: column;
        padding: 40px;
        padding-top: 40px;
        gap: 20px;
    }
    #left{
        height: fit-content;
        width: 100% ;
        /* background-color: red; */
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding-bottom: 50px;
        gap: 30px;
    }
    
    
    #left h1{
        /* font-size: 125px; */
        font-size: 17.3vw;
        font-weight: 500;
        font-family: work sans;
        line-height: 17.5vw;
    }
    
    #bottom-left{
        width: 100%;
        /* background-color: yellow; */
    }
    
    #color{
        /* background-color: blue; */
        width: fit-content;
        padding: 5px 12px;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 50px;
        border: 1px solid black;
    }
    #color h5{
        font-size: 12px;
        margin-right: 5px;
        font-weight: 500;
    }
    
    #color1{
        height: 15px;
        width: 15px;
        background-color: #b3883f;
        border-radius: 50%;
        margin: 3px;
    }
    
    #color2{
        height: 15px;
        width: 15px;
        background-color: #e7bc88;
        border-radius: 50%;
    }
    
    #left h2{
        margin-top: 20px;
        /* font-size: 30px; */
        font-size: 4.5vw;
        margin-bottom: 8px;
    }
    
    #left p{
        font-size: 2.5vw;
        width: 90%;
        font-weight: 600;
        color: #444;
        line-height: 3vw;
    }

    
    #right{
        height: fit-content;
        width: 100%;
        /* background-color: blue; */
        position: relative;
        display: flex;
        flex-direction: column-reverse;
    }

    #right-top{
        height: 50px;
        width: 100%;
        /* background-color: red; */
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-right: 0px; 
    }

    #right-top h4{
        font-size: 25px;
        font-weight: 600;
        font-family: work sans;
    }
    #right-top h5{
        font-size: 16px;

    }
    #right-top h5 i{
        color: goldenrod;
    }

    #right img{
        width: 100%;
        height: 88%;
        object-fit: cover;
        border-radius: 5px;
    }

    #black{
        position: absolute;
        height: 80px;
        width: 80px;
        background-color: rgb(9, 6, 37);
        color: white;
        border-radius: 50%;
        right: -10%;
        top: -6%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    #black h5{
        font-size: 10px;
        font-weight: 400;
    }

    #rotated{
        position: absolute;
        left: 0%;
        top: -6%;
        /* background-color: red; */
        rotate: 0deg;
        transform-origin: 0 0;
        font-size: 22px;
        font-weight: 700;
    }
    footer{
        align-items: center;
        text-align: center;
    }
}

```

Feel free to explore and customize the code to suit your preferences.

---

Made with ❤️ by [Ram](https://github.com/ramxcodes).
