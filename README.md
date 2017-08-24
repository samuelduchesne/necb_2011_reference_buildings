# NECB 2011 Reference Buildings 

This repository contains the weather files and OpenStudio models of 16 building archetypes in 69 Canadian cities.

Similar repository with NECB 2011 baseline models can be found [here](https://github.com/canmet-energy/necb-2011-baselines)

## Requirements
* Admin rights
* Install [Git for Windows](https://git-scm.com/downloads)

## Clone this project
1.  Open Windows explorer and navigate to the folder where you want the repository to be downloaded.
2.  Right click inside the windows explorer and choose "Git Bash Here" from the context menu.
3.  Paste the following command on the Git Bash terminal and press enter
```
git clone https://github.com/canmet-energy/necb_2011_reference_buildings.git
```
4.  This will download the repository in a folder named "necb_2011_reference_buildings"

## Folder Structure

**`3d_files`**: Contains the 3d model as an html file.

**`OS_results`**: Contains an overview of annual/monthly energy uses data, load summary, HVAC profiles, etc.

**`osm_files`**: Contains the OpenStudio model of an archetype

**`qaqc_files`**: Contains general information about space, thermal zones, HVAC equipment list, plant loops and Quality Assurance Quality Control (QAQC) data.

**`weather_files`**: Contains weather files which was used to run the simulation.

