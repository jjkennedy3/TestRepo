# TestRepo
# adding something to merge
# adding something else

|   |   |
|---|---|
|``` 
cat some.log \| grep -i speed \| awk '{print $8}' \| sed -r 's/(`\`^\|<\|`\[`\|`\]`)/ /g' \| awk -F ',' '{sum+=$1}END{print "Average = ", sum/NR}'
```|Here powerful sed comes into play ,using regex we calculate the avg speed from logs using AWK command.|
