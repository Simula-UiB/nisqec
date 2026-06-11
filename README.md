# nisqec 

Table of our constructed stabilizer matrices for NISQ Error Correction Codes.
For CSS codes, "Hz" and "Hx" are binary parity-check matrices defining a CSS code.
Minimum distances are calculated using the classical algorithm of [b], [c].
	
## Table:

| n 	| k 	| d 	| Average row weight | Row weight range | Construction | PCM   | Paper(s) |
| :---: | :---: | :---: | :---: 			 | :---: 			| :---: 	   | :---: | :---:    |
| 144 	| 12	| 12 	| 8 				| 8 				| GB_PK		| [PCM](GB_PK/GB_144_12_w8_37)		| [2], [4] |
| 150 	| 62 	| ? 	| 10 				| 10 				| QT		| [PCM](QT/GenTanner_150_62_1460)	| [3] |
| 168 	| 76 	| 4 	| 12 				| 12 				| GB_MMM	| [PCM](GB_MMM/GB_168_76_w12_17)	| [3] |
| 168 	| 78 	| 3 	| 12 				| 12 				| GQT		| [PCM](GQT/GenTannerLoc_168_78_80) | [3] |
| 175 	| 71 	| ? 	| 10 				| 10 				| QT		| [PCM](QT/GenTanner_175_71_1456)	| [3] |
| 180 	| 26 	| 6 	| 6 				| 6 				| GQT		| [PCM](GQT/GenTannerSch_180_26_2173)| [1] |
| 180 	| 26 	| 7 	| 8 				| 8 				| GB_PK		| [PCM](GB_PK/GB_180_26_19)			| [1] |
| 180 	| 28 	| 5 	| 6 				| 6 				| QT		| [PCM](QT/GenTanner_180_28_14)		| [1] |
| 392 	| 32 	| 14 	| 12 				| 12 				| GB_PK		| [PCM](GB_PK/GB_392_32_w12_31)		| [2] |
| 392 	| 32 	| 12 	| 13 				| 12 - 16 			| QT		| [PCM](QT/GenTanner_392_32_1523)	| [2] |
| 392 	| 48 	| 12 	| 13 				| 12 - 16 			| QT		| [PCM](QT/GenTanner_392_48_1462)	| [2] |
| 392 	| 48 	| 13 	| 13 				| 13 				| GB_MMM	| [PCM](GB_MMM/GB_392_48_w13_7_d13) | [2] |
| 480 	| 40 	| 12 	| 12 				| 12	 			| GB_PK		| [PCM](GB_PK/GB_480_40_6)			| [1] |
| 500 	| 42 	| 4 	| 8.1 				| 6 - 12 			| QT		| [PCM](QT/GenTanner_500_42_1447)	| [1] |
| 500 	| 42 	| 6 	| 8.1 				| 6 - 12 			| GQT		| [PCM](GQT/GenTannerSch_500_42_710)| [1] |
| 500 	| 46 	| 6 	| 8.1 				| 6 - 12 			| QT		| [PCM](QT/GenTanner_500_46_874)	| [1] |
| 500	| 188 	| 4 	| 10 				| 10 				| QT		| [PCM](QT/GenTanner_500_188_2567)	| [3] |
| 504 	| 223 	| 4 	| 12 				| 12 				| GQT		| [PCM](GQT/GenTannerLoc_504_223_47)| [3] |
| 512 	| 174 	| 6 	| 8 				| 8 				| GB_MMM	| [PCM](GB_MMM/GB_512_174_w8_15_d6) | [2], [3] |
| 512 	| 174 	| 7 	| 9 				| 9 				| GB_MMM	| [PCM](GB_MMM/GB_512_174_w9_21_d7) | [2], [3] |
| 686 	| 28 	| 14 	| 13 				| 12 - 16 			| GQT		| [PCM](GQT/GenTannerSch_686_28_2017)| [1], [4] |
| 686 	| 34 	| 13 	| 13 				| 12 - 16 			| QT		| [PCM](QT/GenTanner_686_34_1306)	| [1], [4] |
| 688 	| 30 	| $\geq 19$ 	| 16 		| 16	 			| GB_PK		| [PCM](GB_PK/GB_688_30_w16_16)		| [1], [4] |


When citing, please refer to the paper introducing the code.

	
## References.

[a]. D. J. C. MacKay, G. Mitchison, and P. L. McFadden, “Sparse-graph
codes for quantum error correction,” IEEE Trans. Inf. Theory, vol. 50,
no. 10, pp. 2315–2330, Oct. 2004.

[b] E. Rosnes and Ø. Ytrehus, “An efficient algorithm to find all small-size
stopping sets of low-density parity-check matrices,” IEEE Trans. Inf.
Theory, vol. 55, no. 9, pp. 4167–4178, Sep. 2009.

[c] E. Rosnes, Ø. Ytrehus, M. A. Ambroze, and M. Tomlinson, “Addendum
to “An efficient algorithm to find all small-size stopping sets of low-
density parity-check matrices”, IEEE Trans. Inf. Theory, vol. 58, no. 1,
pp. 164–171, Jan. 2012.

[1] O. Å. Mostad, E. Rosnes and H.-Y. Lin, "Asymptotically Good Generalized Quantum Tanner Codes," in IEEE Journal on Selected Areas in Information Theory, vol. 6, pp. 367-382, 2025, doi: 10.1109/JSAIT.2025.3594310.

[2]. O. Å. Mostad, H.-Y. Lin, E. Rosnes, D.-S. Lee, and C.-Y. Lai, "Advancing Finite-Length Quantum Error Correction Using Generalized Bicycle Codes," 2025 13th International Symposium on Topics in Coding (ISTC), Los Angeles, CA, USA, 2025, pp. 1-5, doi: 10.1109/ISTC65386.2025.11154497, <a target="_blank" href="https://doi.org/10.48550/arXiv.2505.06157">arXiv:2505.06157v1 [quant-ph]</a>.

[3]. O. Å. Mostad, E. Rosnes, and H.-Y. Lin, "Improved Construction of Generalized Quantum Tanner Codes," 2025 13th International Symposium on Topics in Coding (ISTC), Los Angeles, CA, USA, 2025, pp. 1-5, doi: 10.1109/ISTC65386.2025.11154489.

[4]. O. Å. Mostad, E. Rosnes, and H.-Y. Lin, "Improved Decoding of Quantum Tanner Codes Using Generalized Check Nodes," March 2026, <a target="_blank" href="https://doi.org/10.48550/arXiv.2603.05486">arXiv:2603.05486 [quant-ph]</a>.
