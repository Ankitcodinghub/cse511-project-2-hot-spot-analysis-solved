# cse511-project-2-hot-spot-analysis-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse511-solved-14/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;107545&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE511 Project 2-Hot Spot Analysis Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Purpose

In this project, you will perform numerous spatial queries on a huge database that contains geographic information and the real-time locations of the customers of a well-known taxi company.

Objectives

Learners will be able to:

● Set up Apache Spark and use dataframes within it to manage data operations.

● Write some simple Scala code then identify how to run it.

● Interact with geospatial data and run queries on it.

Technology Requirements

● Apache Spark

● SparkSQL

● Scala

● Java

● Hadoop

Project Description

You will be utilizing Scala and Apache Spark in this project to create a solution that can extract crucial data from the provided dataset, which can then be used to make operational and strategic choices. The technology gives the client access to statistically significant geographic locations, which it can utilize to plan its operations in advance and improve customer service.

Directions

In addition to the directions below, please review the “Introduction” video located in the “Week 8: Overview” section.

In this project, you are required to do spatial hot spot analysis. In particular, you need to complete two different hot spot analysis tasks.

Tasks:

1. Hot Zone Analysis

This task will need to perform a range join operation on a rectangle datasets and a point dataset. For each rectangle, the number of points located within the rectangle will be obtained. The hotter rectangle means that it includes more points. So this task is to calculate the hotness of all the rectangles.

Download the required templates (attached in the Coursera project description).

2. Hot Cell Analysis

● Problem Definition page

● Submit Format page

● Special requirement (different from GIS CUP)

As stated in the Problem Definition page, in this task, you are asked to implement a Spark program to calculate the Getis-Ord statistic of NYC Taxi Trip datasets. We call it “hot cell analysis”

To reduce the computation power need, we made the following changes:

1. The input will be “yellow_trip_sample_100000.csv” dataset.

2. Each cell unit size is 0.01 * 0.01 in terms of latitude and longitude degrees.

3. You only need to consider Pick-up Location.

4. We don’t use Jaccard similarity to check your answer. However, you don’t need to worry about how to decide the cell coordinates because the code template generates cell coordinates. You just need to write the rest of the task.

Coding Template Specification:

Input Parameters:

1. Output path (Mandatory)

2. Task name: “hotzoneanalysis” or “hotcellanalysis”

3. Task parameters: (1) Hot zone (2 parameters): nyc taxi data path, zone path(2) Hot cell (1 parameter): nyc taxi data path

1. The number/order of tasks do not matter.

2. But, the first 7 of our final test cases will be hot zone analysis, the last 8 will be hot cell analysis.

Input Data Format:

The main function/entrance is “cse512.Entrance” scala file.

1. Point data: The input point dataset is the pickup point of New York Taxi trip datasets. The data format of this phase is the original format of NYC taxi trip which is similar from Phase 2. But the coding template already parsed it for you. Find the data in the .zip file (attached in the Coursera project description, titled “…Yellow Trip Sample 100000”).

2. Zone data (only for hot zone analysis): at “src/resources/zone-hotzone” of the template

Hot Zone Analysis:

The input point data can be any small subset of the NYC taxi dataset.

Hot Cell Analysis:

The input point data is a sample dataset like “yellow_trip_sample_100000.csv.”

Output Data Format:

Hot Zone Analysis:

All zones with their count, sorted by “rectangle” string in an ascending order.

The coordinates of top 50 hottest cells sorted by their G score in a descending order. ● Note: Do not output G score.

An example input and answer are put in “testcase” folder of the coding template

Where you need to make changes:

Do not delete any existing code in the coding template unless you see this “You need to change this part.”

Hot Zone Analysis:

In the code template:

1. You need to change “HotzoneAnalysis.scala” and “HotzoneUtils.scala”.

2. The coding template has loaded the data and written the first step, range join query, for you. Please finish the rest of the task.

3. The output DataFrame should be sorted by you according to the “rectangle” string.

Hot Cell Analysis:

In the code template,

1. You need to change “HotcellAnalysis.scala” and “HotcellUtils.scala”.

2. The coding template has loaded the data and decided the cell coordinate, x, y, z and their min and max. Please finish the rest of the task.

