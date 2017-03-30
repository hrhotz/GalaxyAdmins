# extra python code used for "select sequence files" tool 

import os
import re
import operator
import MySQLdb
import sys




def files_by_requestF(request):
    # list all files (or rather samples) from request
   
    sys.stdout.write('reguest: ' + str(request) + '\n')
    
    files = []
    p = re.compile("AAA")
    q = re.compile("AA")
    r = re.compile("A")
    
    if p.search(str(request)):
    
        files = [('AAA','AAA.fastq',False),('BBB','BBB.fastq',False),]	

    elif q.search(str(request)):
    
        files = [('AA','AA.fastq',False)]	
    
    elif r.search(str(request)):
 
        files = [('A','A.fastq',False),('D','D.fastq',False),('X','X.fastq',False)]	
	
    return files  
