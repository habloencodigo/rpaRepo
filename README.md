## RPA challenge. http://www.rpachallenge.com
1. The goal of this challenge is to create a workflow that will input data from a spreadsheet into the form fields on the screen.
1. Beware! The fields will change position on the screen after every submission throughout 10 rounds thus the workflow must correctly identify where each spreadsheet record must be typed every time.
1. The actual countdown of the challenge will begin once you click the Start button until then you may submit the form as many times as you wish without receiving penalties.

# Solution is divided in two sequances: 
* Setup
* Fill Form
## Setup sequance

* Read data from provided file: challenge.xlsx (Prepare input data source variable - DTInput).
* Open browser and navigate to provided link: http://www.rpachallenge.com
* Initialize challenge by clicking Start Button.
## Fill Form sequance

* Mapp DTInput culmn data to web browser form fields.
* Indicate Anchor tags.
* For each row in Data Table(DTInput) Type its column data Into Fields Mapped fields.

## Cloning this repo.

1. Open UiPath > **Start**
1. Select Clone or Check Out
1. Select Clone repository
1. Paste repo url in Repository URL: https://github.com/habloencodigo/rpaRepo.git
1. Click Open
