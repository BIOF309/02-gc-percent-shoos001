# 02-gc-percent-shoos001
02-gc-percent-shoos001 created by GitHub Classroom
flu_ns1_seq = 'GTGACAAAGACATAATGGATCCAAACACTGTGTCAAGCTTTCAGGTAGATTGCTTTCTTTGGCATGTCCGCAAACGAGTTGCAGACCAAGAACTAGGTGA'

#Count the number of "C"s in the above sequence

C_num = flu_ns1_seq.count('C')


#Count the number of "G"s in the above sequence

G_num = flu_ns1_seq.count('G') 


#Add "C" and "G" counts together

GC_num = G_num + C_num


#Count the total number of nucleotides in the sequence

Nucleotides_length = len(flu_ns1_seq)


#Divide the total number of "C" and "G" nucleotides by the total number of nucleotides

GC_percentage = GC_num / Nucleotides_length * 100

#Print the percentage

print ("GC percentage: " + str(GC_percentage) + " %")
GC percentage: 44.0 %
