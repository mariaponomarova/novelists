# Report for relations: employment_employment

periods
1751-1810      7
1811-1850     41
1851-1880     90
1881-1910    200
1911-1940    377
1941-1970    234
dtype: int64



## Values for 1751-1810

Number of relationships for this period 7

Number of nodes: 6
Number of edges: 7

Number of nodes for first component: 6
Number of edges for first component: 7



## Values for 1811-1850

Number of relationships for this period 41

Number of nodes: 26
Number of edges: 41

Beware: more than one big component !

Number of nodes for first component: 2
Number of edges for first component: 1



## Values for 1851-1880

Number of relationships for this period 90

Number of nodes: 51
Number of edges: 90

Beware: more than one big component !

Number of nodes for first component: 37
Number of edges for first component: 77

[('university', 37)]

Spearman's rank correlation of eidenvector and betweenness: 0.3097552750495652

Eigenvector
                             label    mainType membersNumber
13  Humboldt-Universität zu Berlin  university            12
26        University of Gothenburg  university             1
25            University of Oxford  university             1
30               All Souls College  university             1
28                 Yale University  university             1
21           University of Hamburg  university             2
27             Columbia University  university             1
-----
Betweenness                                        label    mainType membersNumber
1                          Harvard University  university            11
13             Humboldt-Universität zu Berlin  university            12
6                      University of Freiburg  university             4
12                      Heidelberg University  university            10
14                    University of Göttingen  university             3
24  Martin Luther University Halle-Wittenberg  university             6
0                       University of Chicago  university             2

Number of communitites: 4
Number of nodes per community: [11, 11, 9, 6]



## Values for 1881-1910

Number of relationships for this period 200

Number of nodes: 99
Number of edges: 200

Just one big component with 82 nodes

Number of nodes for first component: 82
Number of edges for first component: 187

[('university', 79), ('research', 2), ('publisher', 1)]

Spearman's rank correlation of eidenvector and betweenness: 0.7189718237204596

Eigenvector
                             label    mainType membersNumber
1            University of Chicago  university             9
2             Princeton University  university             9
3              Columbia University  university            15
20            University of Vienna  university            18
9               Harvard University  university            21
25        University of Notre Dame  university             3
18  Humboldt-Universität zu Berlin  university            22
-----
Betweenness                                               label    mainType membersNumber
1                              University of Chicago  university             9
18                    Humboldt-Universität zu Berlin  university            22
20                              University of Vienna  university            18
2                               Princeton University  university             9
22  London School of Economics and Political Science  university             3
49                                Leipzig University  university            13
32                       Goethe University Frankfurt  university             8

Number of communitites: 5
Number of nodes per community: [24, 18, 16, 14, 10]

Communities: 


Community 0
Betweenness|    | label                    | mainType   |   membersNumber |
|---:|:-------------------------|:-----------|----------------:|
| 20 | University of Vienna     | university |              18 |
|  9 | Harvard University       | university |              21 |
| 10 | The New School           | university |               4 |
| 36 | University of Warsaw     | university |               6 |
| 25 | University of Notre Dame | university |               3 |
-----
Eigenvector|    | label                    | mainType   |   membersNumber |
|---:|:-------------------------|:-----------|----------------:|
| 20 | University of Vienna     | university |              18 |
|  9 | Harvard University       | university |              21 |
| 25 | University of Notre Dame | university |               3 |
| 10 | The New School           | university |               4 |
| 40 | University of Amsterdam  | university |               2 |

Community 1
Betweenness|    | label                              | mainType   |   membersNumber |
|---:|:-----------------------------------|:-----------|----------------:|
| 49 | Leipzig University                 | university |              13 |
| 32 | Goethe University Frankfurt        | university |               8 |
| 60 | Kiel University                    | university |               6 |
|  6 | Heidelberg University              | university |              14 |
| 16 | Friedrich Schiller University Jena | university |               7 |
-----
Eigenvector|    | label                       | mainType   |   membersNumber |
|---:|:----------------------------|:-----------|----------------:|
| 32 | Goethe University Frankfurt | university |               8 |
| 60 | Kiel University             | university |               6 |
| 49 | Leipzig University          | university |              13 |
| 62 | University of Rostock       | university |               2 |
|  6 | Heidelberg University       | university |              14 |

