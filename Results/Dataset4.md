These are the results for Dataset 4, containing a few larger instances with more than a billion edges originally.

|                              |    GNN & LS   |           |   QUICK & LS  |           |       LS      |          |
|------------------------------|:-------------:|:---------:|:-------------:|:---------:|:-------------:|:--------:|
| Graph                        | Cost          | Time      | Cost          | Time      | Cost          | Time     |
| webbase-2001 | **3,440,309,297** | 311.03                   | 3,442,765,890            | 176.72                   | 3,539,284,688            | 62.68                    |
| it-2004      | **1,438,951,442** | 749.59                   | 1,439,091,400            | 490.23                   | 1,480,088,254            | 76.98                    |
| GAP-twitter  | **1,160,408,463** | 724.04                   | 1,160,512,688            | 712.48                   | 1,201,023,583            | 30.18                    |
| twitter7     | **1,160,187,362** | 763.95                   | 1,160,291,460            | 680.71                   | 1,200,789,078            | 29.82                    |
| GAP-web      | **1,861,729,481** | 2,562.73                 | 1,883,467,468            | 1,724.99                 | 1,932,504,652            | 227.39                   |
| sk-2005      | **1,861,502,940** | 2,797.92                 | 1,882,779,425            | 1,788.75                 | 1,932,262,816            | 221.15                   |

| Graph               | \|V\|  | \|E\| | \|V\| after reduction  |
|---------------------|------|-----|----------------------|
| webbase-2001 | 118,142,155               | 854,809,760               | 4,936,598                                 |
| it-2004      | 41,291,594                | 1,027,474,946             | 8,826,771                                 |
| GAP-twitter  | 61,578,415                | 1,202,513,046             | 164,512                                   |
| twitter7     | 41,652,230                | 1,202,513,046             | 165,489                                   |
| GAP-web      | 50,636,151                | 1,810,063,329             | 16,803,173                                |
| sk-2005      | 50,636,154                | 1,810,063,329             | 16,756,003                                |
