# Netflix_Excel_Dashboard

# 📊 **Netflix Dashboard in Excel**


### **Final Dashboard**

<img width="1280" height="636" alt="image" src="https://github.com/user-attachments/assets/2e6ffa53-ee4f-4281-9181-53921e3b2016" />

### **Raw Dataset Structure**

<img width="1360" height="655" alt="image" src="https://github.com/user-attachments/assets/2aed8c30-8b6f-44e5-94bb-c8dde7f6cd61" />


### **Pivot Table Example**
<img width="268" height="243" alt="image" src="https://github.com/user-attachments/assets/79fac2a9-01b2-4492-a81c-2de86ca64915" />



# 📁 **1. PROJECT SETUP**

## **Step 1: Prepare Your Workbook**

1. Open **Excel → Blank Workbook**
2. Rename the sheets:

```
Netflix_Intro  
Movies_vs_TV_Shows  
Content_by_Country  
Content_Growth  
Rating  
Content_Type  
Popular_Directors  
Popular_Actors  
Total_Count  
Countries_Represented  
DASHBOARD
```

## **Step 2: Import the Dataset**

1. Go to **Data → Get Data**
2. Load your dataset into a sheet named **Netflix_Raw_Data**
3. Confirm these column headers:

* Title
* Type (Movie/TV Show)
* Director
* Cast
* Country
* Release Year
* Rating
* Duration
* Genre
* Date Added

## **Step 3: Convert to an Excel Table**

* Select the dataset → press **CTRL + T**
* Name the table: **Netflix**

---

# 📊 **2. ANALYSIS & PIVOT TABLE CREATION**

Each sheet contains a pivot table based on different insights.

---

## **A. Movies vs TV Shows**

**Goal:** Compare number of Movies vs TV Shows
**Sheet:** `Movies_vs_TV_Shows`

### Steps

1. Insert → Pivot Table
2. Rows: **Type**
3. Values: **Count of Title**
4. Insert **Pie or Bar Chart**

<img width="1323" height="395" alt="image" src="https://github.com/user-attachments/assets/2d2de1b3-64f8-4aa0-be3b-782be21e23de" />

---

## **B. Content by Country**

**Goal:** Identify which countries produce the most Netflix content.
**Sheet:** `Content_by_Country`

### Steps

1. Insert Pivot
2. Rows: **Country**
3. Values: **Count of Title**
4. Sort descending
5. Insert **Bar Chart** or **Map Chart**

<img width="1342" height="450" alt="image" src="https://github.com/user-attachments/assets/33c2ba0f-54d9-4c2b-9f2d-0d2288ab7935" />


## **C. Content Growth Over Time**

**Goal:** Show Netflix content added per year.
**Sheet:** `Content_Growth`

### Steps

1. Insert Pivot
2. Rows: **Release Year**
3. Values: **Count of Title**
4. Insert **Line Chart**

<img width="1338" height="450" alt="image" src="https://github.com/user-attachments/assets/f400a106-9827-4c9f-b25b-4c55e64d47dc" />


## **D. Ratings Distribution**

**Goal:** Understand content suitability (PG, TV-MA, etc.)
**Sheet:** `Rating`

### Steps

1. Insert Pivot
2. Rows: **Rating**
3. Values: **Count of Title**
4. Insert **Bar Chart**

<img width="1344" height="440" alt="image" src="https://github.com/user-attachments/assets/70d5b900-53af-4a16-92ce-f4a92f11d17f" />


## **E. Content Type (Genre)**

**Goal:** Visualize genre distribution
**Sheet:** `Content_Type`

### Steps

1. Insert Pivot
2. Rows: **Genre**
3. Values: **Count of Title**
4. Insert **Column/Bar Chart**

<img width="1342" height="448" alt="image" src="https://github.com/user-attachments/assets/019fa204-98dd-4beb-822a-efaa7ceca33f" />

## **F. Popular Directors**

**Goal:** Identify top Netflix directors
**Sheet:** `Popular_Directors`

### Steps

1. Use **Text to Columns** if multiple directors appear
2. Insert Pivot
3. Rows: **Director**
4. Values: **Count of Title**
5. Filter blanks
6. Insert **Bar Chart**

<img width="1344" height="444" alt="image" src="https://github.com/user-attachments/assets/8e89f48b-8c07-4cbf-98fc-7018ab3b3ed6" />


## **G. Popular Actors**

**Goal:** Find actors who appear most often on Netflix
**Sheet:** `Popular_Actors`

### Steps

1. Split cast list if needed
2. Insert Pivot
3. Rows: **Cast**
4. Values: **Count of Title**
5. Insert **Bar Chart**

<img width="1344" height="455" alt="image" src="https://github.com/user-attachments/assets/871d88fb-22e6-4c09-b79b-9aacd6d1cc8c" />

## **H. Total Count**

**Goal:** Show total number of Netflix titles
**Sheet:** `Total_Count`

### Steps

1. Insert Pivot
2. Values: **Count of Title**
3. Create a **KPI card** using shapes

<img width="200" height="138" alt="image" src="https://github.com/user-attachments/assets/a9cfcd1c-13fa-4ce7-a75a-7dfdd2a9a096" />

## **I. Countries Represented**

**Goal:** Count unique countries available on Netflix
**Sheet:** `Countries_Represented`

### Steps

1. Insert Pivot
2. Rows: **Country**
3. Turn **Subtotals OFF**
4. Use PivotTable Analyze → Count

<img width="196" height="162" alt="image" src="https://github.com/user-attachments/assets/c0c41c7c-a2ff-4488-9e72-1c972a1d54f9" />

# 📌 **3. BUILDING THE FINAL DASHBOARD**

All visuals are assembled in the `DASHBOARD` sheet.


## **Step 1: Layout Setup**

* Insert rectangles for background
* Set Netflix-themed colors: **Red • Black • White**
* Add header:

```
NETFLIX CONTENT ANALYTICS DASHBOARD
```


## **Step 2: Add All Charts**

Copy charts from the analysis sheets and place them neatly:

* Movies vs TV Shows
* Content Growth
* Country Distribution
* Ratings
* Popular Directors
* Popular Actors
* Genre Distribution

<img width="1280" height="435" alt="image" src="https://github.com/user-attachments/assets/bd591b11-45ab-4fdd-85e3-d3871d07ba09" />

## **Step 3: Create KPI Cards**

Example metrics:

* Total Titles
* Number of Movies
* Number of TV Shows
* Countries Represented

### How to Build One:

1. Insert → Shape → Rectangle
2. Add a text box
3. Apply Netflix colors
4. Bold the number


## **Step 4: Final Dashboard Polish**

* Remove gridlines
* Align chart edges
* Maintain consistent sizing
* Add icons if desired
* Ensure clean spacing


# 🎉 **DONE!**

You have successfully built the complete **Netflix Excel Dashboard** from scratch.
