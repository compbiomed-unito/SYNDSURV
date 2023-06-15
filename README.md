# Unfederated-Learning


## Datasets
To validate our framework we considered four publicly available survival datasets, commonly used to assess the performance of the survival models: the Assay of Serum Free Light Chain [1] (FLCHAIN), the Molecular Taxonomy of Breast Cancer Interna- tional Consortium [2] (METABRIC), the Study to Understand Prognoses Preferences Outcomes and Risks of Treatment [3] (SUPPORT) and the Rotterdam tumor bank and German Breast Cancer Study Group [4], [5] (GBSG+Rotterdam).

FLChain and METABRIC datasets were preprocessed according to [6], while for GBSG+Rotterdam the same preprocessing schema of [7] was applied, with the only difference that data from the two studies were finally merged together to create a single dataset. As regards SUPPORT, we used the same procedure of [8] for data cleaning and imputation, followed by a final feature selection to decrease the data dimensionality.


## References
[1] T. Therneau, et al., A package for survival analysis in s, R package version 2 (7) (2015).

[2] C. Curtis, S. P. Shah, S.-F. Chin, G. Turashvili, O. M. Rueda, M. J. Dunning, D. Speed, A. G. Lynch, S. Samarajiwa, Y. Yuan, et al., The genomic and tran- scriptomic architecture of 2,000 breast tumours reveals novel subgroups, Nature 486 (7403) (2012) 346–352.

[3] W. A. Knaus, F. E. Harrell, J. Lynn, L. Goldman, R. S. Phillips, A. F. Connors, N. V. Dawson, W. J. Fulkerson, R. M. Califf, N. Desbiens, et al., The support prognostic model: Objective estimates of survival for seriously ill hospitalized adults, Annals of internal medicine 122 (3) (1995) 191–203.

[4] J. A. Foekens, H. A. Peters, M. P. Look, H. Portengen, M. Schmitt, M. D. Kramer, N. Bru ̈nner, F. Ja ̈nicke, M. E. M.-v. Gelder, S. C. Henzen-Logmans, et al., The urokinase system of plasminogen activation and prognosis in 2780 breast cancer patients, Cancer research 60 (3) (2000) 636–643.

[5] M. Schumacher, G. Bastert, H. Bojar, K. Hu ̈bner, M. Olschewski, W. Sauerbrei, C. Schmoor, C. Beyerle, R. Neumann, H. Rauschecker, Randomized 2 x 2 trial evalu- ating hormonal treatment and the duration of chemotherapy in node-positive breast cancer patients. german breast cancer study group., Journal of Clinical Oncology 12 (10) (1994) 2086–2093.

[6] H. Kvamme, Ø. Borgan, I. Scheel, Time-to-event prediction with neural networks and cox regression, arXiv preprint arXiv:1907.00825 (2019).

[7] P. Royston, D. G. Altman, External validation of a cox prognostic model: principles and methods, BMC medical research methodology 13 (1) (2013) 1–15.

[8] P. Chapfuwa, C. Li, N. Mehta, L. Carin, R. Henao, Survival cluster analysis, in: Proceedings of the ACM Conference on Health, Inference, and Learning, 2020, pp. 60–68.
