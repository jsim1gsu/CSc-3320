# CSc-3320-Lab3
CSc 3320 

Lab3-Part 1

Question 1) Run command: 
./Question1.sh

Question 2) Run command: 
./Question2.sh 

Question 3) Run command: awk '{if($1=="ATOM")print $0}' 4HKD.pdb >> Question3 
Run command: ./Question3A.sh 

Question 4) Run command: awk '{if($1=="HETATM")print $0}' 4HKD.pdb >> Question4 
Run command: ./Question4A.sh

Question 5) Run command: ./Question5.sh 

Question 6) Run command: awk '{if($1=="ATOM")print $0}' 4HKD.pdb >> Question6
Run command: sort -n -k 11n Question6>>Question6A 

Lab3-Part 2

Question 1) Run command: cat OutputKnuts.txt

Question 2) Run command: cat OutputStrings.txt

Question 3) Run command: 
cat OutputKnuts.txt | awk'{sum+=$1} END {print sum}'

Question 4) Run command:
cat Question3.SumKnuts | ./Question2.KnutsToString.sh










