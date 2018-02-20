# learning-python
print("hello world")
#python实现DNA反向互补
def reverse_complement(seq):
    DNA_Complement = {'A':'T', 'C':'G', 'T':'A', 'G':'C'}
     
    revSeqList = list(reversed(seq))
    revComSeqList = [DNA_Complement[k] for k in revSeqList]
 
    revComSeq = ''.join(revComSeqList)
    return revComSeq        
print (reverse_complement("ATCTGCTCT"))
