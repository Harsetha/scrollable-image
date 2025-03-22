# scrollable-image
## DATE: 22-03-2025
## NAME: HARSETHA J

## Aim: Design and implement an interactive image gallery using JavaScript, HTML, and CSS. The gallery should meet the following requirements:

## Task: Display multiple images in a horizontal scrollable layout. Each image must have a caption that appears when hovered over. Include Next and Previous buttons to navigate through the images. Use JavaScript to enhance interactivity (e.g., smooth sliding animations, hover effects). Style the gallery using CSS for a visually appealing and responsive design. Include a footer at the bottom of the page with the text "Learner's Name and Register Number". Your solution should include well-structured HTML, CSS, and JavaScript code, ensuring smooth user experience and navigation.
## Program
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galaxy Image Gallery</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            text-align: center;
            background: #000;
            color: white;
            padding: 20px;
        }
        .gallery-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr); 
            grid-template-rows: repeat(2, auto); 
            gap: 15px; 
            max-width: 90%;
            margin: auto;
        }
        .image {
            position: relative;
            border-radius: 8px;
            overflow: hidden;
        }
        .image img {
            width: 100%;
            height: auto;
            object-fit: cover;
            transition: transform 0.3s ease-in-out;
        }
        .image:hover img {
            transform: scale(1.1);
        }
        .caption {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.7);
            padding: 5px;
            text-align: center;
            font-size: 14px;
            display: none;
        }
        .image:hover .caption {
            display: block;
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background: #222;
            text-align: center;
        }
        
        @media (max-width: 800px) {
            .gallery-container {
                grid-template-columns: repeat(2, 1fr); 
                grid-template-rows: repeat(3, auto); 
            }
        }
        
        @media (max-width: 500px) {
            .gallery-container {
                grid-template-columns: repeat(1, 1fr); 
                grid-template-rows: repeat(6, auto); /
            }
        }
    </style>
</head>
<body>

    <h1>Galaxy Image Gallery</h1>
    
    <div class="gallery-container">
        <div class="image">
            <img src="c:\Users\admin\Downloads\img1.jpg" alt="Galaxy 1">
            <div class="caption">A stunning spiral galaxy glowing in the vast expanse of space, surrounded by countless stars</div>
        </div>
        <div class="image">
            <img src="c:\Users\admin\Downloads\img2.jpg" alt="Galaxy 2">
            <div class="caption">A breathtaking cosmic explosion, illuminating a galaxy filled with planets, meteors, and radiant energy.</div>
        </div>
        <div class="image">
            <img src="c:\Users\admin\Downloads\img3.jpeg" alt="Galaxy 3">
            <div class="caption">A mesmerizing deep-space nebula glowing with cosmic light, surrounded by distant planets and stars</div>
        </div>
        <div class="image">
            <img src="c:\Users\admin\Downloads\img4.jpeg" alt="Galaxy 4">
            <div class="caption">A brilliant galaxy shining in the depths of space, surrounded by countless distant stars</div>
        </div>
        <div class="image">
            <img src="c:\Users\admin\Downloads\img5.jpeg" alt="Galaxy 5">
            <div class="caption">A vibrant cosmic collision of galaxies, radiating brilliant red and blue hues across the universe</div>
        </div>
        <div class="image">
            <img src="c:\Users\admin\Downloads\img6.jpeg" alt="Galaxy 6">
            <div class="caption">A breathtaking cosmic night sky, where stars shimmer above glowing clouds in a celestial masterpiece</div>
        </div>
    </div>

    <footer> HARSETHA J | 212223220032 </footer>

</body>
</html>
```
## Output
![Screenshot (188)](https://github.com/user-attachments/assets/946f13b3-d841-4979-bd8b-0a6b3ad9e144)

![Screenshot (189)](https://github.com/user-attachments/assets/1aa36687-d9f1-41ab-b56e-5252ffc2960d)

## Result
This experiment is implemented using HTML,CSS and JS.
