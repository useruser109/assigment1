Question2 Please assign variables to the individual components of your favorite gene! (e.g.promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator, on the standard output! Note: Feel free to create a fictional gene sequence by randomly filling in the gene components by the characters corresponding to individual nucleotide bases.

promoter="AAATTTAAAAATTTTAAA" 5_prime_UTR="CCGGAAATTTAAGGG" start_codon ="AGC" exon1="CCGGAAAATTTCCGAAG" intron="GGGGAAATTTCCCCGGAA" exon2= "TTTAAAGGGCCCAAAT" stop_codon="UAG" 3_prime_UTR="CCCTTTAAAGGGAAAT"

my_favorite_gene = promoter + 5_prime_UTR + start_codon + exon1 +
intron + exon2 + stop_codon + 3_prime_UTR

print("My favorite gene sequence is as follows:") print(my_favorite_gene)
