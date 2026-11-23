ZORK_NUMBER = 1

include ../Makefile.zork

.PHONY: test

test: $(GAME).z3
	python3 ../regtest.py -g "$(GAME).z3" zork1.regtest
