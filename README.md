# learning-python
print("hello world")
def reverse_complement(seq):
    ntComplement = {'A':'T', 'C':'G', 'T':'A', 'G':'C'}
     
    revSeqList = list(reversed(seq))
    revComSeqList = [ntComplement[k] for k in revSeqList]
 
    revComSeq = ''.join(revComSeqList)
    return revComSeq        
print (reverse_complement("ATCTGCTCT"))
