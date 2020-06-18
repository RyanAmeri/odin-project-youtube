# A static implementation of the YouTube Video Player 
## Requirements
This page is created to fulfill the requirements for the Odin Project create YouTube Player project. 
Further infornation can be found at [The Odin Project](https://www.theodinproject.com/courses/html-and-css/lessons/embedding-images-and-video)
## Learnings
* The main requirment for this project was to learn embeding video and audio objects and images. Embeding external iframe for the YouTube Player fell into the same category. 
* I took the requirements further and tried to use SVG for all icons and to create a responsive layout using CSS Grid. 
* I learned a lot about building the wireframes of the page using CSS Grid and got to practice creating all kinds of grids. 
* I also learnt how to create a responsive iframe using the padding-bottom /padding-top CSS hack. I tried to use the new CSS property aspect-ratio but that's still not supported in most browsers. 
* The images were all downloaded from Unsplash and are free for use
* The SVG icons were all obtained from icomoon and are free for use. 
## Further Improvements
* I embeded the SVG definitions and paths directly in the HTML to allow me to style them from CSS. For a small page such as this this method would work but ideally I should store the SVG files separately and use the <object> tag to bring them into the HTML file. That would also result in cleaer HTML layout. 
* Various functionality was left unimplemented because they took too much time and I had to draw the line somewhere!
## Reflections
* I hate this way of writing CSS. I can see the value of something like tailwind or styled components. These classes are meaningless and it essentially becomes inline styles anyway