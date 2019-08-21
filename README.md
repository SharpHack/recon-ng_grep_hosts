# recon-ng_grep_hosts
Grep command to sort output of recon-ng html to simple list of domains

grep links from the html report:

grep "<td>" <filename>.html | cut -d ">" -f 3 | cut -d "<" -f 1 | wc -l

