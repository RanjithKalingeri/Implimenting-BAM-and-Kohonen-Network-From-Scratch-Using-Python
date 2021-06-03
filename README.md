
## description 

1. A Bidirectional Associative Memory(BAM)  is required to store the following  M = 4 pairs of patterns:

Set A:  X1 =[1 1 1 1 1 1 ]T,  X2 =[-1 -1 -1 -1 -1 -1 ]T,  X3 =[1 -1 -1 1 1 1 ]T,  X4 =[1 1 -1 -1 -1 -1 ]T

Set B:  Y1=[1 1 1]T, Y2=[-1 -1 -1]T, Y3=[-1 1 1]T, Y4=[1 -1 1]T

Using BAM algorithm, train a W matrix for BAM which can retrieve all the above mentioned 4 pairs. 
Hence test the level of weight corrections of the BAM with examples.

2. Consider a Kohonen network with 100 neurons arranged in the form of a two-dimensional lattice with 10 rows and 10 columns . 
The network is required to classify two-dimensional input vectors such that each neuron in the network should respond only to the input vectors occurring in its region. 
Train the network with 1500 two-dimensional input vectors generated randomly in a square region in the interval between -1 and +1. Select initial synaptic weights randomly in the same interval  (-1 and +1  ) and take the learning rate parameter α is equal to 0.1.

Test the performance of the self organizing neurons using the following
Input vectors:
X1=[0.1  0.8]T,  X2=[0.5  -0.2]T, X3=[-0.8  -0.9]T, X4=[-0.0.6  0.9]T.

## Math behind Implimentation 

for BAM see this pdf : https://docs.google.com/a/iiita.ac.in/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxnY25hbmRpfGd4OjQwM2JlNzhjZmQ1ODY5MmM
for Kohonen Network  : https://docs.google.com/a/iiita.ac.in/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxnY25hbmRpfGd4OjRmMDNhNmI1Yzk2MjY1MjU



### ------------------------------------------------------------------------------------------------------------------------
## Project Name :	         Implimenting BAM and Kohonen Network From Scratch Using Python 
## Developer Name :	       Ranjith Kalingeri - 9182522753 - ranji.iitb@gmail.com - doing MTECH in CS in IIIAllahabad as of 02-06-2021. 
## Upload Date :	         02-06-2021
## project Platform :      Python
## Programming Language :  Python
## IDE Tool :	             Google Collab
## DataSet :	             None
## project Type :	         Machine Learning Application - BAM and Kohonen Network.  
## Operating system :      windows 10 
## Licence          :      It is My personal project and I am opensourcing it. Feel free to download, add more features and send pull request.
