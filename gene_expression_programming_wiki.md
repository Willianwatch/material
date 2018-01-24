# Gene expression programming

## Encoding:the genotype

&ensp;&ensp;The genome of gene expression programming consists of a linear,symbolic string or chromosome of fixed length composed of one or more genes of equal size.These genes,despite their fixed length,code for expression trees of different sizes and shapes.

## Expression trees:the phenotype

&ensp;&ensp;As shown above,the genes of gene expression programming have all the same size.However,these fixed length strings code for expression trees of different sizes.This means that the size of the coding regions varies from gene to gene,allowing for adaption and evolution to occur smoothly.

## K-expressions and genes

&ensp;&ensp;The k-expressions of gene expression programming correspond to the region of genes that gets expressed.This means that there might be sequences in the genes that are not expressed,which is indeed true for most genes.The reason for these noncoding regions is to provide a buffer of terminals so that all k-expressions encoded in GEP genes correspond always to valid programs or expressions.

&ensp;&ensp;The genes of gene expression programming are therefore composed of two different domains-a head and a tail-each with different properties and functions.The head is used mainly to encode the functions and variables chosen to solve the problem at hand,whereas the tail,while also used to encode the variables,provides essentially a reservoir of terminals to ensure that all programs are error-free.

&ensp;&ensp;It's not hard to see that,despite their fixed length,each gene has the potential to code for expression trees of different sizes and shapes,with the simplest composed of only one node(when the first element of a gene is a terminal) and the largest composed of as many nodes as there are elements in the gene(when all the elements in the head are functions with maximum arity).

&ensp;&ensp;It's also not hard to see that it is trival to implement all kinds of genetic modification(mutation,inversion,insertion,recombination,and so on) with the gurantee that all resulting offspring encode correct,error-free programs.

## Multigenic chromosome

&ensp;&ensp;The chromosome of gene expression programming are usually composed of more than one gene of equal length.Each gene codes for a sub-expression tree(sub-ER) or sub-program.Then the sub-ETs can interact with one another in different ways,forming a more complex program.The figure shows an example of a program composed of three sub-ETs.

&ensp;&ensp;In the final program the sub-ETs could be linked by addition or some other functions,as there are no restrictions to the kind of linking function one might choose.Some examples of more complex linkers include taking the average,the median,the midrange,thresholding their sum to make a binomial classification,applying the sigmoid function to compute a probability,and so on.These linking functions are usually chosen a priori for each problem,but they can also be evolved elegantly and efficiently by the cellular system of gene expression programming.