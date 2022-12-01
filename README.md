# Download and Installation
1. Download files from the repository
2. Run the whatIf_Setup_5.0.11.exe installation package

# Opening model diagram and the Documenter Interface
1. Double click the ESS.dmm file to open the model diagram in Documenter

When open you will be using the model hierarchy and the model diagram to navigate through the model structure as outlined in the video below. Viewing the diagram in Documenter allows a user to explore and understand the model structure. It does not support running simulations and will not store or output data.

![Alt text](https://github.com/whatIfTechnologies/ESS_public/blob/c3012f0b5208859692ce40318ca4162ca309136f/Documentation/documenter.jpg)

# Understanding Model Diagrams
## Hierarchy and Diagram Objects
[![](https://github.com/whatIfTechnologies/ESS_public/blob/cb5d6f428715aa092106a0f790ad5f30433e6259/Documentation/Diagram%20video.jpg)](https://www.youtube.com/watch?v=qFF_o69p0x8)

### Elements of a calculator diagram include:
* **Stock Variables** - These are variables containing counts of some item, such as population or number of vehicles

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/b791397d4964658732260ac4a4fa18c99e8b4090/Documentation/stock.jpg" width="100">

* **Flow Variables** - These are variables containing counts of something that happen per time period or other flow situations, such as births or new buildings

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/cb5d6f428715aa092106a0f790ad5f30433e6259/Documentation/flow.jpg" width="100">

* **Paramter Variables** - These are all other variables, such as rates, shares and constants

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/cb5d6f428715aa092106a0f790ad5f30433e6259/Documentation/parameter.jpg" width="100">

* **Procedure Boxes** - These boxes contain all the TOOL code. TOOL is the multidimensional array language used to transform the inputs variables to output variables. Double click on the procedure boxe to see the code within.

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/cb5d6f428715aa092106a0f790ad5f30433e6259/Documentation/calculator.jpg" width="100">

## Links and Connectivity
The model diagram can be navigated by following variable linked throughout the diagram. Refer to the following video for more detail

[![](https://github.com/whatIfTechnologies/ESS_public/blob/cb5d6f428715aa092106a0f790ad5f30433e6259/Documentation/Connectivity%20video.jpg)](https://www.youtube.com/watch?v=IRO5ZW0ZF-8)

* **Links from one calculator to another** - The yellow box with the solid border indicates this variable is used in another calculator. Double click to proceed to that calculator

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/2ac15bf5a083306603c2af65ea5ba9a083de16e1/Documentation/external%20link.jpg" width="150">

* **Links from one calculator to another (shared)** - The yellow box with the dotted border indicates this variable is used in multiple calculators. Double click to proceed to that calculator

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/2ac15bf5a083306603c2af65ea5ba9a083de16e1/Documentation/shared%20link.jpg" width="150">

* **Links internal to as calculator** - The white box with the solid border indicates this variable is used somewhere else with this calculators. Double click to proceed to the other instance of that variable

<img src="https://github.com/whatIfTechnologies/ESS_public/blob/2ac15bf5a083306603c2af65ea5ba9a083de16e1/Documentation/internal%20link.jpg" width="150">
