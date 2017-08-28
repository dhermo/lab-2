# Informe de laboratorio 02 - Alineamiento de Secuencias
Diego Hermosilla Alfaro

## Parte 1 - Colectar genes homólogos

¿Que función cumple el gen SRY?
  - Este gen codifica un factor de transcripción, perteneciente a la familia de proteínas *DNA-binding*. Esta proteína inicia la determinación sexual masculina.

¿Cuántos genes ortólogos están anotados en esa base de datos?
  - En esta base de datos se encuentran 26 genes ortólogos.



>NM_003140.2 Homo sapiens sex determining region Y (SRY), mRNA
TGTTGAGGGCGGAGAAATGCAAGTTTCATTACAAAAGTTAACGTAACAAAGAATCTGGTAGAAGTGAGTT
TTGGATAGTAAAATAAGTTTCGAACTCTGGCACCTTTCAATTTTGTCGCACTCTCCTTGTTTTTGACAAT
GCAATCATATGCTTCTGCTATGTTAAGCGTATTCAACAGCGATGATTACAGTCCAGCTGTGCAAGAGAAT
ATTCCCGCTCTCCGGAGAAGCTCTTCCTTCCTTTGCACTGAAAGCTGTAACTCTAAGTATCAGTGTGAAA
CGGGAGAAAACAGTAAAGGCAACGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATCGTGTGGTC
TCGCGATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAGAATGCGAAACTCAGAGATCAGCAAGCAGCTG
GGATACCAGTGGAAAATGCTTACTGAAGCCGAAAAATGGCCATTCTTCCAGGAGGCACAGAAATTACAGG
CCATGCACAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCCGAAGAA
TTGCAGTTTGCTTCCCGCAGATCCCGCTTCGGTACTCTGCAGCGAAGTGCAACTGGACAACAGGTTGTAC
AGGGATGACTGTACGAAAGCCACACACTCAAGAATGGAGCACCAGCTAGGCCACTTACCGCCCATCAACG
CAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTGGACAAAGCTGTAGGACAATCGGGTAACATT
GGCTACAAAGACCTACCTAGATGCTCCTTTTTACGATAACTTACAGCCCTCACTTTCTTATGTTTAGTTT
CAATATTGTTTTCTTTTCTCTGGCTAATAAAGGCCTTATTCATTTCA

>NM_001008988.1 Pan troglodytes sex determining region Y (SRY), mRNA
ACTAGGGGGTAGGCTGGTTGGGAGGGGTTGAGGGGGTGTTGAGGGCGGAGAAATGAAAGTTTCATTACAA
AAGTTAACGTAACAAAGAACCTGGTAGAAGTGAGTTTTGGATAGTAAAATAAGTTTCGAACTCTGGCACC
TTTAAATTTTGTCGCACCCTCCTTGTTTTTGACAATGCAATCATATGCTTCTGCTATGTTAAGCGTATTC
AACAGCGATGATTACAGTCCAGCTGTGCAACAGAATATTCCCGCTCTCCGGAGAAGCTCTTCCTTCCTTT
GCACTGAAAGCTATAACTCTAAGTATCAGCGTGAAACGGGAGAAAACAGTAAAGATAGCGTCCAGGATAG
AGTGAAGCGACCCATGAACGCATTCTTCGTGTGGTCTCGCGATCAGAGGCGCAAGATGGCTCTAGAGAAT
CCCAGAATGCGAAACTCAGAGATCAGCAAGCAGCTGGGATACCAGTGGAAAATGCTTACTGAAGCCGAAA
AATGGCCATTCTTCCAGGAGGCACAGAAATTACAGGCCATGCACAGAGAGAAATACCCGAATTATAAGTA
TCGACCTCGTCGGAAGGCGAACATGCTGCCGAAGAATTGCAGTTTGCTTCCCGCAGATCCCGCTTCGGTA
CTCTGCAGCGAAGTGCAACTGGACAACAGGTTGTACAGGGATGACTGTACGAAAGCCACACACTCAAGAA
TGGAGCACCAGCTAGGCCACTTACCGCCCATCAACGCAGCCAGCTCACCGCAGCAACGGGACCGCTACAG
CCACTGGACAAAGCTGTAGGACAATCGGGTAACATTGGCTACAAAGACCTACCTAGATGCTCCTTTTTAC
GATAACTTACAGCCCTCACTTTCTTATGTTTAGTTTCAATATTGTTTTCTTTTCTCTGGCTAATAAAGGC

>XM_015473954.1 PREDICTED: Bos taurus sex determining region Y (SRY), mRNA
TCGTATGCTTCTGCTATGTTCAGAGTATTGAACGACGATGTTTACAGTCCAGCTGTGGTACAGCAACAAA
CTACTCTCGCTTTTAGGAAAGACTCTTCCTTGTGCACAGACAGTCATAGCGCAAATGATCAGTGTGAAAG
GGGAGAACATGTTAGGGAGAGCAGCCAGGACCACGTCAAGCGACCCATGAACGCCTTCATTGTGTGGTCT
CGTGAACGAAGACGAAAGGTGGCTCTAGAGAATCCCAAAATGAAAAACTCAGACATCAGCAAGCAGCTGG
GATATGAGTGGAAAAGGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGC
CATACACCGAGACAAATACCCGGGCTATAAATATCGACCTCGTCGGAGAGCCAAGAGGCCACAGAAATCG
CTTCCTGCAGACTCTTCAATACTATGCAACCCGATGCATGTAGAGACATTGCACCCCTTCACATACAGGG
ATGGTTGTGCCAAGACCACATACTCACAAATGGAAAGCCAATTAAGCCGGTCACAGTCCGTGATCATAAC
CAATTCACTCCTGCAAAAGGAGCATCACAGCAGCTGGACAAGCCTGGGCCACAATAAGGTAACATTGGCT
ACACGGATTTCGGCGGACTTTCCCTGTAACAAAAGCTTAGAGCCTGGACTTTCTTGTGCTTATTTTCAAT
ATTGA