Community 2
Betweenness|    | label                                  | mainType   |   membersNumber |
|---:|:---------------------------------------|:-----------|----------------:|
|  1 | University of Chicago                  | university |               9 |
|  2 | Princeton University                   | university |               9 |
|  4 | Ludwig-Maximilians-Universität München | university |              17 |
| 29 | University of Cambridge                | university |               9 |
|  3 | Columbia University                    | university |              15 |
-----
Eigenvector|    | label                                  | mainType   |   membersNumber |
|---:|:---------------------------------------|:-----------|----------------:|
|  1 | University of Chicago                  | university |               9 |
|  2 | Princeton University                   | university |               9 |
|  3 | Columbia University                    | university |              15 |
| 30 | Yale University                        | university |               9 |
|  4 | Ludwig-Maximilians-Universität München | university |              17 |

Community 3
Betweenness|    | label                          | mainType   |   membersNumber |
|---:|:-------------------------------|:-----------|----------------:|
| 18 | Humboldt-Universität zu Berlin | university |              22 |
| 14 | Institute for Advanced Study   | research   |               3 |
| 55 | University of Cologne          | university |               3 |
| 50 | University of Marburg          | university |               9 |
| 13 | University of Göttingen        | university |              21 |
-----
Eigenvector|    | label                                 | mainType   |   membersNumber |
|---:|:--------------------------------------|:-----------|----------------:|
| 18 | Humboldt-Universität zu Berlin        | university |              22 |
| 14 | Institute for Advanced Study          | research   |               3 |
| 23 | University of California, Los Angeles | university |               2 |
| 28 | Charles University                    | university |               2 |
| 13 | University of Göttingen               | university |              21 |

Community 4
Betweenness|    | label                                            | mainType   |   membersNumber |
|---:|:-------------------------------------------------|:-----------|----------------:|
| 22 | London School of Economics and Political Science | university |               3 |
| 19 | University of Freiburg                           | university |              10 |
| 27 | University of Salzburg                           | university |               1 |
| 31 | New York University                              | university |               1 |
| 33 | University of Leicester                          | university |               1 |
-----
Eigenvector|    | label                                            | mainType   |   membersNumber |
|---:|:-------------------------------------------------|:-----------|----------------:|
| 22 | London School of Economics and Political Science | university |               3 |
| 19 | University of Freiburg                           | university |              10 |
| 27 | University of Salzburg                           | university |               1 |
| 31 | New York University                              | university |               1 |
| 33 | University of Leicester                          | university |               1 |



## Values for 1911-1940

Number of relationships for this period 377

Number of nodes: 176
Number of edges: 377

Beware: more than one big component !

Number of nodes for first component: 101
Number of edges for first component: 269

[('university', 97), ('publisher', 3), ('research', 1)]

Spearman's rank correlation of eidenvector and betweenness: 0.5894427860331801

Eigenvector
                                 label    mainType membersNumber
13                  Harvard University  university            42
1                 Princeton University  university            27
37                 Columbia University  university            14
22  University of California, Berkeley  university            16
34               University of Chicago  university            15
38                 New York University  university             6
35                University of Oxford  university             7
-----
Betweenness                                      label    mainType membersNumber
32  National Center for Scientific Research   publisher             6
13                       Harvard University  university            42
22       University of California, Berkeley  university            16
39            University of Texas at Austin  university             3
36                      Stanford University  university            10
1                      Princeton University  university            27
59         University of California, Irvine  university             4

Number of communitites: 7
Number of nodes per community: [27, 25, 19, 13, 9, 6, 2]

Communities: 


Community 0
Betweenness|    | label                              | mainType   |   membersNumber |
|---:|:-----------------------------------|:-----------|----------------:|
| 13 | Harvard University                 | university |              42 |
| 22 | University of California, Berkeley | university |              16 |
| 39 | University of Texas at Austin      | university |               3 |
| 37 | Columbia University                | university |              14 |
| 35 | University of Oxford               | university |               7 |
-----
Eigenvector|    | label                              | mainType   |   membersNumber |
|---:|:-----------------------------------|:-----------|----------------:|
| 13 | Harvard University                 | university |              42 |
| 37 | Columbia University                | university |              14 |
| 22 | University of California, Berkeley | university |              16 |
| 34 | University of Chicago              | university |              15 |
| 38 | New York University                | university |               6 |

