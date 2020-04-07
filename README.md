# adguard-hosts

curl -s -L https://filters.adtidy.org/extension/chromium/filters/15.txt > adblock.unsorted
sort -u adblock.unsorted | grep ^\|\|.*\^$ | grep -v \/ > adblock.sorted
sed 's/[\|^]//g' < adblock.sorted > adblock.hosts



gedit



    Move the cursor to the line before the first line you want to precede with 0.0.0.0.

    In the Search menu, select Find and Replace….

    In the Find field, type \n.

    In the Replace with field, type \n0.0.0.0\t.

    Press the Find button.

    Press the Replace button repeatedly until all the lines you wanted to add 0.0.0.0 to are complete.
