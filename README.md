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


