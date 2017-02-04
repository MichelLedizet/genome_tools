# genome_tools
```
echo "name,count"
for fasta in data/*.fa; do
  count=$( bash count_seq.sh $fasta)
  echo "$fasta, $count"
done