>XM_007990942.1 PREDICTED: Chlorocebus sabaeus sex determining region Y (SRY), mRNA
CCTAGGCGACAGAGCGAAACTCCATCTAAAAACAAAACAAAACAAAAACTTCTAAGTATATGTTAATATT
CTGATACTTAATGCCTGTGAAAAATGTGTATAGAATTTTCATATACTCTTTAAATAGAAGTGAAGAAAAA
GCGATAATGATTACTATAAATTCAATATGCAGTTATGTATGTATGTATGTGGTTAACACAATTAGGTTCT
CATTAAGCTTTGTTTTTTAAAAGTAACAAGCACATATATTGATAATGATAAACAATTCATATAGCTTTTT
CTGTCCTCTCAACTGGCGTAAAAGGTCAGTGAAAAAATTGGGAATTAAGTCAAATTTGCACTTTTCAGGA
GAGTAGTAGAGCCTTCAAGGCGGCCGATCAGCAGGGCAAGTAGTCAATGTTACTGAATTATCATGTTTTG
CTTGAGAATGAATACATTGTCAGGGCACTAGGGGGTAGCCTGGTTGGGCGGAGTTGAGAGGGGGGTTGGG
GGCGGAGAAATGAAAGTTTCATTACAAAAGTTAAGCTAACAAAGAATCTGGTAGAAGTAAGTTTTGGATA
GTAAATTAAGTTTCAAAATCTGGCACCTTTCCGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAATCA
TATGCTTCTGCCAAGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGAATATTCCTG
CTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCACTGTGAAGCAGGAGA
AAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGCGAT
CAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGCTGGGATACC
AGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCA
TAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGCAGT
TTGCTTCCGGCAGATCCCTCTTCGGTACCCTGCAGAGAAGTGGAACTGGACAACAGGTTGTACAGGGATG
ACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAACACAGCCAG
CTCACCGCAGCAATGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAACCGGGTAACACTGGCTACA
AAGACCTATGTAGATGCTTGTTTTTACGGTAACTTACAGCTTTCTTATGTTTACACTTTCTTATGTTTAG
TTTCAATATTGTTTTCTTTTCTCTGACTAATAAAGGTCTTATTCATTTCGGTTTTACTGGTATTTCATTT
TAAACTTAATTTCAAGACAAGTTGTGTCAACGCGATTAACTTGCAAAGAAATAAAACATCCAGAAGTGAT
CCTGCCTATGTTTGTGGCTATTTAACAGAGTACTAACTTGATACAAAGAGACACTGCGGTTTATTTTAAA
TACTCTAATAAGAAACACATTTCAAAATTGTGCGAAAAGAAATCACACTTCTATATGCAGCGTGTTAGTC
AGTCCTTTCTAGACTGTGTATATACATTGGTCTTTCAGTTACTTTGCATGTCTCTGTAAATTGCAGGTAA
CTAAGGAATGGATATGTAAGCAGGATCAAACTTGTTTCTTTCTCTCCCGCCACACCCAGCTTATTTGTGT
ATTTTTAGAGAGGGGGTTCCACCCTGTTGGCC

>XM_008709959.1 PREDICTED: Ursus maritimus sex determining region Y (SRY), mRNA
ATGTTCGGAGTATTGAACAGCGATGATCACTGTGCAGCGGTACAACAACGAAATATCCTTGCTTTTGGAA
GAACATTTTCGGAATTTTGGATGAACAATCCTACCTCAAATTACCGGTGTGAAACCGAAGGAAATAGTAG
AGACAGCGGCCAGAACCGCGTCAGACGACCCATGAACGCATTCATGCTGTGGTCTCGTGATCAAAGGCGC
AAGGTGGCTCTAGAGAATCCCCAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTACCAGTGGAAAA
TGCTTACGGAAGCCGAAAAATGGCCATTTTTTGAGGAGGCACAGAGACTACAGGCCATGCACCGACAGAA
ATACCCAGACTATAAATATCGACCCCGTCGGAAGGCCACGCCACAGAAAGATGACAAATTGCTACCTTCA
GCTTCTTCCTCCACGCTATGCAGGCAGGTGCGCGTGGATGAGACGTGGTACCCCTTCACCTACAGGAACA
GCCATACTAGGGCTGCGCACTCAGGAATGGAGGACCAGCTAAGCTCCTCACAACCCGTGAACGTAGCCAG
TTCGCTGCTGCAGCAGGAGCAGCACTGCAGCTCCACAAGCTTCCGTGACAGCCGAGAAACCTTGGCTACA
CAGCTGTGGGCTGACCCTCCCTTTTACCCTAAGTAA

>NM_001032836.1 Macaca mulatta sex determining region Y (SRY), mRNA
ATGCAATCATATGCTTCTGCCATGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGA
ATATTCCTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCAGTGTGA
AGCAGGAGAAAACAGTAAAGGCAGCGTCCAGGATAAAGTGAAGCGACCCATGAACGCATTCATTGTGTGG
TCTCGCGATCAGAAGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACA
GGCCATGCATAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAAC
AGTTGCAGTTTGCTTCCGGCAGATCCGTCTTCGGTACCCTGCAGAGAAGTGCAACTGGACAACAGGTTGT
ACAGGGATGACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAA
CACAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAG

>XM_006914921.1 PREDICTED: Pteropus alecto sex determining region Y (SRY), mRNA
ATGCCCAGTGCTAGTGGCAACAGGTTTTATGACCTCTACTATGCACCCCCAGATTCAGCAGAGGCAGTGA
CCAGTTGCAGATTGCTTTTTAGCTCCCACCAGTTGTTCAGCATCATATCTAGTTCCAATCACAGGCCGGG
CGTACAGCAACAAAATATGCTGGCCTTTGGGAAAAACTCTTCCCTACTTTGGACAGACAAACCTAGTTCA
AACTGTGATACAGGAGGAAAAGGAAGAGATAGCAGACAGGACCGAGTCAAACGACCCATGAACGCATTCA
TAGTGTGGTCTCGTGATCAAAGGCGCAAGGCGGCTCTAGAAAATCCCAAAATGCAAAACTCGGAGATCAG
CAAGCGACTGGGATATCAATGGAAAATGCTTACGGAAGCTGAAAAACAGCCATTCTTCGAGGAGGCACAG
AGACTACGCGCCTTGCACCGAGAGAAATACCCGGACTATAAATATCGACCTCGTCGGAAGGCCAAGATGC
CACAGAAAAGTAAAAAATTACTACCCGCAGACTCCTCTTCAATACTGTGCAGACAAGAGCACGTGGATAT
GAGGTTGTATCCCATTACTTACAAGGCCAGCTATCCTGAGACCAGCCACTCACGCATTCAGGACCAGTTA
AGGCACTCACCACCCACCAACAGAGCCAGCTCCGTCCTGCAACAGAGCCAGCTCCGTCCTGCAACAGGAG
CTCCACCGCAGCTCGATAAGCCTGCGTTAACAATCTGGTAA

