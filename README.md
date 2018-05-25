## Change-Datasource-Kata
Change Data source kata for practice Dependency Inversion Principle and other SOLID principles
The goal is change data source of a application with the least possible impact.

### Requirements
At the begin of development of an application we are going to use a local json files as data source and the next iteration we will change json to real database.
### Initial requirements
Create a console application that show information of video list of a data source:

-v  parameter: Show video list
  
Identifier, youtubeId, title, description, subtitle, eventDate, createdDate

-v artist name: show video artist list

-a parameter: Show artist list
            
Identifier, name, birthDate, country
 
Use dependency inversion for avoid coupling with data layer
### Extra requirements if you feel with force :)
Refactor json files to real database solution

