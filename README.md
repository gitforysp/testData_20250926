
The experimental data (File format: *.txt) used to support the findings of this study are included within the supplementary information file(s).

===========================Description===========================
The data are divided two sections:

 a) Small  (Containg 240 instances)
 b) Large  (Containg 400 instances)


Format of the test data:
Each problem instance is titled by the following free format:
a) Number of jobs                 
b) Ratio of capacity C on machine 1 to the number of jobs n  (Jobs*)
c) beta1  (φ1)
d) beta2  (φ2)
e) beta1  (φ3)
    such as   
         20-Rate_C-0.33-beta1-0.5-beta2-0.5-beta3-0.5-case1.txt 
		 (total 20 jobs, C/n = 0.33, φ1=0.5,φ2 =0.5,φ3 =0.5, )


IN each instance :

P=[...]  represents the processing times for each job on the second machine (M2) :
	such as:
	P=[14	11	10	;
		12	13	11	;
		11	14	14	;
		13	10	15	;
		11	10	11	;
		14	12	12	;
		11	10	12	;
		14	12	11	;
		……
		];
	/*  
    each row: each job
	first column: processing time of the first operation on M2
	second column : waiting time between the two operation on M2
	third   column :  processing time of the second operation on M2
	…………

    */

 P_lower=[…………] represents the minimum processing time of each job on machine M1



 
