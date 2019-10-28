

# Data Visualization Project


## Data

The data I propose to visualize for my project is [USA carrier on-time performance data](https://gist.github.com/Echo226/d58e972330148cb6e55c8d4ab2496215). It was collected from **United States Department of Transportation** and preprocessed with Python.



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

- What are the top-5 busiest airports in USA? (only consider the domestic flights)
- How are the top-5 busiest airports perform over time?
- How does USA flights' on-time performance vary over time?



## Sketches

#### Sketch 1

Using bar chart to show the most busiest airport for each State. Clicking on airport name brings us to top-10  busiest flights for that airport.

<img width="700" src="https://user-images.githubusercontent.com/44983835/65616911-d34c0900-df89-11e9-8efa-417342351361.jpg">


#### Sketch 2

Data is visualized geographically.

<img width="700" src="https://user-images.githubusercontent.com/44983835/67640146-7f0caf80-f8ce-11e9-95c5-9ab227d537f5.jpg">


#### Sketch 3

Data is visualized by time to answer question "How does USA carriers' on-time performance vary over time?".

<img width="700" src="https://user-images.githubusercontent.com/44983835/67640148-8f248f00-f8ce-11e9-91f1-0713f254809b.jpg">



### Achievements

* Map for locations of USA airports.
  * This is a USA map showing the location of all airports in USA.
  * Each circle represents an airport, and hovering on the circle will show the airport name and state.



[<img width="949"  src="https://user-images.githubusercontent.com/44983835/67640233-a021d000-f8cf-11e9-9eb0-a6a7daf31fff.png">](https://beta.vizhub.com/Echo226/ec4c2611923541869edbd23bc94b9ec4)



* On-time performance of the top-5 busiest airports in USA.
  * This radial chart shows the on-time performance of the top-5 busiest airports in USA. "BUSY" is defined by the total number of domestic flights departure from July 2018 to June 2019.
  * There is an interactive color legend on the top-right corner. Each color reperesents one airport and hovering on a specifit color will bring the corresponding radial chart of this airport.
  * In one radial chart, each angle represents a specific date from 20180701 to 20190630 and the radius shows how long is the average delay at this airport (in minutes).

[<img width="949"  src="https://user-images.githubusercontent.com/44983835/67641319-f430b280-f8d7-11e9-8213-e6de11f0b0b0.png">](https://beta.vizhub.com/Echo226/40f6502388de4c4d8e985fffbff1d23e)





### Future Works
- I will add a radius axes on the radial chart, which enables us to read the precise delay time more clearly.
- I will add a dropdown box called "time" containing four options: DAY_OF_MONTH, WEEKDAY, MONTH and DATE. Clicking on these different options will show the USA Flight On-time Performance in different time aspects.
