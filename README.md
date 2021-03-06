# covid-argos
This shell script allows you to see frequently-updated stats for the COVID-19 pandemic in the United States.

# Requirements
- argos 'https://github.com/p-e-w/argos'
- node
- npm
- corona-cli `https://github.com/ahmadawais/corona-cli`

# Configuration
The following variables are intended to be set by the user. ARGOS_DIR is the directory you would like to keep the small cache files this script will create. STATES is an array of strings for each state you want detailed COVID-19 stats of. TOP_N allows you to change between listing the top 'n' states or the specific states in STATES. N_STATES determines how many states are listed by TOP_N. TOP_N can also be modified by the menu in the application.
```
ARGOS_DIR=~/.config/argos/covid-argos                                             
STATES=("North Carolina" "New York" "California")                             
TOP_N=false                                                                   
N_STATES=15  
```    
# In action

Closed with stats for USA:

![An image showing the menu collapsed and the current stats for the United States.](screens/covid-19_menubar.png)

Open, with the top 15 states by number of cases:

![An image showing the menu open and the top 15 states by number of cases.](screens/covid-19_top15_states.png)

Open, with only custom states:

![An image showing the menu open and the top 15 states by number of cases.](screens/covid-19_custom_states.png)
