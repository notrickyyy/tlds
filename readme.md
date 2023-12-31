for i in `cat tld.txt | sed 's/ //g'`;do cat h11.txt | grep "\.$i\." ;done
