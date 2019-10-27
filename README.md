# Data Visualization Project


## Data

The data I propose to visualize for my project is [USA carrier on-time performance data](https://gist.github.com/Echo226/d58e972330148cb6e55c8d4ab2496215). It was collected from **United States Department of Transportation** and preprocessed with Python.



## Prototypes

I've created two visualization prototypes of this dataset.

- This is a map showing the location of all airports in USA. Each circle represents one airport.

<img width="474" alt="Prototype1" src="https://user-images.githubusercontent.com/44983835/67640227-94360e00-f8cf-11e9-9f3e-b0dc01edc627.png">

- This is a radial chart and it shows the average departure delay time for all flights thorugh 20180701 to 20190630.

<img width="292" alt="Prototype2" src="https://user-images.githubusercontent.com/44983835/67640233-a021d000-f8cf-11e9-9eb0-a6a7daf31fff.png">



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

- What are the top-5 busiest airports in USA? (only consider the domestic flights)
- How are the top-5 busiest airports perform over time?
- How does USA flights' on-time performance vary over time?

## Interactions:

- There will be an interactive color legend showing the top-5 busiest airports in USA. Each color represents one airport and clicking on this color legend will bring the corresponding information of this airport.
- There will be a dropdown box called "time" containing four options: DAY_OF_MONTH, WEEKDAY, MONTH and DATE. Clicking on these different options will show the USA Flight On-time Performance in different time aspects.



## Schedule of Deliverables:
| Item                                                                                   | Estimated deadline |
| :------------------------------------------------------------------------------------- | -----------------: |
| Collect and clean data                                                                 | Done               |
| Draw a radial chart to visualize USA flights' average delay situation over 'DATE'      | 10/12/2019         |
| Filter the top-5 busiest airports and combine them into one radial chart               | 10/17/2019         |
| Add axes(tick marks and labels) for angle                                              | 10/20/2019         |
| Create a corlor legend and make it interactive                                         | 10/23/2019         |
| Organize the final project report                                                      | 10/27/2019         |
| Make a video for this project                                                          | 10/29/2019         |


## Sketches

#### Sketch 1

Using bar chart to show the most busiest airport for each State. Clicking on airport name brings us to top-10  busiest flights for that airport.

![Airport_1_Xinting](https://user-images.githubusercontent.com/44983835/65616911-d34c0900-df89-11e9-8efa-417342351361.jpg)



#### Sketch 2

Data is visualized geographically.

![Airport_2_Xinting](https://user-images.githubusercontent.com/44983835/67640146-7f0caf80-f8ce-11e9-95c5-9ab227d537f5.jpg)



#### Sketch 3

Data is visualized by time to answer question "How does USA carriers' on-time performance vary over time?".

![Airport_3_Xinting](https://user-images.githubusercontent.com/44983835/67640148-8f248f00-f8ce-11e9-91f1-0713f254809b.jpg)



