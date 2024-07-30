BASENAME = intiial-idea

all: pdf

pdf::
	latexmk --pdf ${BASENAME}

ps::
	latexmk --ps ${BASENAME}

clean::
	latexmk -c ${BASENAME}
	#rm -f ${BASENAME}.pdf
	#rm -f ${BASENAME}.bbl
	#rm -f ${BASENAME}.cb*
	rm -f ${BASENAME}.spl
	rm -f ${BASENAME}.run.xml
	rm -f sections/*.aux
	#rm -f ${BASENAME}.synctex.gz

fullclean::
	latexmk -c ${BASENAME}
	rm -f ${BASENAME}.run.xml
	rm -f ${BASENAME}.spl
	rm -f ${BASENAME}.bbl
	rm -f ${BASENAME}.pdf
	rm -f sections/*.aux
