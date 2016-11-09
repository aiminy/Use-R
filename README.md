# Use-R

R CMD INSTALL -l /projects/scratch/bbc/R/src/R-3.3.0/builddir/library/ GOSJ_0.1.0_R_x86_64-pc-linux-gnu.tar.gz

Re4 is a list

 venn.plot <- venn.diagram(
    x = Re4[c(2,3,4)],
    filename = paste0(venn_output,"DE_gene_overlap_rMAT_SE.tiff"),
    col = "black",
    lty = "dotted",
    lwd = 2,
    fill = c("red", "orange", "blue"),
    alpha = 0.50,
    label.col = c(rep("white",7)),
    cex = 1,
    fontfamily = "serif",
    fontface = "bold",
    cat.col = c("red", "orange", "blue"),
    cat.cex = 0.8,
    cat.fontfamily = "serif"
  )


<!-- ![Bias from gene structure](/home/aiminyan/GOSJ/Figure/BiasFromGeneStructure.png) -->
![Bias from gene structure](/home/aiminyan/GOSJ/Figure/BiasFromGeneStructure.png)

If using command line:

R CMD build PathwaySplice

then 
  
  R CMD check PathwaySplice_0.1.0.tar.gz

