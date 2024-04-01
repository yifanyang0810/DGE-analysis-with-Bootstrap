# DGE-analysis-with-Bootstrap

The Bootstrap-enhanced DGE analysis is a specialized statistical method developed for Differential Gene Expression (DGE) analysis. It aims to address the limitations inherent in existing DGE tools. Specifically, parametric methods like edgeR and DESeq2 perform well with small sample sizes but tend to produce higher false discovery rates as the sample size grows (n>=8). Conversely, non-parametric methods like the Wilcoxon rank-sum test lack power when the sample size is small (n<8).

To address these limitations, the Bootstrap-enhanced DGE analysis integrates Bootstrap methodology. By doing so, it successfully reconciles the strengths and weaknesses of both parametric and non-parametric approaches. As a result, this new algorithm consistently delivers comparable or even superior results across all sample size scenarios (n>2), effectively overcoming the challenges faced by existing DGE tools.
