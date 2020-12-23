# Grid-Layouts

Very funny and enjoyable repo I have to say... [GRID](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) is the new guy in CSS to build your responsive websites up, it gives you totally freedom to leave old style CSS behind (floats and so on...). Based on 2 dimensional system, handling columns and rows from parent containers till children elements.

NOTE!! All CSS StyleSheet has been embedded to each HTML file to improve understanding on each layout.

## What I did in each Layout:
### **1.Basic Structure**

Property: [grid-template-rows](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows)

Grid-template-row manages to fit sections by using auto and 1fr (Fractional Unit) adapting the page to the whole screen.

### Desktop/Mobile Views
![Screenshot 2020-12-23 at 11 32 30](https://user-images.githubusercontent.com/43299285/102987421-8ea77880-4512-11eb-97c1-862f6e2f19f2.png)

### **2.Classic Structure**
Properties: [Grid-template](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template) and 
[grid-column](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column)

Grid template is very useful to place elements in a screen mixing columns, rows and areas. Using grid-column to decide situation and size of the element.

![Screenshot 2020-12-23 at 12 14 29](https://user-images.githubusercontent.com/43299285/102990873-6a4e9a80-4518-11eb-850e-963f90faa9cf.png)

### **3.Repeat-auto**
Properties: [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns) and 
[grid-gap](https://developer.mozilla.org/en-US/docs/Web/CSS/gap)

Functions: [repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat()) and [minmax](https://developer.mozilla.org/en-US/docs/Web/CSS/minmax())

Grid-template-columns is very powerfull when we use repeat and min max functions controlling sizes of the elements and making them all responsive no matter size of the screen.

#### **Big Device View**
<p align="center"> 
<img src="https://user-images.githubusercontent.com/43299285/102992079-d7fbc600-451a-11eb-9d26-494928f8ab05.png">
</p>

|**Medium Device View**  | **Small Device View** |
| ------------- | ------------- |
| ![Screenshot 2020-12-23 at 12 47 32](https://user-images.githubusercontent.com/43299285/102993206-07abcd80-451d-11eb-88ce-c9333c18387e.png)  | ![Screenshot 2020-12-23 at 12 51 11](https://user-images.githubusercontent.com/43299285/102993491-8bfe5080-451d-11eb-87f5-b8cb6f8fdce6.png) |

### **4.Area-Structure**
Properties: [grid-template-rows](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows), [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns), [grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) and [grid-area](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-area).

Specifying grid areas you may set all your website up as you wish, assigning cells to any element based on structure, size and location.

![Screenshot 2020-12-23 at 13 05 39](https://user-images.githubusercontent.com/43299285/102994552-91f53100-451f-11eb-83b8-4dcfbe7df3df.png)

### **5.Cards-Lined Up**

Property: [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns).

Function: [repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat())

Again grid-template-columns and repeat function a great combination to create responsive elements, as you can see below adaptable to all devices with a simple line CSS code.

#### **Big Device View**
<p align="center"> 
<img src="https://user-images.githubusercontent.com/43299285/102994888-44c58f00-4520-11eb-907f-425c1b69dcbc.png">
</p>

|**Medium Device View**  | **Small Device View** |
| ------------- | ------------- |
| ![Screenshot 2020-12-23 at 13 13 54](https://user-images.githubusercontent.com/43299285/102995151-b69dd880-4520-11eb-8b53-6bb35852c771.png) | ![Screenshot 2020-12-23 at 13 11 53](https://user-images.githubusercontent.com/43299285/102994996-6e7eb600-4520-11eb-91ef-cf60e2e98377.png) |

### **6.Sidebar**

Property: [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns).

Function: [minmax](https://developer.mozilla.org/en-US/docs/Web/CSS/minmax())

Handling sidebars in a website is pretty easy with GRID, just use grid-template-columns and minmax function to fit the element and decide how size will be based on your needs.

<p align="center"> 
<img src="https://user-images.githubusercontent.com/43299285/102995567-9fabb600-4521-11eb-85f5-bd9cd70a733c.png">
</p>

### **7.Span-Grid**
Property: [grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns).

Function: [repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat())

This is just ademostration that everything is possible with GRID, even create the most senseless layouts like this one. Very funny, isn't?...
<p align="center"> 
<img src="https://user-images.githubusercontent.com/43299285/102997108-97a14580-4524-11eb-922d-071fff0586ab.png">
</p>

### **8. Super-Centered**
Property: [place-items](https://developer.mozilla.org/en-US/docs/Web/CSS/place-items)

When you apply place-items to an element it will be centered in your page so no additional properties are needed, you will save time trying to set up your element in both Axis (X and Y). It will do it for you!.

<p align="center"> 
<img src="https://user-images.githubusercontent.com/43299285/102996942-46915180-4524-11eb-87cc-d00a601456b2.png">
</p>

## Getting Started
These instructions will get you a copy of the project up on your local machine to practice with GRID exercises.

## Installing
* Clone the project to your local directory.
* $git clone https://github.com/JoseMMorales/Grid-Layouts.git
* $cd Grid-Layouts
* Right click on index.html file and select "Copy path".
* Open window browser and paste URL.

## Technology:
* HTML5
* Grid CSS

## Author
Jose MMorales