>XM_006195400.1 PREDICTED: Camelus ferus sex determining region Y (SRY), mRNA
ATGCAATCATATGCTTCTGCTATGTTTGCGGAACTGAATGGTGATAATTACAGCTCAGCGGTACAGCAAC
AAAATATCCTTTCCTTCAGGAAAGCCTCCTCGCTACTTCAGAGAGACAATCGTAGCTCAAAAGGTCTGTA
TGAAACTGGAGGAAACGGTAGAGAGTACATGAAGGACCGTGTCAAGCGACCCATGAACGCTTTCATTGTA
TGGGCTCGTGATCAAAGGCGAAAGGTGGCTCTAGAGAATCCCAAAATGCAGAACGCAGAGATCAGCAAGC
GGCTGGGATACCAGTGGAAATTACTTACAGAAGCTGAAAAGCGGCCGTTCTTCGAGGAGGCGCAGAGACT
CCGGGCCATACATCGGGACAAATACCCGGACTGTAAATACCAACCTCGTCAGAAGACCGAGGGGCTACCG
AGAAGTGACAAATCATTTCCCACAGACCCTTCAACACTATGCAGCCAGGTACATGTAGACGACCGTTTGT
ACTCCTTCACATACACGGACCATTGTGCCAAGACACCGCAGTCACGAATGGAAGGCCCGTTAAGTCCCTC
ACAACGGATGAGCATTACCAGCTCACTCCCTCAGCAAGAGCACTGCAGCAACTGGACAAGCCTGCACCAC
ACTAGGGTGACACTGGCTACACAGATCTCTGCGGATGGTCCCTTTTACTGTAGTTTGCAGCCTGGACATT
CTCACCGTTACTTTTGGTGTTGA

>XM_021693078.1 PREDICTED: Neomonachus schauinslandi sex determining region Y (SRY), mRNA
TTTTATGCTTCTGCTATGTTCGGAGTATTGAACAGCAGTGATCACCGTGCAGCGGTACAACAACGAAATA
TCCCCGCCTTTGGAAGAACCTCTTTTGAACTGTGGACGGACAATCCTACCTCAAACTATCGGTGTGAAAC
CGGAGGAAACGGCAGGGATAGCGGCCAGAACCGCGTCAGACGGCCCATGAACGCATTCATGGTGTGGTCG
CGTGATCAAAGGCGCAGGGTGGCTCTAGAGAATCCCCAAATGAAAAACTCAGAGATCAGCAAGCAGCTGG
GGTACCAGTGGAAAATGCTTACAGAAGCCGAAAAATGGCCATTCTTCGAGGAGGCACAGAGACTACAGGC
CATGCACCGAGAGAAATACCCAGACTATAAATATCGACCTCGTCCGAAGGCTCTGCCACAGAAAAGTGAT
AAATTGCTACCTGCAGCCTCCTCCTCCATGCTATGCAGGCAGGTGCTCGTGGATGAGAAATGGTATCCCT
TCACGTACAGGGACAGCTGTAGTAGGGCTGCACACCCACGTATGGAGGACCAGTTAAGCTCCTCACAACC
CGTGAACATAGCCAACTCGCTGCTGCAACAGGAGCACCACTACTGCTCCACAAGCCTCCGTGACAGTCCA
GAAACCTTGGCTATGCATCTGTCCGCTGACCCTCCCTTTTACCCTAAGTAA

>XM_020896759.1 PREDICTED: Odocoileus virginianus texanus sex determining region Y (SRY), mRNA
ATGTTCAGAGTATTGAACGACGATGTTTACAGTACAGCCGAGATACAACAACAAAATCCTCTCGCCTTTG
GGAAAGCCTCTTCCTTGTTCATAGACCATCGCAGCGCAAATGATCAGTGTGAAACGGGAGAAAATGTTAG
GGACAGCGGCCAGGACCACGTCAAGCGACCCATGAACGCGTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACAGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAAAACGAAGAGGCAACAGAAATTGCTTCCTGCAGACTCT
TCAATACTACGCAAACAGATGCATGTAGAGACATTGCAGCCCTTCACATACAGGGACGGTTGTGCCAAGA
CCACATGCTCACGAATGGAAAGCCAGTTAAGCCTCTCACAGTCTGTGACCATAACCAATTCATTCCTCCA
AAAGGAGCATCACAGCAGCTGGACAAACCTGGGCCACAATAGGGTAACATTGGCTACACAGATTTCCTCG
GACTTTCCCTTTTATCAAAGTTTACAGCCTGGACTTTCTTGCGCTTATTTTCAATACTGA

>XM_019956600.1 PREDICTED: Bos indicus sex determining region Y (SRY), mRNA
ATGTTCAGAGTATTGAACGACGATGTTTACAGTCCAGCTGTGGTACAGCAACAAACTACTCTCGCTTTTA
GGAAAGACTCTTCCTTGTGCACAGACAGTCATAGCGCAAATGATCAGTGTGAAAGGGGAGAACATGTTAG
GGAGAGCAGCCAGGACCACGTCAAGCGACCCATGAACGCCTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGAAAAACTCAGACATCAGCAAGCAGCTGGGATATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACCGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAGAGCCAAGAGGCCACAGAAATCGCTTCCTGCAGACTCT
TCAATACTATGCAACCCGATGCATGTAGAGACATTGCACCCCTTCACATACAGGGATGGTTGTGCCAAGA
CCACATACTCACAAATGGAAAGCCAATTAAGCCGGTCACAGTCCGTGATCATAACCAATTCACTCCTGCA
AAAGGAGCATCACAGCAGCTGGACAAGCCTGGGCCACAATAAGGTAACATTGGCTACACGGATTTCGGCG
GACTTTCCCTTTAACAAAAGCTTAGAGCCTGGACTTTCTTGTGCTTATTTTCAATATTGA

