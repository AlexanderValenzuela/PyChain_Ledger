# Project Title - Pychain Ledger

## Introduction
As a fintech engineer at a large global bank, the primary objective of our decentralized finance team is to build a blockchain-based ledger system with a front end web interface.  This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Technologies
**Python Libraries**

`python 3.7.13`<br>
`streamlit 1.23.1`<br>
`pandas 1.3.5`<br>
`dataclass 0.8`<br>
`datetime`<br>
`hashlib`<br>
`Any, List`

## Installation Guide

[Install Anaconda](https://www.anaconda.com/download/)

[Install Git](https://git-scm.com/downloads) 

To clone and run this application, you'll need Git installed on your computer.
From your command line:
```
# Create a new conda environment
conda create -n whatever_your_name python=3.7 anaconda

# Activate the new environment with the following command
conda activate whatever_your_name

# Iniitlaize git (skip if git is installed)
git init

# Browse to your directory and clone the repository below on your local machine
git clone https://github.com/AlexanderValenzuela/Pychain_Ledger

# Install dependencies in the new conda environment
pip install streamlit

# In the conda environment, launch your preferred source code editor and browse to your directory

# Alternatively, browse to your directory and launch pychain.py

```

## Usage

1.) Launch the app in the Streamlit user interface. In the command prompt or terminal, type the following: streamlit run pychain.py or copy and paste the local or network URL in your preferred browser.<br>
![Screenshot 2023-07-23 at 8 53 02 PM](https://github.com/AlexanderValenzuela/PyChain_Ledger/assets/111409358/de0b2ff2-bbc0-46dc-8277-194240c70ccd)

2.) Pychain.py is launched in a browser.  
![Screenshot 2023-07-23 at 9 03 39 PM](https://github.com/AlexanderValenzuela/PyChain_Ledger/assets/111409358/c3043c8f-6ea7-4fb0-9d09-84e7b462695c)

3.) Add a transaction record to the PyChain by entering information in the following fields: Sender, Receiver and Amount.  Click on the Add Block and Validate Chain buttons.  Adjust the Block Difficulty slider accordingly.<br>
![Screenshot 2023-07-23 at 9 19 18 PM](https://github.com/AlexanderValenzuela/PyChain_Ledger/assets/111409358/b9af39b2-1a80-44ca-bd59-1e4f7900a4f4)


4.) In the Block Inspector drop down menu, select the Block you would like to view.<br>
![Screenshot 2023-07-23 at 9 23 14 PM](https://github.com/AlexanderValenzuela/PyChain_Ledger/assets/111409358/050d3fb2-0821-4448-a30f-ff776610425a)

5.) Below are the details of the selected block.<br>
![Screenshot 2023-07-23 at 9 24 17 PM](https://github.com/AlexanderValenzuela/PyChain_Ledger/assets/111409358/5081f9f7-644e-4d44-9fb0-d16ae273ec3e)


## Contributors
- Firas Obeid, UC Berkeley FinTech Instructor
[GitHub](<https://github.com/firobeid>)

- Hasan Mehommod, Central Tutor Support

- Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)


## License
Licensed under the MIT License

