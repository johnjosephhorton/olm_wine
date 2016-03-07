# Notes

This is the associated code for my paper  ``Online Labor Markets`` published in 2010 in ``Internet and Network Economics.''
The paper is available at:

1. My website: [http://www.john-joseph-horton.com/papers/online_labor_markets.pdf](http://www.john-joseph-horton.com/papers/online_labor_markets.pdf)
1. SSRN: [http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1689743](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1689743)
1. ACM Digital Library: [http://dl.acm.org/citation.cfm?id=1940226](http://dl.acm.org/citation.cfm?id=1940226)

## Citation Info

```
@incollection{horton2010online,
  title={Online labor markets},
  author={Horton, John J},
  booktitle={Internet and Network Economics},
  pages={515--522},
  year={2010},
  publisher={Springer Berlin Heidelberg}
}


```
## Replication

This paper has no empirical component, so ``replication'' is a bit of misnomer.
However, I thought some people might like to see the sources, so here it is. 
The repository is set up to make it transparent how the final PDF is constructed from the raw sources. 
To replicate, you will need a Linux or Mac OX machine that has the following installed:

1. `R`
1. `pdflatex`
1. `make`
1. `gpg`
1. `curl`
1. `gs` (GhostScript)


####Download the repository from github
```
 git clone git@github.com:johnjosephhorton/olm_wine.git 
```

#### Build the PDF
From `/olm_wine`, run: 
```
cd writeup
make olm_wine.pdf
```

If you run into any trouble replicating, please contact me at ``john.joseph.horton@gmail.com``. 
