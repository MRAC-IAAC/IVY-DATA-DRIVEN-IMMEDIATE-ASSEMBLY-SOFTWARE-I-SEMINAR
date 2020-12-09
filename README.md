## IVY DATA-DRIVEN IMMEDIATE ASSEMBLY – SOFTWARE I SEMINAR

### Project Description: 
Data Driven immediate Assembly is a project developed during the Software I Seminar of the **MRAC-20/21-program**. The task was based on developing a pavilion or similar structure based on a sensible data. The structure should be generated from small components using grasshopper aggregation method and Anemone was used for this design approach.

### Design Approach & data collection:-
This project focusses on design generation using sensible data, NDVI (Normal difference vegetation index) data of Barcelona was decided to be collected.
![Workflow Target](doc/diagrams/Workflowtarget.jpg)

### Workflow- 
The design consists of small components aggregating (using anemone) to create a final output.The components have male and female connectors to lock with each other. 

![Basic components](doc/diagrams/Basiccomponents.jpg)

The components were modified for better aggregation (connection), better asthetic, and to use the NDVI data collected (refer the blog for better reference)

![Final upgraded components](doc/diagrams/Upgradedcomponents.jpg)

The upgraded components were tried with several logic of connection (with different number of receiving planes to create uniform aggregation in all direction).Below is the final output received.

![Final upgraded components](doc/diagrams/Finaloutput.jpg)

Please note that, the implementation of NDVI data is done partial through this project till date and still has a lot of space for developments. 


[Project Blog](http://www.iaacblog.com/?post_type=program&p=106351&preview=true)

## Requirements:
1. Rhino 5 or later.
2. Grasshopper
3. Anemone plugin
4. NDVI data from internet

# Getting Started: 
After downloading all the required. you can open the rhino (3dm) file and grasshoopper (.gh) file. After opening the files you can find the trigger tab for initating the anemone loop. Once the loop is triggered the aggregation will start. you can make changes as per your requirements 

 
    
# References: 
[Refeference link](https://opendata-ajuntament.barcelona.cat/en)

[Refeference link](https://www.qgis.org/en/site/)

[Refeference link](http://www.jeannouvel.com/en/)

IVY DATA-DRIVEN IMMEDIATE ASSEMBLY is a project of IaaC, Institute for Advanced Architecture of Catalonia. developed at **Master in Robotics and Advanced Construction** in 2020-2021/22 by:
Students: **Arpan Mathe, Charng Shin Chen**
Faculty: **Ján Pernecký, Eugenio Bettucchi**

# Source folder content:
1.	Grasshopper definition
2.	3d model Rhino file

# Document folder: 
1.	Final renders
2.	Component renders
3.	Within Components connection details (render)
4.  Component-component connection detail (render)


          




