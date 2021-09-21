# Apanasevich Dzmirty #

Email: dmirty.apan@yandex.by
Tel: +375333788580

# Design engineer at Mechatronics. #
Development of axle load sensors and weighing systems.
I like to learn new things, we teach quickly, I am diligent.

# Programming languages #
C, C#, JavaScript, HTML, CSS, GitHub, React, React-redux, React-router, scss

# Code Example #

```
function superStreetFighterSelection(fighters, position, moves) {
  let fighterHeight = fighters.length;
  let fighterWidth = fighters[0].length;
  
  return moves.map(move => {
    switch(move) {
        case "up":
          position[0]--;
        
          if (position[0] < 0 || fighters[position[0]][position[1]] === "") {
            position[0]++;
          }
        break;
        
        case "down":
          position[0]++;
        
          if (position[0] === fighterHeight ||  fighters[position[0]][position[1]] === "") {
            position[0]--;
          }
        break;
        
        case "left": 
          do {
            position[1]--; 
            
            if (position[1] < 0) {
              position[1] = fighterWidth - 1;
            }           
          } while (fighters[position[0]][position[1]] === "")  
        break;
        
        case "right":
          do {
            position[1]++; 
            
            if (position[1] === fighterWidth) {
              position[1] = 0;
            }           
          } while (fighters[position[0]][position[1]] === "") 
        break;
    }
    
    return fighters[position[0]][position[1]];
  });
}
```
# Work Experience #
Application development using react framework - 1year.

Projects being worked on:
- [Task Manager](http://task-manager-by-b.herokuapp.com/ "Task Manager")

# Education #

- Minsk Higher Rabiotechnical College, 2009-2013
- Belarusian State University of Informatics and Radioelectronics, 2013-2017

# English #

Level A2. Way stage or elementary.