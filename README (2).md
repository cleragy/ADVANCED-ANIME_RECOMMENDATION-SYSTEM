# Unsupervised_learning-OA3







## Table of Contents

- [General Information](#general-information)
- [Dataset](#dataset)
- [Packages](#packages)
- [Environment](#environment)
- [Team Members](#team-members)

# General Information
Overview
This project aims to develop an advanced anime recommendation system using unsupervised learning techniques. With the increasing number of anime titles, it can be challenging for viewers to find shows that match their preferences. This system leverages machine learning to automate the recommendation process, enhancing content discoverability and improving user experience.

# Dataset Overview 
This project uses a dataset from the Kaggle Anime Recommender System competition, containing detailed information on anime content and user ratings. The key files are:

**anime.csv:** Details on each anime, including:

**anime_id:** Unique identifier.
**name:** Anime title.
**genre**: List of genres.
**type:** Format (e.g., movie, TV).
**episodes:** Number of episodes.
**rating:** Average user rating.
**members:** Number of community members.

**train.csv:** User rating data, including:

**user_id:** Randomly generated user ID.
**anime_id:** Anime rated by the user.
**rating:** Rating out of 10 (-1 if not rated).
**test.csv:** Contains user_id and anime_id for rating prediction.


# Packages
To carry out all the objectives for this repo, the following necessary dependencies were loaded:

python 3.8+, pandas 1.3.0, numpy 1.21.0, scikit-learn 0.24.2,suprise 1.1.1, streamlit 0.86.0, MLflow 1.19.0, matplotlib 3.4.2

# Environment
It's best practice to utilize a virtual environment for your projects to maintain package dependencies and isolate project environments. Below, we've detailed one approach to set up a virtual environment. Be sure to update this section regularly to reflect any changes or enhancements. By following these instructions, anyone cloning your repository will have clear steps to prepare the required environment swiftly, ensuring a seamless start to their work.
Create the new evironment - you only need to do this once

# Create the conda environment:
conda create <our_env>
This is how you activate the virtual environment in a terminal and install the project dependencies
activate the virtual environment
conda activate <our_env>
install the pip package
conda install pip
install the requirements for this project
pip install -r requirements.txt

# Team Members

| Name               | Email                       |
| -------------      | ---------------             |
| Asanda Gambu    | sinegugugambu@gmail.com  |
| Cleragy Kanuni | kanunimkonza@gmail.com     |
| Coceka Keto  | cocekaketo28@gmail.com |
| Keamogetswe Mothoa |keamogetswemitchellmothoa@gmail.com
| Phumzile Sibiya  | sibiyaphumzile9@gmail.com      |
| Zamancwabe Makhathini  | zamancwabemakhathini@gmail.com |
