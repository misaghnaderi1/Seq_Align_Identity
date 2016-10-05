# Seq_Align_Identity
Pairwise sequence alignment followed by calculating the sequence identity 

This code contains two functions 
1-Calculate the percentage of sequence identity 
2-Align two sequences A and B and show the top alignment. 
  This step uses pairwise2 module from Biopytho
    "This package implements pairwise sequence alignment using a dynamic programming algorithm.

    This provides functions to get global and local alignments between two sequences. A global alignment finds the best concordance           between all characters in two sequences. A local alignment finds just the subsequences that align the best.

    When doing alignments, you can specify the match score and gap penalties. The match score indicates the compatibility between an            alignment of two characters in the sequences. Highly compatible characters should be given positive scores, and incompatible ones          should be given negative scores or 0. The gap penalties should be negative.

    The names of the alignment functions in this module follow the convention <alignment type>XX where <alignment type> is either "global"     or "local" and XX is a 2 character code indicating the parameters it takes. The first character indicates the parameters for matches       (and mismatches), and the second indicates the parameters for gap penalties..." 
                                                                            http://biopython.org/DIST/docs/api/Bio.pairwise2-module.html
                                                                            
    
