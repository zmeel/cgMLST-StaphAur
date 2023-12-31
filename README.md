# Prokka annoted genes of the cgMSLT scheme of Staphylococcus aureus
<br>
The Staphylococcus aureus reference strain (for the SeqSphere+ cgMLST scheme) consists of x sequences.
The cgMLST scheme itself consists of 1861 sequences.<br><br>

1. The [sequence](https://raw.githubusercontent.com/zmeel/cgMLST-StaphAur/main/NC_002951.2%20Staphylococcus%20aureus%20subsp.%20aureus%20COL.fasta) of the reference strain Staphylococcus aureus COL was imported in SeqSphere+ and run throught the cgMLST scheme.<br>
2. The [results](https://github.com/zmeel/cgMLST-StaphAur/blob/main/S.%20aureus_cgMLST_scheme.fasta) were exported and later used in ChatGPT<br>
3. The [sequence](https://raw.githubusercontent.com/zmeel/cgMLST-StaphAur/main/NC_002951.2%20Staphylococcus%20aureus%20subsp.%20aureus%20COL.fasta) of the reference strain Staphylococcus aureus COL was also uploaded to Galaxy and Prokka was run to annotate the whole genome.<br>
4. The [resulting GFF3 file](https://raw.githubusercontent.com/zmeel/cgMLST-StaphAur/main/S.%20aureus%20COL.gff3) was used in ChatGPT to create a table with all ID's of the genes and their positions in the genome.<br>
5. The [Prokka derived ffn file](https://raw.githubusercontent.com/zmeel/cgMLST-StaphAur/main/S.%20aureus%20COL.ffn) was then used to add 60 bases of each gene to the table
```
ID               | Start Position | End Position | First 60 Bases
-----------------+----------------+--------------+--------------------------------------------------------
APEGOOKB_00001   | 544            | 1905         | ATGTCGGAAAAAGAAATTTGGGAAAAAGTGCTTGAAATTGCTCAAGAAAAATTATCAGCT
APEGOOKB_00002   | 2183           | 3316         | ATGATGGAATTCACTATTAAAAGAGATTATTTTATTACACAATTAAATGACACATTAAAA
APEGOOKB_00003   | 3706           | 3942         | TTGGTTCAAGAAGTTGTAGTAGAAGGAGACATTAATTTAGGTCAATTTCTAAAAACAGAA
APEGOOKB_00004   | 3939           | 5051         | ATGAAGTTAAATACACTCCAATTAGAAAATTATCGTAACTATGATGAGGTTACGTTGAAA
APEGOOKB_00005   | 5061           | 6995         | ATGGTGACTGCATTGTCAGATGTAAACAACACGGATAATTATGGTGCTGGGCAAATACAA
APEGOOKB_00006   | 7032           | 9695         | ATGGCTGAATTACCTCAATCAAGAATAAATGAACGAAATATTACCAGTGAAATGCGTGAA
APEGOOKB_00007   | 9782           | 10594        | ATGGAAACGTTAAATTCTATTAACATTCCTAAGCGTAAAGAAGATTCACATAAAGGTGAT
APEGOOKB_00008   | 10920          | 12434        | ATGACTTTATATTTAGATGGTGAAACACTAACAATTGAGGATATTAAATCATTTTTACAA
APEGOOKB_00009   | 12813          | 14099        | ATGTTAGACATTAGATTATTCAGAAATGAGCCTGACACAGTTAAGAGCAAAATTGAATTA
APEGOOKB_00010   | 14749          | 15444        | ATGACAACACATTTAAGTTTTAGACAAGGCGTGCAAGAGTGTATCCTAACATTATTGGGT
```
