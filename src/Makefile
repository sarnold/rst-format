# document build target (see corresponding .rst source file)
RESUME ?= sarnold_main

# just one pdf doc target for now
DOCS = $(RESUME).pdf

# figure generation engine; can use other layouts/drivers
DOT = dot

# input files
DOTSRC  := $(wildcard images/*.dot)
#FIGSRC	:= $(wildcard images/*.svg)
#RSTSRC	:= $(wildcard *.rst)
RSTSRC	:= $(RESUME).rst
INCSRC  := foss_cs.rst work.rst projects_cs.rst pubs_interests.rst appendix-A.rst appendix-B.rst

# set this to the output image format to include in the doc target
FIGTYPE = svg

# generated input files
FIGS := $(DOTSRC:.dot=.$(FIGTYPE))

# input files for DOC target
#SOURCES_MK	:= $(FIGS) $(RSTSRC)
SOURCES_MK	:= $(RSTSRC)
# stuff to clean
GENFILES	:= $(FIGS)

DOTFLAGS = -T$(FIGTYPE)
RSTFLAGS = -s styles/pdf-resume.style
DOT_OFLAG = -o
PDF_OFLAG = -o

# reset file suffixes
.SUFFIXES:
.SUFFIXES: .pdf .dot .rst .$(FIGTYPE)

.NOTPARALLEL: $(FIGS) $(DOCS)

# build the figures
images/%.$(FIGTYPE) : images/%.dot
	$(DOT) $< $(DOT_OFLAG) $@ $(DOTFLAGS)

# build the pdf output
$(DOCS): $(SOURCES_MK) $(INCSRC)
	rst2pdf $< $(RSTFLAGS) $(PDF_OFLAG) $@
	cp $(DOCS) ../prebuilt

CLEAN  += $(GENFILES) $(DOCS)

clean :
	rm -rf $(CLEAN)
