# All corpuses for syzkaller found in open source

## For what?

The corpus.db file contains all the corpora for fuzzing found on the internet. They will help significantly speed up the process of finding bugs and increasing code coverage. 

# How to use                                                                                                                                                                             
Unzip the corpus.db.xz file, then move corpus.db to the syzkaller workdir.
 
At the start of fuzzing, there will be approximately over a million fuzzing candidates.
Depending on your host’s processing power, filtering the fuzzing candidates may take some time. Once the number of fuzzing candidates reaches 0, you will have a ready corpus.db file that is much smaller than the original file.

## links.txt                                                                                                                                                                         

All source links 

## downloadn-links.sh

Mini bash script, for download raw-corpuses via wget.

## corpus.db

Combined corpuses from raw corpuses
 
