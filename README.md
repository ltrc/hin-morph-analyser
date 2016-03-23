# hindi-morph-analyzer
A Morph Analyzer for Hindi

To compile, type:
```bash
$ make -C analyser
```

Example run:
```bash
$ ./analyser/morph_hin.exe --logfilepath ./morph.log --pdgmfilepath ./analyser/data/ --uwordpath ./analyser/data/dict_final --dictfilepath ./analyser/data/dict -ULDWH --inputfile ./tests/morph_test.in --outputfile /dev/stdout | head
1	rAma		<fs af='rAma,n,m,sg,3,d,0,0'>|<fs af='rAma,n,m,pl,3,d,0,0'>|<fs af='rAma,n,m,sg,3,o,0,0'>
2	KAnA		<fs af='KAnA,n,m,sg,3,d,0,0'>|<fs af='KA,v,m,sg,any,,nA,nA'>
3	KAne		<fs af='KAnA,n,m,pl,3,d,0,0'>|<fs af='KAnA,n,m,sg,3,o,0,0'>|<fs af='KA,v,m,pl,any,,nA,nA'>
4	ke		<fs af='kA,psp,m,sg,,o,kA,kA'>|<fs af='kA,psp,m,pl,,d,kA,kA'>|<fs af='kA,psp,m,pl,,o,kA,kA'>
5	liye		<fs af='liye,psp,,,,,,'>|<fs af='le,v,any,sg,2,,e,e'>|<fs af='le,v,any,sg,3,,e,e'>|<fs af='le,v,m,pl,any,,yA,yA'>
6	apane		<fs af='apanA,pn,any,sg,1,o,kA,kA' agr_gen='m' agr_num='pl' agr_cas='d'>|<fs af='apanA,pn,any,sg,1,o,kA,kA' agr_gen='m' agr_num='sg' agr_cas='o'>|<fs af='apanA,pn,any,sg,1,o,kA,kA' agr_gen='m' agr_num='pl' agr_cas='o'>|<fs af='apanA,adj,m,sg,,o,,'>|<fs af='apanA,adj,m,pl,,d,,'>|<fs af='apanA,adj,m,pl,,o,,'>
7	Gara		<fs af='Gara,n,m,sg,3,d,0,0'>|<fs af='Gara,n,m,pl,3,d,0,0'>|<fs af='Gara,n,m,sg,3,o,0,0'>
8	gayA		<fs af='jA,v,m,sg,any,,yA1,yA1'>
9	hE		<fs af='hE,v,any,sg,2,,hE,hE'>|<fs af='hE,v,any,sg,3,,hE,hE'>
10	?		<fs af='?,punc,,,,,,'>
```
