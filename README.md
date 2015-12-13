# google-circle
This implementation is build on the top of the google circle animation example avaliable at: https://github.com/Abe/Google-Circles-Animation

Short description:
Allows friends circle to be added and removed to and from circle via drag drop.

What is added?
 * Allow multiple circles
 * Detecting if circles are present inside or not and on the basis of that doing zooming and zoom out
 * Allow use of images for friend circles
 * Disallowing to drop inside the circle with text, is drop is inside the circle with text then move it to default location
 * Provide configurable easy method of google circle implementation:
 * Text label to circle

* Method: 

function drawGoogleCircle(configObj)

example config object:

```
    
	var config = {drawHeight:600,drawWidth:600,
	
	circleX : 150,
		
	circleY : 150,
		
        circleRadius : 80,
		 
        innerCircleRadius : 60,
		
         text : "my circle",
	
         firendsPositionX : 30,
	
	 firendsPositionY : 300,
		
         friendRadius:20,
		
         friends:[{
 
                      fill: 'blue',
  
                       stroke: 'none',
            
                      opacity: .8,
			
                      src:'img/friend1.png' 
                   }
                    ]};
```
