all:
	hfst-lexc mehweb.lexc -o mehweb.lexc.hfst
	hfst-twolc mehweb.twol -o mehweb.twol.hfst
	hfst-compose-intersect -1 mehweb.lexc.hfst -2 mehweb.twol.hfst -o mehweb.hfst

clean:
	rm mehweb.hfst mehweb.lexc.hfst mehweb.twol.hfst
