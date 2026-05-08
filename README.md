# Online-to-Local

### Github to local

```bash
cd Desktop
git clone < My GitHub repository Link>
```

### put the picture into the directory

```bash
cd PB_MB_bulkseq_analysis
mkdir -p results/figures
cp ~/Desktop/TAPS_score_boxplot_PB_vs_MB_nonWNT_nonSHH.png results/figures/
cp ~/Desktop/TAPS_gene_heatmap_ordered_by_score.png results/figures/
```

### README insert picture

```test
![TAPS score boxplot](results/figures/TAPS_score_boxplot_PB_vs_MB_nonWNT_nonSHH.png)

![TAPS gene heatmap](results/figures/TAPS_gene_heatmap_ordered_by_score.png)
```

### terminal

```test
git status
git add README.md results/figures/
git commit -m "Add TAPS score figures"
git push
```

### Online renew README to local


