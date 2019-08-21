# recon-ng_grep_hosts
Grep command to sort output of recon-ng html to simple list of domains

grep links from the html report:

grep "<td>" att_com.html | cut -d ">" -f 3 | cut -d "<" -f 1 | wc -l

