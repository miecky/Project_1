Project 1: Standardized Testing, Statistical Summaries and Inference

### Overview
> The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers 
the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT
participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board 
and you will use the provided data and outside research to make recommendations about how the College Board might work to 
increase the participation rate in a **state of your choice**.

#### Provided Data

This project has two provided 2017 test score datasets, the 2018 test score datasets were obtain through SAT and ACT official
website. Through the project, three new combined datasets were generated.

Provided
- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

Obtained
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/ACT_2018.csv)

Generated
- [Combined 2017 Scores](./data/combined_2017.csv)
- [Combined 2018 Scores](./data/combined_2018.csv)
- [Combined All Scores](./data/final.csv)

### Description of Datasets (final.csv)
| Feature              | Type    | Dataset      | Description                 |
|----------------------|---------|--------------|-----------------------------|
| state                | object  | sat_2017.csv | Name of the state           |
| 17_sat_participation | float64 | sat_2017.csv | 2017 SAT Participation Rate |
| 17_sat_ebrw          | int64   | sat_2017.csv | 2017 SAT Verbal Score       |
| 17_sat_math          | int64   | sat_2017.csv | 2017 SAT Math Score         |
| 17_sat_total         | int64   | act_2017.csv | 2017 SAT Total Score        |
| 17_act_participation | float64 | act_2017.csv | 2017 ACT Participation Rate |
| 17_act_english       | float64 | act_2017.csv | 2017 ACT English Score      |
| 17_act_math          | float64 | act_2017.csv | 2017 ACT Math Score         |
| 17_act_reading       | float64 | act_2017.csv | 2017 ACT Reading Score      |
| 17_act_science       | float64 | act_2017.csv | 2017 ACT Science Score      |
| 17_act_composite     | float64 | act_2017.csv | 2017 ACT Composite Score    |
| 18_sat_participation | float64 | sat_2018.csv | 2018 SAT Participation      |
| 18_sat_ebrw          | int64   | sat_2018.csv | 2018 SAT Verbal Score       |
| 18_sat_math          | int64   | sat_2018.csv | 2018 SAT Math Score         |
| 18_sat_total         | int64   | sat_2018.csv | 2018 SAT Total Score        |
| 18_act_participation | float64 | ACT_2018.csv | 2018 ACT Participation Rate |


#### Final Presentation
- [Project 1 Presentation](./project_1.pdf)
