introduction.html: introduction.Rmd ../my.css
	Rscript -e 'library("rmarkdown"); render("introduction.Rmd")'

introduction-small.pdf: introduction.pdf
	qpdf --optimize-images introduction.pdf introduction-small.pdf
