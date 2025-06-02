# Philia 1.0
Philia 1.0 program is a stock-flow consistent (SFC) model that shows how money circulates between different economic agents, households, businesses, government and banks, which can be run under EVIEWS:
- It enables economic policies to be evaluated in a variety of scenarios, giving decision-makers a clear view of the potential advantages and disadvantages of their choices. 
- It facilitates understanding of the interactions between economic sectors. 
- Its eco-systemic block allows addressing contemporary issues of sustainable development.
- It can be enriched to reflect the growing complexity of the economy, by integrating new modules to more faithfully represent how the economy really works. 
- It takes into account the temporal dynamics to analyze the short- and long-term effects of economic policies. 

## Files and Running the program
To run the model in EVIEWS, you just need to launch 00-philia.

Philia 1.0 Instructions.pdf shows the steps to run the Philia 1.0 Program with screenshots

Philia1.0.zip include all the code modules.

Philia-PRGM.docx displays the entire program by module in a WORD file.

Technicalappendix_PHILIA.docx describes the SFC model and all the equations.

For each module, two files are available VP (for VARIABLES AND PARAMETERS) and EQ (for EQUATIONS).


## Instructions for Running the Philia 1.0 Program

### Requirements

    The statistical software EViews must be installed on your computer.

### Steps to Follow

    1. Download and Extract the Program

        - Download the Philia 1.0 zip file.
        - Extract all files from the archive.

    2. Launch the Program

        - Open the file 00-philia (double-click to launch).
        - This will automatically open EViews and run the 00-philia.prg program.

    3. After Execution

        - The program will generate a Workfile automatically.
        - This Workfile contains all the variables created for each period and each scenario:
            - var_0: base scenario
            - var_1: alternative scenario (Scenario 1)

    4. Data Analysis

        - The model is a Stock-Flow Consistent (SFC) model.
        - Analysis starts from the period when the model stabilizes: from period 150 to period 210.
        - For example, GDP is stored in the variable y_0.

    5. Accessing Additional Modules

        - To open the various modules called by 00-philia, go to:
             File → Open → Program...
 
## Modules
In the Philia 1.0 program, the various economic sectors have been segmented into modules for better analysis. 

In all, there are 11 modules:
- Module  1 named 01-macromodel  : covers the basic equations of a macroeconomic model
- Module  2 named 02-households  : concerns worker and rentier households within the economy 
- Module  3 named 03-social      : invests the social enterprises as companies with virtuous investment behavior
- Module  4 named 04-capitaliste : adresses listed corporation as a response to market logic
- Module  5 named 05-bank        : deals with banks in the granting of credit and the purchase of debt
- Module  6 named 06-fund        : examines investment funds in their financing of the economy
- Module  7 named 07-centralbank : discusses the role of central banks as regulators
- Module  8 named 08-ratesreturns: determines different interest rates and rates of return
- Module  9 named 09-public      : studies the public sector, both government and state-owned enterprises
- Module 10 named 10-ecosystem   : presents the relationship between the ecosystem and the economy 
- Module 11 named 11-biomimicry  : contains the intersectoral monetary ‘trophic’ flows

## LICENSE

This project is licensed under the terms of the license CC BY 4.0.