>XM_018044472.1 PREDICTED: Capra hircus sex determining region Y (SRY), mRNA
ATGAATAGAACGGTGCAATCGTATGCTTCTGCTATGTTCAGAGTATTGAAAGACGATGTTTACAGTCCAG
CGGTGGTACAGCAACAAAATACTTTCGCCTTTGGGAAAACCTCTTCCTTGTGCACAGACAATCATAGTGC
AAATGATCAGTGTGAAAGGGGCGAAAATGTTACGGAGAGCAGCCAGGACCACGTCAAGCGACCCATGAAC
GCCTTCATTGTGTGGTCTCGTGAACGAAGACGAAAGGTGGCTCTAGAGAATCCCAAATTGCAAAACTCAG
AGATCAGCAAGCAGCTGGGATACGAGTGGAAAAGGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGA
GGCACAGAGACTACTAGCTATACACCGAGACAAATACCCGGGCTATAAATATCGACCTCGTCGGAAAGCC
AAGAGGCCACAGAAATCGCTTGATGCAGACTCTCCAATACTATGCAACCAGATGGATGTAGAGACATTGC
ACCCCTTCACATACAGGGACGATTGTGCCAAGACCACACACTCACAAATGGAAAGCCAATTATGCCGCTC
ACAGTCCCTGATTCTAACCAATTCACTTCTGCAAAAGGAGCATCACAGCAGCTGGACAAACCTGGGCCAC
GATAGGGTAACATTGGATACACGGATTTCCGCGGACTTTCCCTTTTACCAAAGCTTAGAGCCTGGGCTTT
CTTGCGCTTATGTTCAATACTGA

>XM_017847138.1 PREDICTED: Rhinopithecus bieti sex determining region Y (SRY), mRNA
CTTAATGCCTGCGAAAAATGTGTATAGAAATTCTATACACATTTACTCTTTAAATAGAAGTGAAGAAAAA
GCGATAATGATTACTATAAATTCAATATGCAGTTATGTATGTATGTATGTATGTGGTTAACACAATTAGG
TTCTCATTAAGCTTTGTTTTTTAAAGGTAACATGCACATATATTGATAATGATAAACAATTCATGTAGCT
TTTTCTGCCCTCTCAACTGGCGTAAAAGGTCAGTGAAAAAATTGGTGATTAAGTCAAATTTGCATTTTTC
AGGAGAGTAGTAGAGCCTTCAGGGCGGCCGATTGGCAGGGCAAGTAGTCAATGTTACTGAATTACCGTGT
TTTGCTTGAGAATGAATACATTGTCAGGGCACTAGGGGGTTAGCTGGTTGGGCGGAGTTGAGAGGGGTGT
TGGGGGCGGAGAAAGAAAGTTTCATTACAAAAGTTAAGGTAACAGAGAATCTGGTAGAAGTAAGTTTTGG
ATAGTTAATTAAGTTTCCAAATCTGGCACCTTTCAGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAA
TCATATGCTTCTGCTATGTTAAGCGTATTTAACACTGATGATTACAGTCCAGCTGCGCAACAGAACGTTC
CTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCGGTGTGAAGCAGG
AGAAAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGC
GATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCTAAACTCAGAGATCAGCAAGCAGCTGGGAT
ACCAGTGGAAAATGCTTACCGAAGCCGATAAACGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCAT
GCATAGAGAGAGATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGC
AGTTTGCTTCCCGCAGATCCTTCTTCGGTACTCTGCAGAGAAATGGAACTGGACAACAGATTGTACAGGG
ATGATTGTATCAAAGCCACACACTCAAGAATGCAGCTAGGCCACTTACCGCCCATCAACACAGCCAGCTC
ACCGCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAATCGGGTAACACTGGCTACAAAG
ACCTATGTAGATGCTCGTTTTTACGGTAACTTACAGCCCTCACTTTCTTATGTTTAGTTTCAATATTGTT
TTCTTTTCTCTGACTAATAAAGGTCTTATTCATTTTGGTTTTACTGGTATTTCATTTTAAACTTAATTTC
AAGACAAGTTGTGTCAACACGATTAACTTGCAAAGAAATAAAACATCCAGAAGTGATCCCGCCTATGTTT
GTGGCTGTTTAGCAGAGTACTAACTTGATACAAAGAGACACCGCGGTTTATTTTAAATACTCTAATGAGA
AACACATTTGAAAATTGTACAAAAAGAAATCACACTTCTATATGCAGCATGTTAAGCAGTCCTTTCTAGA
C

>XM_017518856.1 PREDICTED: Cebus capucinus imitator sex determining region Y (SRY), mRNA
TGAATTTTTCAGTACCCTGCTTGTTTTTGACAATGCAGTCTTATGCTTCCACTATGCTGAGAGTATTTAA
CTGTGATGAATACAGTCCAGCTGCGCAACAGAATATCCCTGCTTCCGGGAAAAGCTCTTCCGTCGTTTGG
ACTGAGAACTCTAGCTCAAAGTATCAGTGCGAAACAGGAGAAAACAGTAAAGGCAACGTCCAGAACAGAG
TGAAGCGACCCATGAACGCTTTCATTGTGTGGTCTCGTGACCAAAGGCGCAAGATGGCTGTAGAGAATCC
CCAGATGCGAAACTCAGAGATCAGCAAGCGGCTGGGATACCAGTGGAAATTGCTTACTGAAGCCGAAAAA
TGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCACAGAGAGAAATACCCGAATTATAAGTATC
GACCTCGTCGGAAGGCCAACTTACTGCAGAACAATGACAGTTTGCGTCCCGTCGATCCCTCTTCAGAGCT
CTGTAACGAAATGCAAGTAGAAGACAGGTTGTACACCTTCTCATACAGGGATAACTGTACGAAATCCACC
CAATCAATAATGGAGCACCAGCTAGTCCACTCACCTCCAGTCAACCCAGCCAGCTCACCGCAGCAGCGGG
ACCGCTACAGCAACTCGACAAACCTGCAGGGCAATCGGGTAACATTGACTACAAAGAGCTATGCAGACTG
TCCTTTTTACCGTTAA

>XM_016217292.1 PREDICTED: Miniopterus natalensis sex determining region Y (SRY), mRNA
ATGTTAAGAGTAATAAACAGCGATGATGATTACAATCCAGTGGTACAGCAACAAACTATCCTGGCTTTTG
GGGAAACCTCTTCCCTACTTTGGATGGGCAATCCTAGCTCAAATTATCGGTGTGAAACAGGAGGAAATGG
TAGCGACAAGGGCCGGGACCGCATCAAAAGACCCATGAATGCATTCATGCTGTGGTCTCGAGACCAGAGG
CGCAAGGTGGCTCTAGAAAATCCCAAAATGCAAAACTCAGAAATCAGCAAGCGTCTGGGAAACCAGTGGA
AAATGCTTACAGAAACCGAAAAATGGCCGTTCTTCGAGGAGGCACTGAGGCTCCGTGACGAGCACAGAGA
GAAATACCCGGACTACAAATATAGACCTCGTCGGAAGGTCAACATACCACCGAAAAGTGACTATCGCACC
CCGCAGATTTCCTCTTCAATACTATGCAGCCGGATCCATGTGGAGGGGCGGTTGCACCCTATCCCATACA
GCCGCATCTCTACTACGACCACACACTCACGAATGGAGGACCAGTTAAGCCGCTTGCAACCCATGAATAG
AGTCAGCTCGGTGCTGCGACAGGAGCAGGGCCGCAGCTTCACAGGCCTGTGA

