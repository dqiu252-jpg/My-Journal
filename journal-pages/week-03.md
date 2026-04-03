---
layout: default
---

# Week 03

[← Back to Home](../index.md)

## Living Data

### Activity 1 
![alt text](<../assets/week-03/week 3 img1.png>)
![alt text](<../assets/week-03/week3 img2.png>)

*This sketch demonstrates how to fetch live data using APIs in p5.js. It retrieves current weather data from Open-Meteo and word information from a dictionary API. The data is displayed as text on the canvas. This helped me understand how APIs return structured data and how it can be accessed and used in code.*

Using cURL in the terminal, I explored different APIs like wttr.in and the Free Dictionary API. I learned how to request weather data using GPS coordinates by adding latitude and longitude to the URL. I also tried changing the language of the weather output by adding a language parameter, which showed the same data in a different language. I found that wttr.in can also show the current moon phase, which was interesting because it adds more environmental information beyond basic weather.

With the Free Dictionary API, I looked up synonyms and antonyms of a word, which helped me understand how APIs can return structured language data. I also explored extra features like getting extended forecasts and different output formats. This activity helped me understand how APIs work as systems for requesting and receiving live data.
## Activity 2
![alt text](<../assets/week-03/week3 img 3.png>)

This sketch translates live weather data into visual form. Temperature controls the colour of the circle, while wind speed controls its size. This shows how numeric data can be mapped to visual properties. By changing the location, the visual output changes, making the sketch dynamic and responsive to real-world conditions.

<video controls src="../assets/week-03/week3 ved1.mov" title="Title"></video>

This version adds randomness and animation to create a more expressive visualisation. The number of shapes increases with temperature, creating a more dynamic and abstract representation of weather. This explores how data can be combined with generative design to create more artistic outputs.

## Activity 3

My Protocol:
The data protocol is designed to record sound activity in a space and translate it into a visual form. The source of data is all the sounds happening in the immediate environment, such as people talking, typing, footsteps, or background noise. The aim is to focus on everyday sounds that are usually ignored and turn them into something visible.

The observations are recorded every 10 seconds. At each interval, the participant pauses and listens carefully to identify the most noticeable sound at that moment. This regular timing helps create a consistent flow of data over the duration of the activity.

Each sound is translated into a visual mark based on a set of rules. The volume of the sound determines the shape: loud sounds are represented by large circles, medium sounds by triangles, and quiet sounds by small dots. The type of sound is shown using colour, where human voices are blue, mechanical or object sounds are red, and background or ambient sounds are black. The position of each mark on the page reflects where the sound comes from in the space, such as left, right, or centre.

The activity continues for 10 minutes, creating a layered drawing of sound over time. Participants are encouraged to respond quickly and not overthink their decisions, focusing on their immediate perception. If multiple sounds occur at once, they should choose the most noticeable one.

This protocol aims to show how live data can be interpreted and visualised through simple rules. It also highlights how different people may produce different results even when following the same instructions.

## Independent Study

![alt text](<../assets/week-03/week3 img4.png>)
*(see [Link](https://editor.p5js.org/dqiu252/sketches/WwWGdlIr5) to try this out).*

I created a p5.js sketch that responds to live sound data using the computer’s microphone. This builds on my earlier data protocol, where I recorded sounds in a space and translated them into visual marks. Instead of manually observing and drawing, this version uses real-time audio input as a continuous data source.

The microphone captures sound levels from the environment, which are represented as numeric values between 0 and 1. I mapped these values to visual properties such as size and colour. Louder sounds produce larger shapes and brighter colours, while quieter sounds create smaller and softer visuals. I also added multiple shapes that appear across the screen to represent how sound spreads through space.

This visualisation reveals qualities of sound that are difficult to capture in a static drawing or written data. The movement and constant change of the shapes reflect the dynamic nature of sound. Unlike my hand-drawn version, which recorded sound at fixed intervals, this sketch responds instantly, showing subtle changes in volume in real time. This creates a more immersive and responsive experience for the viewer.

The sketch changes continuously as the sound environment changes. For example, speaking, typing, or background noise all affect the visual output differently. The rhythm of the visuals follows the rhythm of the sound, making the connection between data and experience more direct and immediate.

Through this process, I learned how to use live input data and map it to visual systems in p5.js. I also explored how randomness and layering can make the visualisation more expressive. This project shows how data does not need to be static or numerical—it can be live, sensory, and closely connected to everyday experience. It also highlights how digital tools can extend analogue ideas, turning simple observations into interactive and evolving visual forms.
