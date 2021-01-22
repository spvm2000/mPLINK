mPLINK was modified from PLINK 1.07. 

Modification: add a function to make simulation by specifying the penetrances of AA, Aa and aa ('a' is minor allele)

To reach this purpose, you need give a new format line in the simulation file. The format looks like:

100	disease	0.00	1.00	0.01	0.02	0.2

	The first 4 columns are same as the original PLINK, and the rest columns are the penetrances of AA, Aa and aa,
	respectively.