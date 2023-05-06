# CDCBirthData

As a graduate research assistant at the Distributed Artificial Intelligence
Research (DAIR) lab at Hunter College, I worked on a project focused on
predicting and preventing preterm birth. We primarily focused on making use of
the [Nulliparous Pregnancy Outcomes Study: Monitoring Mothers-to-Be (nuMoM2b)](
https://www.nichd.nih.gov/research/supported/nuMoM2b)
data but I also spent some time exploring [birth data](
https://www.cdc.gov/nchs/data_access/Vitalstatsonline.htm)
made publicly available by
the National Center for Health Statistics (NCHS), a part of the Centers for
Disease Control and Prevention (CDC). My work at that time did not progress
beyond some EDA and refinement down to a couple of dataset versions, but this
research remains close to my heart and I would like to continue this work, with
particular emphasis on contending with *large* amounts of data (millions of
births). Thus whereas I previously worked with Python, using the Pandas package,
here I will make use of R and a PostgreSQL database to review and refine the
data, first repeating the work I did on the 2013 data, and later expanding to
additional years. This will enable some machine learning applications:
supervised learning focused on birth outcomes, as well as some unsupervised
learning to understand relationships in the data.

### To-do:
Review:
- [ ] Add data background
- [x] Retrieve the 2013 data
- [x] Create a database for this project
- [x] Load the data (.csv file) into the database
- [ ] Drop unnecessary columns or highly incomplete rows
- [ ] Set aside a test set of data (stratified sampling) for supervised work
- [ ] Visualizations
- [ ] Make the 2013 data process repeatable for additional years

Supervised learning:

Unsupervised learning:


