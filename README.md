### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 31/10/2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {'RAGA SUSANTH','KARTHIKA','RASOOL','VIJAYA','SNEHITH'}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
'RAGA SUSANTH',101,high,2,male,250311
'KARTHIKA',102,low,3,female,251665
'RASOOL',103,medium,1,male,240238
'VIJAYA',104,low,5,female,200200
'SNEHITH',105,high,2,male,240240


--------------
Weather Data
---------------

@relation weather

@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@attribute CLIMATE {HOT,MILD,COLD}

@data
sunny,85.0,85.0,false,no,HOT
overcast,80.0,90.0,true,no,MILD
sunny,83.0,86.0,false,yes,HOT
rainy,70.0,86.0,false,yes,COLD
rainy,68.0,80.0,false,yes,COLD
rainy,65.0,70.0,true,no,COLD
overcast,64.0,65.0,false,yes,MILD
sunny,72.0,95.0,true,no,HOT
sunny,69.0,70.0,false,yes,HOT
rainy,75.0,80.0,false,yes,COLD

```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

<img width="1919" height="1151" alt="image" src="https://github.com/user-attachments/assets/df7a56c6-8b1a-470d-b6b7-feb84d42e5e7" />
<img width="1231" height="740" alt="image" src="https://github.com/user-attachments/assets/bf403736-3c7f-42da-bd58-a1c583ce046b" />


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1920" height="1150" alt="image" src="https://github.com/user-attachments/assets/ed7a9da9-4a08-4b64-918c-c4a35f5aed43" />


<img width="1232" height="740" alt="image" src="https://github.com/user-attachments/assets/dc70c695-7619-48db-8238-9b0f54ca14ad" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1920" height="1153" alt="image" src="https://github.com/user-attachments/assets/e30eca63-30f0-4391-bcfe-7c8878a7fb66" />

<img width="1235" height="739" alt="image" src="https://github.com/user-attachments/assets/1e15a20d-3927-4713-adb1-5f9d295b8f0e" />



### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

<img width="1920" height="1152" alt="image" src="https://github.com/user-attachments/assets/e8e61e5f-60b2-4e3b-ad72-6774b4feefe9" />

<img width="1234" height="740" alt="image" src="https://github.com/user-attachments/assets/d615b256-d8b8-4827-9374-493fe4d94cc1" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
