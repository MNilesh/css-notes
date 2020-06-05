## CSS Width and Height new Way
### min(500px, 70%)
use which ever is minimum in this case. between 500px and 70% whichever is minimum will be used.
 ```
    width: min(500px, 70%);
 ```
 
 ### ! max(500px, 70%)
use which ever is maximum in this case. between 500px and 70% whichever is maximum will be used.
 ```
    width: max(500px, 70%);
 ```
 
 ### clamp(min, avg, max);
clamp takes 3 parameters and wont work in 1 or 2 parameters. it can be used to set really dynamic font-sizes.
 ```
    font-size: clamp(2rem, 5vw, 5rem);
 ```