>XM_015488163.1 PREDICTED: Marmota marmota marmota sex determining region Y (Sry), mRNA
TCTTCGGCTATGTTCACAGTACTGAACCCCAGCGATTACAGTCCAGCCCAGAAGCAACAGGATGGCCTCG
ACTTCGGAAAAAACTCTTCCTTCCTTGGGATCGACCACTCTAGCTCAAATGATCAGTGTGAAACAGGAGG
CAACCTTAAAGGGACCCAGGGCCGGGTCAAGAGACCCTTGAATGCTTTCATGGTATGGTCTCGCGACCAG
CGGCGCAAGATGGCTCTGGAGAACCCCAGCATGCGAAATTCAGAGATCAGCAAGCTGCTGGGATACCGGT
GGAAAACGCTTACAGAAGCCGAAAAATGGCCATTCTTCCAAGAGGCACAGAGACTACAGGCCATGCACAG
AGAGAAATACCCGAACTACAAGTATCGGCCTCGCAGGAAGGTTAAGACTCAACAGAAGACTGGCAGCAGT
TCGCTGCCCGAAGAGCCCCCATTAAAACTGTGCAGCCAGGCGTCCGTGGACGCGAGGCTGCATAACCTTG
GGCAGCCAGAGCGCAGTTCAGAAAACCTGCACTGATGAAAGCAGAGCCAGCGAAGCCATTCATAGCCCCA
CTTACTGACACCAGCCAGCGGGCT

>XM_014827486.1 PREDICTED: Equus asinus sex determining region Y (SRY), mRNA
ACATATATTCATATTGATAAAGCAATTCATTAGTATCCGTCTGTGCTCCACCTGCATCCTTTCATTTATA
GACCTAATAAAATAATAATGACAAAGTTTGTTTTGTATTATTTTAAGGAGAGGCAGAGCCTTCAGCGCTA
GGGATTAGAAGTAGGGCACAGAAACACTGTGTTATTACTCTGTTATCAGGTTTTGCTTGAGAGTGGATAG
GCTGGTTGGGCTTTGGCTGACGGCCCAGGGCACGTTTGAGGGGAGGAGTTGGGGGCGGAGAAATAAGTAT
TTTATTACAAAAGTTGTAGTAACAAAGCCTCTGCTAGAATAACCTTGGAAAAGTAAGATAATTTTCCCAA
CGCTTTATCTTCGCATTTTGCTACCACCCTCCTCTTCAACGGTGCCATCTTAAGCTTCTGCTATGTCCAG
AGTATCCAACAGCGATAACTACAGTCTAGCAGGACAGCAACAAACCGTTCTCGGCTCTGGGAGAACCTCA
TCCCTACTTTGGACGAGCAATCCTGGCTCACATTTTCGGAGTGAAACAAGAGGAAATGGTAGAGAGAACG
GCCAGGACCGTGTCAAACGACCCATGAATGCATTCATGGTGTGGTCTCGTGATCACAGGCGCAAGGTCGC
TCTAGAGAATCCCCAACTGCAAAACTCAGAGATCAGCAAGCGGCTGGGATGCCAGTGGAAAATGCTTACG
GAAGCCGAAAAATTGCCATTCTTCGAGGAGGCACAGAGACTACGGGCTATGCATCAAGAGAAATACCCGG
ACTATAAATATCGACCTCGTCGGAAGGCCAAGATGCCACAGAAAAGTGACAAACCGCTTCGCGCAGACTC
CTCTTCTACACTGTGCAGGCAGGCGCACGTACACGTCGACGAGTGGTTGAACCCTTTCACATTCGCGGAC
GACTGTACTGAGGCCACACAGTCACAAACGGAGGAGCGGTTAAACCATTCGCAGCCCGCGAACACAGCTA
GTTTGGCGCTGCAACAGGAGCGTTACAGCAGCACCGCAACCCTGCGTGACAATCGGGTAAAGTTGGCTAC
GCAGACATACGCAGACGTTCCCTTTCACTGTAATTTACCCTCCGGACTTTCTCACGGTGATTTTCCTTGA
TT

>XM_010860135.1 PREDICTED: Bison bison bison sex determining region Y (SRY), mRNA
ATGTTCAGAGTATTGAACGACGATGTTTACAGTCCAGCTGTGGTACAGCAACAAACTACTCTCTCTTTTA
GGAAAGACTCTTCCTTGTGCACAGACAGTCATAGCGCAAATGATCAGTGTGAAAGGGGAGAACATGTTAG
GGAGAGCAGCCAGGACCATGTCAAGCGACCCATGAACGCCTTCATTGTGTGGTCTCGTGAACGAAGACGA
AAGGTGGCTCTAGAGAATCCCAAAATGAAAAACTCAGACATCAGCAAGCAGCTGGGATATGAGTGGAAAA
GGCTTACAGATGCTGAAAAGCGCCCATTCTTTGAGGAGGCACAGAGACTACTAGCCATACACCGAGACAA
ATACCCGGGCTATAAATATCGACCTCGTCGGAGAGCCAAGAGGCCACAGAAATCGCTTCCTGCAGACTCT
TCAATACTTTGCAACCCGATGCATGTAGAGACATTGCACCCCTTCACATACAGGGATGGTTGTGCCAAGA
CCACATACTCACAAATGGAAAGCCAATTAAGCCGGTCACAGTCCGTGATCATAACCAATTCACTCCTGCA
AAAGGAGCATCACAGCAGCTGGACAAGCCTGGGCCACAATAAGGTAACATTGGCTACACGGATTTCGGCG
GACTTTCCCTTTAACAAAAGCTTAGAGCCTGGACTTTCTTGTGCTTATTTTCAATATTGA

