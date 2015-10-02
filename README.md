# hadoop201510

## install git

- sudo yum install git

- git clone <git>


## Shell Command

- wget https://raw.githubusercontent.com/ywchiu/hadoopiii/master/Data/entry.tsv
- head entry.tsv 
- cut -f 3
- cut -f 3 entry.tsv 
- cut -f 3 entry.tsv | sort | uniq
- cut -f 3 entry.tsv | sort | uniq -c
- cut -f 3 entry.tsv | sort | uniq -c | wort
- cut -f 3 entry.tsv | sort | uniq -c | sort
- cut -f 3 entry.tsv | sort | uniq -c | sort |head
- cut -f 2 entry.tsv
- cut -f 2 entry.tsv | cut -d  '/' -f 2
- cut -f 2 entry.tsv | cut -d  '/' -f 3
- cut -f 2 entry.tsv | cut -d  '/' -f 3 | sort | uniq -c
- cut -f 2 entry.tsv | grep jp | cut -d  '/' -f 3 | sort | uniq -c
- cut -f 2 entry.tsv | grep jp | cut -d  '/' -f 3 | sort | uniq -c | awk '{print $1}'
- cut -f 2 entry.tsv | grep jp | cut -d  '/' -f 3 | sort | uniq -c | awk 'BEGIN{sum=0}{sum += $1}END{print sum}' 
- python -m SimpleHTTPServer

## download from ftp

- ftp 10.120.30.4
- get EHC_2nd_round_train.log ~/EHC_2nd_round_train.log
- split -l 1000000 EHC_2nd_round_train.log
- cat xaa | grep -o "\[.*\]" > xaa.time
- cut -d ' ' -f 1 xaa | sort | uniq -c > xaa.ip 
- cat xaa.time | cut -d ":" -f 1 | sort | uniq -c > xaa.aggtime
- cat xa* | grep -o "\[.*\]" | cut -d ":" -f 1 | sort | uniq -c > x.aggtime
- grep U466226569 xa[a-f] | grep -o "pid=.*;cat"
- cat xa[a-f] | grep -o "pid=.*;cat" | sort | uniq -c > most.prod1
- sort -k 1 -nr most.prod1 | head -n 20


