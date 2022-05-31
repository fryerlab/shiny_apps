
1. The **add_color_columns.Rmd** script will add a color labeling column to a table of differentially expressed genes. It can loop through pvalues and logFC values to generate many combinations. This will make creating a volcano plot downstream much quicker.
2. **gene_options.txt** is a gene list. These are these genes that were used in the annotation file. They will be used to help users easily search for a gene in the shiny app.
3. The **bulk_gene_volcano.Rmd** script contains the components for creating the shiny app and plotting a volcano plot and box plot.