3. The output DataFrame should be sorted by you according to G-score. The coding template will take the first 50 to output. Do not output G-score.

Submission Directions for Project Deliverables

Submission Files:

Submit a .jar file. Please title your file with “Last Name_First Name_Fall B 2022_Project 2 Hot Spot Analysis.”

1. Go to “Programming Assignment: Project 2: Hot Spot Analysis”.

3. Click on “Create submission.”

4. Upload your project jar package and click “Submit.”

5. You need to make sure your code can compile and package by entering sbt clean assembly.

We will run the compiled package on our cluster directly using “spark-submit” with parameters. If your code cannot compile and package, you will not receive any points.

**Important: Grading will take about 10~20 minutes.**

Tips (Optional):

This section is the same as that in Phase 2.

How to debug your code in IDE:

If you are using the Scala template,

1. Use IntelliJ Idea with Scala plug-in or any other Scala IDE.

2. Replace the logic of User Defined Functions ST_Contains and ST_Within in SpatialQuery.scala.

3. Append .master(“local[*]”) after .config(“spark.some.config.option”, “some-value”) to tell IDE the master IP is localhost.

5. Run your code in IDE.

6. You must revert Step 3 and 4 above and recompile your code before use of spark-submit!

How to submit your code to Spark:

If you are using the Scala template

1. Go to the project root folder.

3. Find the packaged jar in

“./target/scala-2.11/CSE511-Project-Hotspot-Analysis-Template-assembly-0.1.0.jar”

4. Submit the jar to Spark using Spark command “./bin/spark-submit”. A pseudo code example:

./bin/spark-submit

~/GitHub/CSE511-Project-Hotspot-Analysis-Template/target/scala-2.11/CSE511-Project-Hotsp ot-Analysis-Template-assembly-0.1.0.jar test/output hotzoneanalysis src/resources/point-hotzone.csv src/resources/zone-hotzone.csv hotcellanalysis src/resources/yellow_trip_sample_100000.csv

Report Submission:

For this project deliverable, you must write a 2-3 page report detailing your work on this project. Your report should include the following elements:

1. Reflection: How did you approach the project? What did you specifically do?

2. Lessons Learned: What did you learn by doing this project?

3. Implementation: You need to include the following parts in your Project 2 report:

a. What hot zone analysis is doing:

i. def ST_Contains(queryRectangle: String, pointString: String )

b. What hot cell analysis is doing:

i. write the multiple steps required before calculating the z-score.

This is a manually graded task and you will get credit for the report if you covered all the mentioned parts.

Your report should be in doc, docx, or pdf. Please title your report file with “Last Name_First

Name_Fall B 2022_Project 2 Hot Spot Analysis Report.”

When you are ready to submit the report:

Double check that the content of your report is complete, your file is in doc, docx, or pdf and titled with “Last Name_First Name_Fall B 2022_Project 2 Hot Spot Analysis Report.” Then submit your report:

1. Go to “Graded Assignment: Project 2: Hot Spot Analysis Report Submission”.

2. Click “Start Submission”.

3. Click “Upload a File.”

4. Locate and select your report file.

6. Click “Submit.”

Evaluation

Grading Rubric for Report

Component 0 1 2

Reflection There is no reflection included. The reflection attempts to demonstrate thinking about learning but is vague and/or unclear about the personal learning process. The reflection explains the student’s own thinking and learning processes, as well as implications for future learning.

Analysis There is no analysis included. The reflection attempts to analyze the learning experience but the value of the learning to the student or others is vague and/or unclear. The reflection is an in-depth analysis of the learning experience, the value of the derived learning to self or others, and the enhancement of the student’s appreciation for the discipline.

Learner Checklist

Prior to submitting, read through the Learner Checklist to ensure you are ready to submit your best work.

Did you title your file correctly and convert it into a single .jar file?

Did you include your legal first and last name in the designated area on the report?

Did you title your report document correctly and convert it into a single doc, docx, or pdf?

○ Last Name_First Name_Semester Year_Name of Project Name

Did you answer all of the questions to the best of your ability?

Did you make sure your answers directly address the prompt(s) in an organized manner that is easy to follow?

Did you self-assess your open-ended responses using the rubric and make any necessary revisions?

Did you proofread your work?
