Image 1 is the regulatory graph of a published logical model of MAPK signalling in urinary bladder cancer cells.

A bladder cancer cell line carries the FGFR3 S249C mutation and has wild type TP53. The cells are grown without any growth factor and are treated with cisplatin, nutlin-3a and SB203580 together. Find how many protein nodes in Image 1 are active once the network settles.

There are some things which stay fixed. Read the graph as a synchronous threshold Boolean model. At time $0$ every node is inactive except the inputs set by this condition and any node fixed by the mutation or the drugs. At each step all nodes update at once, and a node becomes active when its active activators outnumber its active inhibitors, otherwise it becomes inactive. Inputs and fixed nodes keep their value. Count protein nodes only, including fixed ones, and not the input or phenotype nodes.

Report your final answer as a single integer.
