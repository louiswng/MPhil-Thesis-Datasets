This README.txt file was generated on 20240922 by WANG Tianle

-------------------
GENERAL INFORMATION
-------------------

1. Title of Dataset: Denoising Social Recommendation with Self-Supervised Learning

2. Author Information
<create a new entry for each additional author>

First Author Contact Information
    Name: WANG Tianle
    Faculty: Engineering
    Email: louis.wng@outlook.com

Corresponding Author Contact Information
    Name: HUANG Chao
    Faculty: Engineering
    Email: chaohuang75@gmail.com


---------------------
DATA & FILE OVERVIEW
---------------------

Directory of Files:
   A. Filename: test_Data.pkl        
      Short description: The dataset used for testing has been negatively sampled at a ratio of 1:100.        


        
   B. Filename: train.pkl        
      Short description: The interaction data used for training.         


        
   C. Filename: trust.pkl        
      Short description: The social data used for training. 


Additional Notes on File Relationships, Context, or Content 
(for example, if a user wants to reuse and/or cite your data, 
what information would you want them to know?):

If you find DSL useful in your research or applications, please kindly cite:
@article{wang2023denoised,
  title={Denoised Self-Augmented Learning for Social Recommendation},
  author={Wang, Tianle and Xia, Lianghao and Huang, Chao},
  journal={arXiv preprint arXiv:2305.12685},
  year={2023}
}            

File Naming Convention: All files are in .pkl format.


-----------------------------------------
DATA DESCRIPTION FOR: CiaoDVD
-----------------------------------------
<create sections for each dataset included>


1. Number of variables: 2


2. Number of cases/rows: 6,672 users, 98,875 items, 198,181 interactions, 109,503 social ties


3. Missing data codes:
        Code/symbol        Definition
        Code/symbol        Definition


4. Variable List

    A. Name: user
       Description: user id
                    


    B. Name: item
       Description: item id

-----------------------------------------
DATA DESCRIPTION FOR: Epinions
-----------------------------------------
<create sections for each dataset included>


1. Number of variables: 2


2. Number of cases/rows: 11,111 users, 190,774 items, 247,591 interactions, 203,989 social ties


3. Missing data codes:
        Code/symbol        Definition
        Code/symbol        Definition


4. Variable List

    A. Name: user
       Description: user id
                    


    B. Name: item
       Description: item id


-----------------------------------------
DATA DESCRIPTION FOR: Yelp
-----------------------------------------
<create sections for each dataset included>


1. Number of variables: 2


2. Number of cases/rows: 161,305 users, 114,852 items, 1,118,645 interactions, 2,142,242 social ties


3. Missing data codes:
        Code/symbol        Definition
        Code/symbol        Definition


4. Variable List

    A. Name: user
       Description: user id
                    


    B. Name: item
       Description: item id


--------------------------
METHODOLOGICAL INFORMATION
--------------------------

1. Software-specific information:
<create a new entry for each qualifying software program>

Name: numpy
Version: 1.23.2
System Requirements: Python=3.8
Open Source? (Y/N): Y

Name: scipy
Version: 1.9.1
System Requirements: Python=3.8
Open Source? (Y/N): Y

(if available and applicable)
Executable URL: N/A
Source Repository URL: N/A
Developer: N/A
Product URL: N/A
Software source components: N/A


Additional Notes(such as, will this software not run on 
certain operating systems?):
N/A

2. Equipment-specific information:
<create a new entry for each qualifying piece of equipment>

Manufacturer: N/A
Model: N/A

(if applicable)
Embedded Software / Firmware Name: N/A
Embedded Software / Firmware Version: N/A
Additional Notes: N/A