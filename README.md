# 2020_Summer_Individual_study [Working on ReadMe]

## Notion link
[Individual SubNote](https://www.notion.so/SubNote-c44b5edc2bce4f158651a44a88177dc6)

    - Reference 1 summary
    - Reference 3 summary (lite)
    - Programming Timeline

- - -

## Classifying method
  There are two methods to handle data in order to input to classifier. Before handling, the data is organized like the picture below. They'll be converted to 2-dimensional matrix.
![Before](/pictures/illust-data_structure.png)

### Method 1
This method follows the reference 1.
> There will be various number of segments in each try, since active time will be different for every try. 

Calculate RMS values in each try for each channel. 
> Ex) We have "2 segments" consist of "m, n active windows", and "N=3".    
> Each window is consists of 168-dimensional vector. Therefore, if we process the segments in order to input into the classifier, X will be made like below.   
   
### Method 2
Flatten all the ACTIVE windows. Then active window becomes row of input data of classifier while columns are channels.

