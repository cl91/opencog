IF(HAVE_ATOMSPACE)
	ADD_SUBDIRECTORY (agents)
	ADD_SUBDIRECTORY (module)
ENDIF(HAVE_ATOMSPACE)

IF(HAVE_ATTENTION)
	ADD_SUBDIRECTORY (c++-attentionbank)
	#ADD_SUBDIRECTORY (hopfield)
ENDIF(HAVE_ATTENTION)

