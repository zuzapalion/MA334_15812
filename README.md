This code is a part of MA334 - UG Dissertation in Mathematics course at the London School of Economics and Political Science. It was created by Zuzanna Palion, BSc Mathematics with Economics (Candidate Number: 15812)for the purposes of performing computational experiments within the topic "On Dyadic Fractional Packings of T-joins". 

File Snarks.txt contains a list 195 snarks encoded line-by-line via graph6 format, readable by Python. It should be downloaded to a user's desktop and its file location path should be copied in the place of '/Users/zuzapalion/Desktop/Snarks.txt' in MA334_Code_15812 (line 4). 

File MA334_Code_15812 is a Python notebook that requires SageMath 9.2 kernel available to run. 
  The first part of the code defines 9 necessary function to perform the tasks of interest in the second part of the code: find a maximum fractional packing of T-joins for each snark and check if it is dyadic, time the running of the program, and calculate total % of snarks with dyadic optimal solutions found. 
  The code includes all the comments a user needs to familiarise himself/herself with in order to adopt the methodology. 
  Note that the run time on all 195 snarks together is around 40 minutes. In order to investigate a subset of the list of snarks, manipulate the range after "# Iterate through 194 snarks to look for maximum fractional packings of postman sets that are dyadic:" in the last cell of the code. 