Community 1
Betweenness|    | label                                              | mainType   |   membersNumber |
|---:|:---------------------------------------------------|:-----------|----------------:|
| 32 | National Center for Scientific Research            | publisher  |               6 |
| 59 | University of California, Irvine                   | university |               4 |
| 30 | Paris Nanterre University                          | university |              18 |
| 93 | School for Advanced Studies in the Social Sciences | university |               8 |
| 19 | Paris-Sorbonne University - Paris IV               | university |               6 |
-----
Eigenvector|    | label                                              | mainType   |   membersNumber |
|---:|:---------------------------------------------------|:-----------|----------------:|
| 32 | National Center for Scientific Research            | publisher  |               6 |
| 24 | Tel Aviv University                                | university |               2 |
| 93 | School for Advanced Studies in the Social Sciences | university |               8 |
| 88 | University of Kassel                               | university |               2 |
| 59 | University of California, Irvine                   | university |               4 |

Community 2
Betweenness|    | label                                 | mainType   |   membersNumber |
|---:|:--------------------------------------|:-----------|----------------:|
| 36 | Stanford University                   | university |              10 |
|  1 | Princeton University                  | university |              27 |
|  3 | City University of New York           | university |               4 |
|  2 | The Rockefeller University            | university |               3 |
| 28 | Massachusetts Institute of Technology | university |               8 |
-----
Eigenvector|    | label                                 | mainType   |   membersNumber |
|---:|:--------------------------------------|:-----------|----------------:|
|  1 | Princeton University                  | university |              27 |
| 28 | Massachusetts Institute of Technology | university |               8 |
|  2 | The Rockefeller University            | university |               3 |
| 36 | Stanford University                   | university |              10 |
|  3 | City University of New York           | university |               4 |

Community 3
Betweenness|    | label                    | mainType   |   membersNumber |
|---:|:-------------------------|:-----------|----------------:|
| 66 | Wayne State University   | university |               4 |
|  9 | University of Notre Dame | university |               4 |
| 65 | University of Rochester  | university |               2 |
|  8 | Duke University          | university |               3 |
| 71 | Brown University         | university |               4 |
-----
Eigenvector|    | label                    | mainType   |   membersNumber |
|---:|:-------------------------|:-----------|----------------:|
|  9 | University of Notre Dame | university |               4 |
| 80 | University of Malawi     | university |               1 |
|  8 | Duke University          | university |               3 |
| 66 | Wayne State University   | university |               4 |
| 71 | Brown University         | university |               4 |

Community 4
Betweenness|    | label                      | mainType   |   membersNumber |
|---:|:---------------------------|:-----------|----------------:|
| 46 | University of Warsaw       | university |              17 |
| 52 | University of Pennsylvania | university |               4 |
| 45 | University of Łódź         | university |               2 |
| 63 | University of Gdańsk       | university |               1 |
| 64 | Polish Academy of Sciences | publisher  |               2 |
-----
Eigenvector|    | label                         | mainType   |   membersNumber |
|---:|:------------------------------|:-----------|----------------:|
| 46 | University of Warsaw          | university |              17 |
| 45 | University of Łódź            | university |               2 |
| 52 | University of Pennsylvania    | university |               4 |
| 47 | University of Utah            | university |               1 |
| 53 | Pennsylvania State University | university |               1 |



## Values for 1941-1970

Number of relationships for this period 234

Number of nodes: 122
Number of edges: 234

Beware: more than one big component !

Number of nodes for first component: 77
Number of edges for first component: 172

[('university', 73), ('publisher', 2), ('research', 2)]

Spearman's rank correlation of eidenvector and betweenness: 0.5188757540751864

Eigenvector
                                    label    mainType membersNumber
24  University of California, Los Angeles  university             5
56                    Stanford University  university            10
7                  University of Michigan  university             5
8                 University of Minnesota  university             3
2                         Yale University  university             8
9                     Columbia University  university             5
4                   University of Vermont  university             2
-----
Betweenness                                      label    mainType membersNumber
40                    University of Chicago  university             7
9                       Columbia University  university             5
2                           Yale University  university             8
36  University of Paris 1 Pantheon-Sorbonne  university            19
5        University of California, Berkeley  university             9
32                 Paris Diderot University  university             9
7                    University of Michigan  university             5

