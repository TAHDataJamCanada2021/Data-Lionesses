# DataJam Canada 2021 - _**TRACKS: A Trafficking Reporting and Compilation frameworK System:**_

<span style="color:blue">_This is a repository for research projects in the human trafficking domain. It includes all future related project ideas or research topics that would be useful for our project._

_Each topic would have a separate repository. This would include the following:_</span>

## 1. Problem Statement

_A description of an issue to be addressed._
Transport of victims is a major component of human trafficking. There is a lack of user-friendly reporting systems in place for those working in the transportation industry who are likely to see trafficking activity (and lack of methods to identify common trafficking routes?).

## 2. Objective

_Objective of the solutions (the challenge, problem or need that it contributes to solve)._
A reporting system for drivers of transportation companies (ride-sharing apps?). Drivers are sent notifications to report suspicious activity when they are identified to drop off or pick up riders in high risk regions and along high risk routes with particular attention to indigenous communities. The system will be pitched to the police …

## 3. Solution/Data use case description

_A comprehensive description of the data-based solution or/and data use case._
Components of TRACKS

TRACKS makes use of factors which indicate vulnerability to trafficking to identify high risk regions. We train a model with existing trafficking data as ground truth. 
{describe model}

A trip with a rating above a certain threshold is flagged. This sends a notification to a driver or clerks of vehicle rental companies to report trafficking suspicions when they are travelling to and from high risk areas. Notification directs them to a reporting form. This framework collects reports and corresponding locations of drivers to analyze over time to identify high risk or trafficking routes and also to refine the data which leads to more accurate reporting.

The framework is versatile, can be applied to different provinces or interprovincial anti-trafficking initiatives.

The framework can be it’s own app or integrated into existing apps. For example Uber which has an emergency alert system for passengers but not drivers. If it is a separate app, location data can be collected and we do not need to ask a private company for access to private data.

## 4. Pitch

_A pitch of maximum 4 minutes._

Hint: Recommended is to add here just link(s), for example to Youtube recording:

Example location: [link to video](https://www.youtube.com/watch?v=xUcB90b2HMs)

GitHub Limitations:
 - 100MB per file
 - 10GB per repository

## 5. Datasets

Location: [/datasets](datasets)

_A list of data sets, sources and challenges for the research project._
This would include:

- API access to required TAH data
- Access to other datasets (either through API or downloaded)
- Statements on data quality issues, transformations needed
- Container for new data generated for this research (i.e. through merging other data sets)

## 6. Project Code

Location: [/project](project)

This would include the following:

- Data transformations, merging & quality assurance
- Model related code (projection, prediction, correlation etc.)
- User Interface code

## 7. Additional docs (Optional)

Location: [/docs](docs)

- PowerPoint presentation
- Flayers
- Additional videos/demo
- Protocols
- Guides
