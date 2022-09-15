# NorwAI 2022 hackathon
Welcome to this years NorwAI hackathon!

This year we will be looking at a dataset by Hafslund ECO (HEV) about water inflow into the storage lake of a hydro power plant.
The name of the power plant is *Hemsil 2* and it is located near *Hemsedal* in the inland of Norway. 

## Task
### Option 1
Your task is to analyze the dataset and provide the power plant operators with useful predictions to control it and plan ahead, or alternatively identify other insights that may prove helpful.
### Option 2
Your task is to identify innovations and business cases for power plant operators or organizations/businesses that would benefit and help with the sustainable operation of power plants if they would have access to such data as in the provided dataset.

Since *Hemsil 2* is a hydro power plant, it is very important to know how much water is currently saved in the storage lake and how much water inflow is to be expected. 

Other interesting insights could be how the weather develops in the area, how much snowfall will happen, or how these influences affect the inflow. Such insights are not necessarily limited to those that are of interest to the hydro power industry.

## Getting started
#### Setting up your working repository
- Please fork this repository to create a working space for your group. There should be **exactly one** fork per group.
- It is **not allowed** to check out the contributions of other groups before the end of the work phase when everyone has handed in their solution.

#### Using the dataset
The dataset is located in a seperate repository that can be found here: https://github.com/sfi-norwai/2022_hackathon_hemsil2_dataset. The `README.md` file of this repository contains further information about the dataset and what the different data columns represent. It also clearly states that the dataset should only be used and distributed within the scope of this hackathon. Please read it carefully.

You can clone it to your local machine by running 
`git clone https://github.com/sfi-norwai/2022_hackathon_hemsil2_dataset.git`

Please don't commit the dataset into your working repository. We are not allowed to distribute the dataset in any way outside of the *NorwAI 2022 hackathon*. To make it possible for you to freely share your contribution to the hackathon afterwards (e.g. through opening your GutHub repo for reference), we need to ensure that the dataset itself is not contained in the contribution. 

It is best to keep the dataset in a completely seperate folder on your local machine. You can also keep it in the root of your local copy of the working repository, as long as you don't rename it. In this case, the `.gitignore` file protects you from commiting it by mistake. 

After you have forked your working repository, navigate to the folder where you store it on your local machin **into** the folder. 
Getting the dataset

### Suggestions for contributions
- You could straight up try to predict the inflow as accurately as possible
- Don't feel restricted by only what the dataset contains. You can probably get auxiliary data from external APIs, such as weather providers (https://frost.met.no/index.html or others) that can give weather, snowfall, humidity, sun intensity, ...
- Perhaps you can do some simplified physical modeling to get additional data columns that help with the prediction, such as modeling the water evaporation
- You could consider modeling different time horizons, such as 1 day, 2 days, or even a week or longer
- You are also encouraged to find insights about the dataset itself. Perhaps you find that not all features are equally important?


## Criteria for success
- Developer track
    - Modeling accuracy (in case you go  this way)
    - Presentation of results:
        - Being able to explain model and procedure
        - Data visualizations
    - Scientific findings such as finding new ways to do predictions on the data, insights about the data itself
- Innovation track
    - Novelty of idea
    - Presentation of idea:
        - Being able to argue for the relevancy and possible impact of your idea
        - Present use-cases and potential stakeholders

### Additional developer criteria
- Computational efficiency of the solution
- Software quality
    - Documentation
    - Readability of Code
    - Structuring
- Reproducibility and testability of the solution

## Discouraged behaviors that might lead to disqualification
- Your contribution should be **unique** and **original**. You should not just copy a solution from the internet. However, it is of course allowed to get inspiration from how others have solved similar problems.
- Getting outside help. The solution **must** come solely from members of the team
- It is **not allowed** to distribute or share the dataset in any way outside of the NorwAI 2022 hackathon. 


