making-a-plot.html: making-a-plot.Rmd ../my.css
	Rscript -e 'library("rmarkdown"); render("making-a-plot.Rmd")'

making-a-plot-small.pdf: making-a-plot.pdf
	qpdf --optimize-images making-a-plot.pdf making-a-plot-small.pdf
