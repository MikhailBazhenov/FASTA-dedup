
## FASTA-dedup

This is a Python function for finding unique sequences in fasta file.
To find unique haplotypes among multiple sequences, for example of a gene sequenced in many individuals,  make an alignment, trim it in alignmemt editor to form smooth edges, put result in fasts file, and apply FASTA-dedup function on it. 

```python
fasta_dedup('Grf9-6A_from_10+genomes.fasta')
```

The _results.txt file will contain information on unique sequences:


>The number of alleles = 4<br>
><br>
>Lo7    :   A<br>
>Zavitan	:	B<br>
>Mace	:	C<br>
>Spelt	:	C<br>
>Stanley	:	C<br>
>Lancer	:	C<br>
>Landmark	:	C<br>
>Norin61	:	C<br>
>Paragon	:	C<br>
>ArinaLrFor	:	C<br>
>Jagger	:	C<br>
>Julius	:	C<br>
>Robigus	:	C<br>
>SY_Mattis	:	C<br>
>Cadenza	:	C<br>
>Dublet_Grf9-6A	:	D<br>
>Chinese_Spring	:	C<br>
