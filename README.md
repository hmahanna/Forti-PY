# Forti-PY
Python script to export Fortigate FW configurations 


- install python 3.8.x
- Run the following commands to install Python required packages : 

pip install openpyxl 
pip install regex
pip install tqdm



- download config file from Fortigate FW 
- copy configuration text starting from : " config firewall policy " to "end" 
- save the previous copy to txt file and name it 
- create .xlsx file in the same folder 

- open cmd in the created folder and run the .py file 
- type : python arg1 arg2 arg3 ..... 

where : 
arg x is one of the names defined by fortinet configurations as follows :
 
     - srcaddr
     - dstaddr
     - srcintf
     - dstintf
     - name
     - action 
     
     and so on ........ 
