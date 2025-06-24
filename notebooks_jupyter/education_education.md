# Report for relations: education_education

periods
1751-1810      5
1811-1850     25
1851-1880     57
1881-1910    123
1911-1940    127
1941-1970     84
dtype: int64



## Values for 1751-1810

Number of relationships for this period 5

Number of nodes: 7
Number of edges: 5

Beware: more than one big component !

Number of nodes for first component: 3
Number of edges for first component: 3



## Values for 1811-1850

Number of relationships for this period 25

Number of nodes: 17
Number of edges: 25

Beware: more than one big component !

Number of nodes for first component: 15
Number of edges for first component: 24



## Values for 1851-1880

Number of relationships for this period 57

Number of nodes: 40
Number of edges: 57

Beware: more than one big component !

Number of nodes for first component: 32
Number of edges for first component: 53

[('university', 32)]

Spearman's rank correlation of eidenvector and betweenness: 0.7333882292272687

Eigenvector
                                        label    mainType membersNumber
9              Humboldt-Universität zu Berlin  university            12
16     Ludwig-Maximilians-Universität München  university             6
5   Martin Luther University Halle-Wittenberg  university             6
8                       Heidelberg University  university            10
1                          Leipzig University  university            12
22                       University of Vienna  university             5
10                    Jagiellonian University  university             3
-----
Betweenness                                        label    mainType membersNumber
1                          Leipzig University  university            12
8                       Heidelberg University  university            10
9              Humboldt-Universität zu Berlin  university            12
5   Martin Luther University Halle-Wittenberg  university             6
22                       University of Vienna  university             5
16     Ludwig-Maximilians-Universität München  university             6
10                    Jagiellonian University  university             3

Number of communitites: 4
Number of nodes per community: [10, 8, 7, 7]



## Values for 1881-1910

Number of relationships for this period 123

Number of nodes: 55
Number of edges: 123

Just one big component with 51 nodes

Number of nodes for first component: 51
Number of edges for first component: 121

[('university', 51)]

Spearman's rank correlation of eidenvector and betweenness: 0.8416085692099676

Eigenvector
                                     label    mainType membersNumber
3                   University of Freiburg  university            10
1           Humboldt-Universität zu Berlin  university            22
2                  University of Göttingen  university            21
21  Ludwig-Maximilians-Universität München  university            17
17                   Heidelberg University  university            14
18                   University of Marburg  university             9
0                       Harvard University  university            21
-----
Betweenness                                                label    mainType  \
1                      Humboldt-Universität zu Berlin  university   
0                                  Harvard University  university   
2                             University of Göttingen  university   
20  Friedrich-Alexander-Universität Erlangen-Nürnberg  university   
21             Ludwig-Maximilians-Universität München  university   
9                                 Columbia University  university   
3                              University of Freiburg  university   

   membersNumber  
1             22  
0             21  
2             21  
20             7  
21            17  
9             15  
3             10  

Number of communitites: 5
Number of nodes per community: [18, 12, 9, 7, 5]

Communities: 


Community 0
Betweenness|    | label                | mainType   |   membersNumber |
|---:|:---------------------|:-----------|----------------:|
|  0 | Harvard University   | university |              21 |
|  9 | Columbia University  | university |              15 |
| 12 | Cornell University   | university |               5 |
|  4 | Princeton University | university |               9 |
| 16 | Merton College       | university |               2 |
-----
Eigenvector|    | label                                  | mainType   |   membersNumber |
|---:|:---------------------------------------|:-----------|----------------:|
|  0 | Harvard University                     | university |              21 |
|  9 | Columbia University                    | university |              15 |
| 12 | Cornell University                     | university |               5 |
| 15 | Tufts University School of Engineering | university |               1 |
| 13 | Tufts University                       | university |               1 |

Community 1
Betweenness|    | label                              | mainType   |   membersNumber |
|---:|:-----------------------------------|:-----------|----------------:|
|  1 | Humboldt-Universität zu Berlin     | university |              22 |
|  3 | University of Freiburg             | university |              10 |
| 18 | University of Marburg              | university |               9 |
| 24 | Friedrich Schiller University Jena | university |               7 |
| 17 | Heidelberg University              | university |              14 |
-----
Eigenvector|    | label                          | mainType   |   membersNumber |
|---:|:-------------------------------|:-----------|----------------:|
|  3 | University of Freiburg         | university |              10 |
|  1 | Humboldt-Universität zu Berlin | university |              22 |
| 17 | Heidelberg University          | university |              14 |
| 18 | University of Marburg          | university |               9 |
| 28 | University of Bern             | university |               1 |

Community 2
Betweenness|    | label                                  | mainType   |   membersNumber |
|---:|:---------------------------------------|:-----------|----------------:|
|  2 | University of Göttingen                | university |              21 |
| 21 | Ludwig-Maximilians-Universität München | university |              17 |
| 31 | University of Greifswald               | university |               3 |
| 26 | Frederick William University Berlin    | university |               3 |
| 33 | Lviv University                        | university |               4 |
-----
Eigenvector|    | label                                  | mainType   |   membersNumber |
|---:|:---------------------------------------|:-----------|----------------:|
|  2 | University of Göttingen                | university |              21 |
| 21 | Ludwig-Maximilians-Universität München | university |              17 |
| 26 | Frederick William University Berlin    | university |               3 |
| 31 | University of Greifswald               | university |               3 |
| 32 | University of Bucharest                | university |               5 |

Community 3
Betweenness|    | label                                             | mainType   |   membersNumber |
|---:|:--------------------------------------------------|:-----------|----------------:|
| 20 | Friedrich-Alexander-Universität Erlangen-Nürnberg | university |               7 |
| 29 | University of Paris                               | university |               6 |
| 23 | University of Bonn                                | university |               6 |
| 34 | Freie Universität Berlin                          | university |               3 |
| 35 | Ulm University                                    | university |               1 |
-----
Eigenvector|    | label                                             | mainType   |   membersNumber |
|---:|:--------------------------------------------------|:-----------|----------------:|
| 20 | Friedrich-Alexander-Universität Erlangen-Nürnberg | university |               7 |
| 23 | University of Bonn                                | university |               6 |
| 29 | University of Paris                               | university |               6 |
| 34 | Freie Universität Berlin                          | university |               3 |
| 35 | Ulm University                                    | university |               1 |

Community 4
Betweenness|    | label                             | mainType   |   membersNumber |
|---:|:----------------------------------|:-----------|----------------:|
|  7 | University of Cambridge           | university |               9 |
| 27 | Technische Universität Berlin     | university |               3 |
| 47 | Trinity College                   | university |               3 |
| 48 | Victoria University of Manchester | university |               2 |
| 49 | King's College                    | university |               3 |
-----
Eigenvector|    | label                             | mainType   |   membersNumber |
|---:|:----------------------------------|:-----------|----------------:|
|  7 | University of Cambridge           | university |               9 |
| 27 | Technische Universität Berlin     | university |               3 |
| 47 | Trinity College                   | university |               3 |
| 48 | Victoria University of Manchester | university |               2 |
| 49 | King's College                    | university |               3 |



## Values for 1911-1940

Number of relationships for this period 127

Number of nodes: 112
Number of edges: 127

Beware: more than one big component !

Number of nodes for first component: 8
Number of edges for first component: 8



## Values for 1941-1970

Number of relationships for this period 84

Number of nodes: 79
Number of edges: 84

Beware: more than one big component !

Number of nodes for first component: 6
Number of edges for first component: 5
