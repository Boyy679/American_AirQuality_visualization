# American_AirQuality_visualization
This is a project shows american air quality status and trends through 2020. Including the American declining national air pollutant emissions, American national emissions by source category, Comparison for Growth Areas and Declining Emissions, Impact from the COVID-19 Restrictions

Through the use of **highchart**, **shiny** and other packages to draw:

* interactive scatter plots
  * line charts
  * histograms
  * maps 

to do U.S. national air quality visualize analysis

> Dataset: 

Our dataset is from GitHub of **USEPA / Air-Trends-Report/ etrends_2021**

​	https://github.com/USEPA/Air-Trends-Report

> Task 1

* Plot 1.1: American declining national air pollutant emissions

  * **Task:** to find the output trend of CO, NH3, NOx, Direct PM2.5, Direct PM10, S02, VOC through 1990 to 2020.

  * **Data:** 3 Quantitative attributes; 1 categorical attribute

  * **Mask:** Points, Line connects marks between them

  * **Channels:** Aligned lengths to express quantitative value; 

    ​					Separated and ordered by key attribute into horizontal regions

  * **Trend:** Emissions of key air pollutants continue to decline from 1990 levels:

    •CO: **decrease 70%**

    •NH3: **decrease 8%**

    •NOx: **decrease 68%**

    •PM2.5: **decrease 38%**

    •PM10: **decrease 31%**

    •SO2: **decrease 92%**

    •VOC: **decrease 48%**

![](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143002694.png)

* Plot 1.2: American national emissions by source category

  * **Task:** Find the category of national emissions and is percentage.

  * **Data:** 2 Categorical attributes,1 quantitative attribute

  * **Channels:** Length and color; Spatial regions: one per glyph

  * **Mark**: Line marks normalized to full vertical height;

    ​			Single stacked bar equivalent to full pie

  * Introduction:

    **highway vehicles**, like car,…

    **industrial and other processes**, like: metal smelters, petroleum refineries, cement kilns and dry cleaners…

    **non-road mobile sources**, like: marine vessels, aircraft and locomotives…

    **fuel combustion sources**, like: electric utilities, industrial boilers…

![image-20230401143105136](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143105136.png)

> Task 2
>
> > Comparison for growth areas and declining emissions

* Plot 2.1: Multi-line chart for Comparison declining national air pollutant emissions
  * Variable introduction
    * Year: The time when the value is record
    * GDP: Change rate of Gross Domestic Product (comparing to 1970)
    * Aggregate Emissions (Change rate of the aggregate emissions, which contain PM2.5, PM10, SO2, NOx, VOCs,CO and Pb)
    * Energy Consumption: Change rate of the energy consumption
    * CO2Emssions: CO2Emssions, Change rate of CO2 emissions
    * Vehicle Traveled: Change rate of the Vehicles Miles Traveled
    * Population: Change rate of population comparing to 1970

![image-20230401143441777](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143441777.png)

* Plot 2.2: Graph composition of the correlation plot between each area
  * **Data**: 2 categorical, 1 quantitative
  * **Task**: Relationship analysis
  * **Mark**: Area
  * **Channel**: Color hue

![image-20230401143529779](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143529779.png)

* Plot 2.3: Graph composition for Economic development helps reduce Emissions
  * **Data**: 3 quantitative 
  * **Task**: Relationship analysis
  * **Mark**: Point
  * **Channels**: Horizontal, Vertical Positions, Area, Color hue

![image-20230401143535659](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143535659.png)

> Task 3
>
> > American air quality impact from the COVID-19 Restrictions

* **Data**: **4** quantitative, **1** categorical 
* **Task**: Comparison
* **Mark**: Points
* **Channels:** Icon, Color Hue, Geographic Positions

![image-20230401143732969](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143732969.png)

* **Data**: 8 quantitative
* **Task**: Comparison
* **Mark**:  Lines, Areas
* **Channels:** Area range, Color

![image-20230401143747399](C:\Users\think\AppData\Roaming\Typora\typora-user-images\image-20230401143747399.png)

