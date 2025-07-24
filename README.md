# Mental-Health-Music-Analysis

This repository contains a Python script for analyzing the relationship between music listening habits and various mental health indicators based on survey data. The script generates different data visualizations to provide insights into age-based listening hours, music genre preferences, streaming service usage, and the perceived effects of music on anxiety, depression, insomnia, and OCD.
___________________________________________________________________________________________________________________________________________________________________

### Features
The script provides the following analysis options, accessible via an interactive command-line menu:

#### Age and Hours Analysis: Visualizes the average hours spent per day listening to music by different age groups (Pie Chart).

#### Favorite Genre Analysis: Shows the distribution of favorite music genres among the surveyed population (Bar Chart).

#### Most Used App (Streaming Service): Displays the most preferred primary streaming services (Bar Chart).

#### Music Preference While Working: Illustrates the preference for listening to music while working (Pie Chart).

#### Anxiety Analysis: Examines the perceived effectiveness of music on anxiety levels (Horizontal Bar Chart).

#### Depression Analysis: Shows the perceived effectiveness of music on depression levels (Pie Chart).

#### Insomnia Analysis: Analyzes the perceived effectiveness of music on insomnia (Pie Chart).

#### OCD Analysis: Investigates the perceived effectiveness of music on OCD (Bar Chart).

#### People's Opinion on Effectiveness of Music: Presents the general opinion on the overall effectiveness of music (Pie Chart).
____________________________________________________________________________________________________________________________________________________________________

#### Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

#### Prerequisites
You need to have Python installed on your system. This project uses pandas for data manipulation and matplotlib for plotting.

Python 3.x
pip (Python package installer - usually comes with Python)

#### Installation
Clone the repository:
git clone [https://github.com/YourUsername/Mental-Health-Music-Analysis.git](https://github.com/YourUsername/Mental-Health-Music-Analysis.git)
cd Mental-Health-Music-Analysis
(Replace YourUsername with your actual GitHub username)

Install required Python packages:
pip install pandas matplotlib

#### Data
This project requires a CSV file named mh.csv to be present in the root directory of the project. This file should contain the survey data with columns such as "Age", "Hours per day", "Fav genre", "Primary streaming service", "While working", "Anxiety", "Depression", "Insomnia", "OCD", and "Music effects".

##### Note: Ensure the mh.csv file is placed in the same directory as IPproject.py after cloning the repository.

#### Usage
To run the analysis script, execute the IPproject.py file from your terminal:
python IPproject.py

The script will present an interactive menu. You can enter one or more numbers (separated by commas) corresponding to the analyses you wish to perform.

Please choose an option:
1. Age and Hours Analysis
2. Favorite Genre Analysis
3. Most Used App (Streaming Service)
4. Music Preference While Working
5. Anxiety Analysis
6. Depression Analysis
7. Insomnia Analysis
8. OCD Analysis
9. People's Opinion on Effectiveness of Music
0. Exit
Enter the numbers corresponding to your choices : 1,2,5

#### Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please feel free to:
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
