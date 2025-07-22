# General-documentation

The place to read, maintain and post documentation on each iteration of the MRS ASV.  

Learn about:  
* Past ASV iterations:
    + Progress reports
    + Technical reports
    + Older systems
* Overview on the electrical, mechanical and software systems (more detail below)
* Design decisions
* Goals
* Remote control manual
* Traffic light messages
* Set-up

The directory is structured like so:  
```
General-documentation/
│
├── ITERATION_1/  
│   ├── Electrical/  
│   │   ├── Overview.md  
│   │   └── Deep/  
│   │       └── <detailed_docs>.md  
│   │  
│   ├── Mechanical/  
│   │   ├── Overview.md  
│   │   └── Deep/  
│   │       └── <detailed_docs>.md  
│   │  
│   ├── Software/  
│   │   ├── Overview.md  
│   │   └── Deep/  
│   │       └── <detailed_docs>.md  
│   ├── Admin/  
│   |   └── <internal_docs>.md  
|   |  
│   └── UserManual.pdf  
│      
├── ITERATION_2/  
│   └── (same structure)  
|
├── ITERATION_N/
│   └── (same structure)
│  
└── README.md  
```
Each system folder at the top level will include an overview.md file that may have diagrams and top level overviews of the system. This is to give the team and new members a better understanding of each system as a whole, the challenges and goals. These should be written as if anyone reading it is completely new to engineering. 

For more complicated or specific documentation, the document should be placed in the Deep folder. 

The UserManual.pdf contains info on how to use the ASV as if the ASV was used commercially. Another pdf will explain the Njord challenge. 


This is part of the intiative to make MRS more accessible to new members. 
