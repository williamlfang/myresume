BUILD_ENGINE:= xelatex
PDF_CMD:= evince

all: 方莲-简历

方莲-简历: 方莲-简历.tex
	$(BUILD_ENGINE) $<

display: 方莲-简历.pdf
	$(PDF_CMD) $< &
