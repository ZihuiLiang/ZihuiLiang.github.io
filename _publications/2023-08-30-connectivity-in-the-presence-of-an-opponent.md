---
title: "Connectivity in the Presence of an Opponent"
collection: publications
category: conferences
permalink: /publication/2023-08-30-connectivity-in-the-presence-of-an-opponent
excerpt: ''
date: 2023-08-30
venue: 'Annual European Symposium on Algorithms'
paperurl: 'https://drops.dagstuhl.de/storage/00lipics/lipics-vol274-esa2023/LIPIcs.ESA.2023.79/LIPIcs.ESA.2023.79.pdf'
citation: 'Zihui Liang, Bakh Khoussainov, Toru Takisaka, and Mingyu Xiao. Connectivity in the Presence of an Opponent. In 31st Annual European Symposium on Algorithms (ESA 2023). Leibniz International Proceedings in Informatics (LIPIcs), Volume 274, pp. 79:1-79:14, Schloss Dagstuhl – Leibniz-Zentrum fur Informatik (2023)'
---

The paper introduces two player connectivity games played on finite bipartite graphs. Algorithms that solve these connectivity games can be used as subroutines for solving Muller games. Muller games constitute a well established class of games in model checking and verification. In connectivity games, the objective of one of the players is to visit every node of the game graph infinitely often. The first contribution of this paper is our proof that solving connectivity games can be reduced to the incremental strongly connected component maintenance (ISCCM) problem, an important problem in graph algorithms and data structures. The second contribution is that we non-trivially adapt two known algorithms for the ISCCM problem to provide two efficient algorithms that solve the connectivity games problem. Finally, based on the techniques developed, we recast Horn’s polynomial time algorithm that solves explicitly given Muller games and provide the first correctness proof of the algorithm. Our algorithms are more efficient than that of Horn’s algorithm. Our solution for connectivity games is used as a subroutine in the algorithm.