>XM_010621263.1 PREDICTED: Fukomys damarensis sex determining region Y (Sry), mRNA
ATGTTCAGAAAATTGAAAAGCAAAGACTACTGGCCAGGTGTGCAGCAAGATGTCCTCACCTTTGGAGAAA
ACTTTTCCTACCTTTGGAAGGGCAATGCTTGCTCAAGTTATCAAAATGAAACAGGAGGCAATGATAAAAA
CAGCATCGTGCACCGGGTCAAGAGACCCTTGAATGCATTCATGGTGTGGTCTCGTGACCAGAGGCGCAAA
GTGGCTCTGGAGCATCCCAACTTGCAAAACTCAGAGATCAGCAAGTGGCTGGGGTACCAGTGGAAAATGC
TTACTGAAGCCGAAAAATGGCCATTCTTTCAGGAGGCCCAGAGACTGCAGGCTATGCACAGAAGGAAATA
TCCTGACTATAAGTATCAACCTCGCCGGAAGACTAAGACGCTGCAGCAGAGTAGCAGTTTGCTGCATTCA
GAAACCTCCTTAAACCCTGGTGGCCAAGCACACTTGGAGGAGATGCTGTGTGCCTTGCCCTGCAGGGAAG
GCTTTACTGAGGCTAAGCACTCAGGACTGAAGAACGAGCTAATGATGAGCCACTCTCAGCCCATGGACAC
AGCCAACTTGCTACTGCAACAGAAGGGCCACAGCACCTCCCCAAACCCAGGACAATTAGAAACCTGGCTA
CATGGACACTCAGTTTAA

>XM_010369191.1 PREDICTED: Rhinopithecus roxellana sex determining region Y (SRY), mRNA
GGGCGGAGAAAGAAAGTTTCATTACAAAAGTTAAGGTAACAGAGAATCTGGTAGAAGTAAGTTTTGGATA
GTTAATTAAGTTTCCAAATCTGGCACCTTTCAGTTTTGTCGCACCCTCCTTGTTTTTGACAATGCAATCA
TATGCTTCTGCTATGTTAAGCGTATTTAACACTGATGATTACAGTCCAGCTGCGCAACAGAACGTTCCTG
CTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCGGTGTGAAGCAGGAGA
AAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGGTCTCGCGAT
CAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCTAAACTCAGAGATCAGCAAGCAGCTGGGATACC
AGTGGAAAATGCTTACCGAAGCCGATAAACGGCCATTCTTCCAGGAGGCACAGAAACTACAGGCCATGCA
TAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAACAGTTGCAGT
TTGCTTCCCGCAGATCCTTCTTCGGTACTCTGCAGAGAAATGGAACTGGACAACAGATTGTACAGGGATG
ACTGTATCAAAGCCACACACTCAAGAATGCAGCTAGGCCACTTACCGCCCATCAACACAGCCAGCTCACC
GCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAGGACAATCGGGTAACACTGGCTACAAAGACC
TATGTAGATGCTCGTTTTTACGGTAACTTACAGCCCTCACTTTCTTATGTTTAGTTTCAATATTGTTTTC
TTTTCTCTGACTAATAAAGGTCTTAT

>XM_009820972.1 PREDICTED: Gavia stellata sex determining region Y (SRY), partial mRNA
GCGGAGTGGAAACTTTTATCCGAGGCGGAAAAGAGACCCTTCATTGACGAAGCCAAGCGGCTCAGAGCTC
TGCACATGAAGGAGCACCCGGATTATAAATACCGACCCCGGAGGAAAACCAAGACCCTCATGAAGAAGGA
TAAGTACACGTTGCCAGGGGGCTTACTGGCACCGGGCACCAATACCATGACGACTGGGGTAGGGGTTGGG
GCTACCTTGGGAGCNNNNNNNNNNNNNNNNNNNNNNCTCGGCTACCCGCAGCACCCGGGCTTGAACGCGC
ACAACGCGTCGCAGATGCAGCCCATGCACCGCTACGACGTGAGCGCCCTGCAGTACAACTCCATGACCAG
CTCGCAGACTTACATGAACGGATCGCCTACCTACAGCATGTCTTACTCCCAGCAAGGGACCCCGGGCATG
GCCCTGGGCTCCATGGGCTCGGTGGTCAAGACGGAATCC

>XM_008594334.1 PREDICTED: Galeopterus variegatus sex determining region Y (SRY), mRNA
ATGTTCAGAGTATTGAACGGCGAAAGTCAAAGCCCTGACGTGAAGCAACAGAATATCCCCGACTCCAGGA
AAAACTCTTCCCTCCTTTGGACGGACAATCCTAGCTCAAACGATCGGTGTGAAACGGAAGAAAACGGTAA
AGAGATAGGCCACGACCGGGTCAAGCGACCCATGAACGCATTCATGGTGTGGTCTCGAGACCAGAGGCGC
AAGATGGCTTTAGAGAATCCCAAAATGCAAAACTCAGAGATCAGCAAGCGGCTGGGATACCAGTGGAAAA
CGCTGACAGAAGCCGAAAAATGGCCATTCTTCCAGGAAGCACAGAGATTACAGGCCATACACAGAGACAA
ATACCCGGACTACAAGTATCGACCTCGCCGCAAGGTTAAACTGCTACAGAAGAGTGGACGTTTGCTGCCC
GTAGACCCCTCTTCGGTACTGTGCAGCCAAGTGAACGTGGACCAGAGCGTGTACACCTTCACATACAGGG
AGGGCTATACCAAGGCTGCATACTCACGAATGGAGGACCAGCGAAGCCATTCACAGCCGATGAATACAGC
CTGCTCGATGCTGCAACAGGAGCGCCTCAGCATCTCCTCAGACCTGAGTGACAATCGGGTAATACTGGCA
ACACAGACCTACGGGGACGTTCCTTTTTACCCTGACTTACTGTCCTGA

>XM_008510974.1 PREDICTED: Equus przewalskii sex determining region Y (SRY), mRNA
GCTATGTCCAGAGTATCCAACAGCGATAATTACAGTCTAGCAGGACAGCAACATACCGTTCTCGGCTCTG
GGAGAACCTCATCCCTACTTTGGACGAGCAATCCTGGCTCACATTTTCGGAGTGAAACAAGAGGAAATGG
TAGAGAGAACGGCCAGGACCGTGTCAAACGACCCATGAATGCATTCATGGTGTGGTCTCGTGATCACAGG
CGCAAGGTCGCTCTAGAGAATCCCCAACTGCAAAACTCAGAGATCAGCAAGCGGCTGGGATGCCAGTGGA
AAATGCTTACGGAAGCCGAAAAATTGCCATTCTTCGAGGAGGCACAGAGACTACGGGCTATGCATCAAGA
GAAATACCCGGACTATAAATATCGACCTCGTCGGAAGGCCAAGATGCCACAGAAAAGTGACAAACCGCTT
CCCGCAGACTCCTCTTCTACACTGTGCGGGCAGGCGCACGTACACGTCGACGAGTGGTTGAACCCTTTCA
CATTCACGGACGACTGTACTGAGGCCACACAGTCACAAACGGAGGAGCGGTTAAACCATTCGCAGCCCGC
GAACACAGCTAATTCGGCGCTGCAACAGGAGCGTCACAGCAGCACCGCAACCCTGCGTGACAATCGGGTA
ACGTTGGCTACGCAGACATACGCAGACGTTCCCTTTCACTGTAATTTACCCTCCGGACTTTCTCACGGTG
ATTTTCCTTGATT

