# CDC and Redlining Data
### BerkeleyExtension_AIAssignment_FinalProject

**Julian Cady**

#### Executive summary
Redlining data is crossed with CDC data in an attempt to determine redlining grades' ability to predict health outcomes.

#### Rationale
I happen to believe that the racist practices of our past have a continuing effect on our present and future. If I can show that redlining is a predictor of current health outcomes, I can add another piece of concrete evidence to body of proof showing that fact. Information like this gives people fighting for their rights more tools to do it with, and shows city planners and lawmakers where to focus their efforts.

#### Research Question
Is an area's status as a historically redlined area a large predictor of health outcomes?

#### Data Sources
The data used are from the CDC PLACES dataset and the University of Richmond's Digital Scholarship Lab's redlining data.
https://data.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb/data_preview
https://dsl.richmond.edu/panorama/redlining/data

#### Methodology
Geodata from both sources are combined and used to train as accurate a model as possible, then coefficients are examined to determine their influence on the final outcome. In addition, a model trained on only grade (its redlining score, essentially) will be trained to see how accurate it can get.

#### Results
I found that a location's grade does not have a high correlation with asthma in adults. The very simple linear regression model trained on only grade has a very bad score, further supporting the idea.

#### Next steps
Frankly, I need more time to understand how to work with the data I have. My next step, personally, may involve asking ChatGPT to explain my own code to me to figure out what I may be misunderstanding.

#### Outline of project
- [Link to notebook](https://github.com/GitHusbando/BerkeleyExtension_AIAssignment_FinalProject/blob/main/final_project.ipynb)


##### Contact and Further Information
email: julian@cadytech.com  
  
In order to use the notebook, you will need the file from here:  
https://data.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb/about_data  
Press "Export" on the top right and place the file into a folder called "data."

