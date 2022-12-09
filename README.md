# Chess Tournament Manager - Swiss Pairing System

Programmation orientée objet
Implémentation d'un système MVC
Méthode d'appariement des joueurs selon la méthode suisse
Conforme aux recommandations de la PEP8

OVERVIEW
Beta version of a chess tournament manager (Swiss system). 

REQUISITORIES 
Python3

INSTALLATION

Start by closing the repository :
git clone 
Start access the project folder

for Window
Create a virtual environment
python -m venv env
Enable the virtual environment
cd env/scripts
source activate
for Linux or macOS
Create a virtual environment
python3 -m venv env
Activate the virtual environment with
source env/bin/activate 
. . .
Install the python dependencies to the virtual environment
pip install -r requirements.txt
PEP8 Audit report

Use Spyder 4 Code analysis or see Code_analysis _report.pdf

LAUNCH
Run
python main.py
	1. Launch main will generate automatically 8 players for a tournament
	2. Launch 6 at option menu will generate pairs according to Swiss Sytem 
	3. When the round is finished, enter the results. 
  4. Repeat steps 3 for subsequent rounds until the message 'the winner is…' appears.