>XM_007959089.1 PREDICTED: Orycteropus afer afer sex determining region Y (SRY), mRNA
ATGGCCAGAGTGAAGAGAGATGATTACAGCCCGGCAGCCCGACCCGCTATCAGCACCTTTGGGACCAACC
CTTCCGTACCGTGGAGGAACGATCTTAGTTGCAATTTTCCGTGGGAAACTGGAGGAAACGGGAGAGAGAG
CGGCGAGGCCCGGGTCAAGCGGCCCTTGAACGCCTTTATGGTGTGGTCGCGAGACCAGAGACGCAAGATG
GCTCTAGACAATCCCCAGATGCGAAACTCAGATATCAGCAAGCGGCTGGGATGGCAGTGGAAGACGCTTA
CAGACGCGGAGAAATGGCCATTCTTGGAGGAGGCGCGGAGGCTGCGGGCCCTGCACCGACAGAAATACCC
CGACTATAAGTATCGCCCTCATCGGAAGGCCACGATGCTACAGAAGAGTGTCAAGCTGCTGCCCGCAGGC
TCCTCGTCAATACTGTGCAGCCAGCTGCACGTGAACCCCAGGTTGCACACCTTCACACACACCGATAGCT
GTACACAGGCCCCACGCTCACGAATGGAAGACCAGCCACGCTGCTCACCGTGCATGAACACCGCCAGCTC
ACTGCTCCAAGAGCTGCTCCGCAGCAACTCCACACGCATACAGGACAGCCCCGTGACACTGGTTAATGCA
GACTTCCGCAGGTGCTCCCTTTTACTGTAA

>XM_006163439.1 PREDICTED: Tupaia chinensis sex determining region Y (SRY), mRNA
ATGCTCTCAGCTATGCTCACGATTTGGAACAGCAGTGATTGCAGCCCAGCCCTAGAACAACAGAATCTCT
TCGCCTTGGAGAAAAACTCTTCCTTTCTTGCGACGGACAGCTCTCGCTCAAATTATCGCCGTGAAACAGG
AGTAAATTATAAAGAGCACAGCCAGAACCGGGTCAAGAGACCCATGAACGCGTTCTTCGTATGGTCTCGA
GATCAGAGGCGCAAGCTGGCTCTGGAGAATCCGAAAATGCGAAACTCAGAGATCAGCAAGCAGCTCGGAT
CCCGGTGGAAAATGCTTACAGAAGACGAAAAACTGCCGTTCTTCCAGGAGGCAAAGTTTTTCGACCCCCC
CCCTTTTGTTTTTTTTTTTTGTCCCCCCCCCCCTACTTTTGGACGGTGTAATCACATGCTCTCAGCTATG
CTCACGATTTGGAACAGCAGTGATTGCAGCCCAGCCCTAGAACAACAGAATCTCTTCGCCTTGGAGAAAA
ACTCTTCCTTTCTTGCGACGGACAGCTCTCGCTCAAATTATCGCCGTGAAACAGGAGTAAATTATAAAGA
GCACAGCCAGAACCGGGTCAAGAGACCCATGAACGCGTTCTTCGTATGGTCTCGAGATCAGAGGCGCAAG
CTGGCTCTGGAGAATCCGAAAATGCGAAACTCAGAGATCAGCAAGCAGCTCGGATCCCGGTGGAAAATGC
TTACAGAAGACGAAAAACTGCCGTTCTTCCAGGAGGCACGGAGACTACAGGACGTGCACAGGGAGAAATA
CCCGGACTATAAGTATCGACCTCGGCGGAAGGTTAAGAAGGGTGGCAGTTTGCTGCCGGTAGACCCTTCT
TCAAAATTGTACAGCGAAATAAACGTGGAAGAGAGGTTGTACACCCTCACGTATAGGGACGGCTGTAGTA
AAGCCATATGCTCACGAGTGGAGCAGTGTTCACAGTCCAGAAACACAGCCAGCTCCCTGCTCCAAGGCGG
TTCACAGCAATTGGAGAAACCTGCGTTAATTGTCGGGTAA

>XM_004417134.1 PREDICTED: Odobenus rosmarus divergens sex determining region Y (SRY), mRNA
ATGTTCGGAGTATTGAACAGCGATGATCACCGTGCAGCGATACAACAACGAAATATCCTCGCCTTTGGAA
GAACCTCTTCTGAACTGTGGACGAACAATCCTACCTCAAATTATTGGTGTGAAACCAGAGGAAACGGTAG
GGACAGCGGCCAGAACCGCGTCAGACGGCCCATGAACGCATTCATGGTGTGGTCGCGTGATCAAAGGCGC
AAGGTGGCTCTGGAGAATCCCCAAATGCAAAACTCAGAGATCAGCAAGCAGCTGGGGTACCAGTGGAAAA
TGCTTACAGAAGCCGAAAAATGGCCATTCTTCGAGGAGGCACAGAGACTACAGGCCATGCACCGAGAGAA
ATACCCAGACTATAAATATCGACCTCGTCGGAAGGCCCTGCCACAGAAAAGTGATAAATTGCTACCTGCA
GCCTCCTCCTCCCTGCTATGCAGGCAGGTGCTCGTGGATAAGTGGTATCCCTTCACGTACAGGGACAGCT
GTAGTAGGGCTACACACTCACATATGGAGGACCAGTTAAGCTCCACACAACCCGTGAACATAGCCAACTC
GCTGCTGCAACAGGAGCACCACTACAGCTCTACAAGCCTCCGTGGCAGTCCAGAAACCTTGGCTACGCAT
CTGTCCGCTGACACTCCCTTTTACCCTAAGTAA


## Parte 2 - Alineamiento múltiple

¿Qué es el EMBL-EBI? 
  - Es el Instituto Bioinformático Europeo, que fomra parte del Laboratorio Europeo de Biología Molecular (organización de investigación), que proporciona de manera gratuita información biológica por medio de servicios y herramientas.
  
