# <h1 style='background:#4686C8; border:0; color:#5CE1E6'><center>SUDOKU PUZZLE </center></h1> 

For this project, I am going to solve a sudoku puzzle from an image of an unsolved puzzle. 

The project is divided into three parts

**Part One: Digit Classification Model**

Build and train a neural network on the Chars74K image dataset for digits. This will be further used in classifying the digits in the image.

**Part Two: Detecting And Reading The Sudoku From An Image**

Identify the sudoku puzzle in an image using OpenCV-library.
Classify the digits in the detected sudoku puzzle using the model made in part one. 
Getting the values of the cells in the sudoku in for of array.

**Part Three: Solving The Puzzle**

The array is converted into matrix.
The given puzzle is are solved using recursion. 


   <a id='top'></a>
<div class="list-group" id="list-tab" role="tablist">
<h1 style='background:#4686C8; border:0; color:#5CE1E6'><center>TABLE OF CONTENTS</center></h1>

1. IMPORTING LIBRARIES
    
2. PART ONE: DIGIT CLASSIFICATION MODEL 

3. LOADING DATA      

4. SPLITTING DATASET

5. MODEL BUILDING

6. PART TWO: READING THE SUDOKU PUZZLE
    
7. DETECTING CONTOUR

8. SPLITTING THE CELLS AND CLASSIFYING DIGIT   

9. PART THREE: SOLVING THE SUDOKU

10. END

<h1 style='background:#4686C8; border:0; color:#5CE1E6'><center>Note Please download the data from requirements.txt and update it in DIGITS and Sudoku Box Detection Folders Respectively</center></h1>
    