Number of communitites: 7
Number of nodes per community: [17, 16, 14, 13, 8, 5, 4]

Communities: 


Community 0
Betweenness|    | label                                              | mainType   |   membersNumber |
|---:|:---------------------------------------------------|:-----------|----------------:|
| 32 | Paris Diderot University                           | university |               9 |
| 41 | Paris Nanterre University                          | university |              14 |
| 43 | University of Poitiers                             | university |               4 |
| 17 | Paris-Sorbonne University - Paris IV               | university |              15 |
| 33 | School for Advanced Studies in the Social Sciences | university |               6 |
-----
Eigenvector|    | label                                   | mainType   |   membersNumber |
|---:|:----------------------------------------|:-----------|----------------:|
| 32 | Paris Diderot University                | university |               9 |
| 17 | Paris-Sorbonne University - Paris IV    | university |              15 |
| 43 | University of Poitiers                  | university |               4 |
| 41 | Paris Nanterre University               | university |              14 |
| 16 | National Center for Scientific Research | publisher  |               9 |

Community 1
Betweenness|    | label                   | mainType   |   membersNumber |
|---:|:------------------------|:-----------|----------------:|
|  2 | Yale University         | university |               8 |
|  6 | Princeton University    | university |              16 |
|  8 | University of Minnesota | university |               3 |
| 20 | Tel Aviv University     | university |               5 |
| 18 | Western University      | university |               4 |
-----
Eigenvector|    | label                   | mainType   |   membersNumber |
|---:|:------------------------|:-----------|----------------:|
|  8 | University of Minnesota | university |               3 |
|  2 | Yale University         | university |               8 |
|  6 | Princeton University    | university |              16 |
| 18 | Western University      | university |               4 |
| 20 | Tel Aviv University     | university |               5 |

Community 2
Betweenness|    | label                                 | mainType   |   membersNumber |
|---:|:--------------------------------------|:-----------|----------------:|
| 40 | University of Chicago                 | university |               7 |
|  9 | Columbia University                   | university |               5 |
|  7 | University of Michigan                | university |               5 |
| 24 | University of California, Los Angeles | university |               5 |
| 42 | University of Pittsburgh              | university |              11 |
-----
Eigenvector|    | label                                 | mainType   |   membersNumber |
|---:|:--------------------------------------|:-----------|----------------:|
| 24 | University of California, Los Angeles | university |               5 |
|  7 | University of Michigan                | university |               5 |
|  9 | Columbia University                   | university |               5 |
| 42 | University of Pittsburgh              | university |              11 |
| 40 | University of Chicago                 | university |               7 |

Community 3
Betweenness|    | label                                   | mainType   |   membersNumber |
|---:|:----------------------------------------|:-----------|----------------:|
| 36 | University of Paris 1 Pantheon-Sorbonne | university |              19 |
|  5 | University of California, Berkeley      | university |               9 |
|  4 | University of Vermont                   | university |               2 |
| 10 | University of Texas at Austin           | university |               2 |
| 52 | Paul-Valéry-Montpellier University      | university |               4 |
-----
Eigenvector|    | label                              | mainType   |   membersNumber |
|---:|:-----------------------------------|:-----------|----------------:|
|  4 | University of Vermont              | university |               2 |
| 10 | University of Texas at Austin      | university |               2 |
|  5 | University of California, Berkeley | university |               9 |
| 59 | Carnegie Mellon University         | university |               2 |
| 11 | University of South Florida        | university |               1 |

Community 4
Betweenness|    | label                                            | mainType   |   membersNumber |
|---:|:-------------------------------------------------|:-----------|----------------:|
| 56 | Stanford University                              | university |              10 |
| 12 | University of California, San Diego              | university |               4 |
| 19 | London School of Economics and Political Science | university |               4 |
| 71 | Indiana University                               | university |               3 |
| 58 | University of Wisconsin–Madison                  | university |               2 |
-----
Eigenvector|    | label                                            | mainType   |   membersNumber |
|---:|:-------------------------------------------------|:-----------|----------------:|
| 56 | Stanford University                              | university |              10 |
| 12 | University of California, San Diego              | university |               4 |
| 71 | Indiana University                               | university |               3 |
| 19 | London School of Economics and Political Science | university |               4 |
| 58 | University of Wisconsin–Madison                  | university |               2 |