¿Cuántos tipos de alienamiento múltiple se pueden realizar en EMBL-EBI?
  - Existen 7 herramientas para generar alineamientos en esta página. *Clustal Omega, Kalign, MAFFT, MUSCLE, MView, T-Coffee, WebPRANK*

¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?
  - Ellos ofrecen el *MUSCLE*
  
¿Qué otros tipo de herramientas ofrece EMBL-EBI?
  - Nos ofrece varias herramientas, con las que podemos desde secuenciar proteínas, ensamblar, BLAST, busqueda de estructuras, *DNA back-translation*, etc. 
  
¿Cuál es el costo de abrir un gap?
  - El costo de abrir un gap es de 1.53.

¿Cuál es el costo de extender un gap?  
  - El costo de extenderlo es de 0.123
  
¿Cuál es la longitud total del alineamiento?
  - La longitud es de 1932
  
![imagen 1](https://raw.githubusercontent.com/dhermo/lab-2/master/Alineamiento.jpg)
Imagen 1: Alineamiento multi FASTA

![imagen 2](https://raw.githubusercontent.com/dhermo/lab-2/master/arbolfilogenetico.jpg)
Imagen 2: Árbol Filogenético

¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?
  - La especie más relacionada con el humano es la *Pan troglodyte* (chimpancé común)

¿Cuál es el más lejano?
  - La especie más lejana es *Pteropus alecto* (zorro volador negro, murciélago)
  
¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?
  - La especie *Equus przewalskii*(caballo salvaje mongol)
  
¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?
  - Si el costo de un gap aumentara los resultados serían los mismos o muy parecidos ya que al al no variar el costo de extender un gap, seguira siendo más conveniente abrir un solo gap antes que extenderlos. Si disminuye el costo, solo variarían los resultados cuando el costo de abrir un gap fuera menor que el de extenderlo. En ese caso se obtendrian más gaps que extenciones.
  
¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?  
  - De la misma manera, si el costo aumentara más que el costo de abrirlos predominaria el abrir gaps. Si disminuye del establecido no variara demasiado, mientras el de abrir un gap no sea inferior a este.
  
¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?
	prueba lo mismo pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento  
  - De acuerdo a lo explicado anteriormente la longitud del alineamiento no varia al variar los costos de 1.53 a 2.0, ni al disminuir la extención de estos.  
  
  
## Parte 3 - Diseño de partidores

>sry gene [Homo sapiens]
ATGCAATCATATGCTTCTGCTATGTTAAGCGTATTCAACAGCGATGATTACAGTCCAGCTGTGCAAGAGA
ATATTCCCGCTCTCCGGAGAAGCTCTTCCTTCCTTTGCACTGAAAGCTGTAACTCTAAGTATCAGTGTGA
AACGGGAGAAAACAGTAAAGGCAACGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATCGTGTGG
TCTCGCGATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAGAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACTGAAGCCGAAAAATGGCCATTCTTCCAGGAGGCACAGAAATTACA
GGCCATGCACAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCCGAAG
AATTGCAGTTTGCTTCCCGCAGATCCCGCTTCGGTACTCTGCAGCGAAGTGCAACTGGACAACAGGTTGT
ACAGGGATGACTGTACGAAAGCCACACACTCAAGAATGGAGCACCAGCTAGGCCACTTACCGCCCATCAA
CGCAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTGGACAAAGCTGTAG

>sry gene [Pan troglodytes]
ATGCAATCATATGCTTCTGCTATGTTAAGCGTATTCAACAGCGATGATTACAGTCCAGCTGTGCAACAGA
ATATTCCCGCTCTCCGGAGAAGCTCTTCCTTCCTTTGCACTGAAAGCTATAACTCTAAGTATCAGCGTGA
AACGGGAGAAAACAGTAAAGATAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCTTCGTGTGG
TCTCGCGATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAGAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACTGAAGCCGAAAAATGGCCATTCTTCCAGGAGGCACAGAAATTACA
GGCCATGCACAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAACATGCTGCCGAAG
AATTGCAGTTTGCTTCCCGCAGATCCCGCTTCGGTACTCTGCAGCGAAGTGCAACTGGACAACAGGTTGT
ACAGGGATGACTGTACGAAAGCCACACACTCAAGAATGGAGCACCAGCTAGGCCACTTACCGCCCATCAA
CGCAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTGGACAAAGCTGTAG

>sry gene [Macaca mulatta]
ATGCAATCATATGCTTCTGCCATGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGA
ATATTCCTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCAGTGTGA
AGCAGGAGAAAACAGTAAAGGCAGCGTCCAGGATAAAGTGAAGCGACCCATGAACGCATTCATTGTGTGG
TCTCGCGATCAGAAGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACA
GGCCATGCATAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAAC
AGTTGCAGTTTGCTTCCGGCAGATCCGTCTTCGGTACCCTGCAGAGAAGTGCAACTGGACAACAGGTTGT
ACAGGGATGACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAA
CACAGCCAGCTCACCGCAGCAACGGGACCGCTACAGCCACTCGACAAAGCTGTAG

>sry gene [Chlorocebus sabaeus]
ATGCAATCATATGCTTCTGCCAAGTTAAGCGTATTTAACACTGATGGTTACAGTCCAGCTGCGCAACAGA
ATATTCCTGCTCTCCGGAGAAGCTCTTCCTTCATTTGCACTGAAAGCTGTAGCTCTAAGTATCACTGTGA
AGCAGGAGAAAACAGTAAAGGCAGCGTCCAGGATAGAGTGAAGCGACCCATGAACGCATTCATTGTGTGG
TCTCGCGATCAGAGGCGCAAGATGGCTCTAGAGAATCCCAAAATGCGAAACTCAGAGATCAGCAAGCAGC
TGGGATACCAGTGGAAAATGCTTACCGAAGCCGATAAATGGCCATTCTTCCAGGAGGCACAGAAACTACA
GGCCATGCATAGAGAGAAATACCCGAATTATAAGTATCGACCTCGTCGGAAGGCGAAGATGCTGCAAAAC
AGTTGCAGTTTGCTTCCGGCAGATCCCTCTTCGGTACCCTGCAGAGAAGTGGAACTGGACAACAGGTTGT
ACAGGGATGACTGTACCAAAGCCACGCACTCAAGAATGCAGCACCAGTTAGGCCACTTACCGCCCATCAA
CACAGCCAGCTCACCGCAGCAATGGGACCGCTACAGCCACTCGACAAAGCTGTAG


![imagen 3](https://raw.githubusercontent.com/dhermo/lab-2/master/primers.jpg)
Imagen 3: Primers
