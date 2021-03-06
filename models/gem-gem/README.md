# opus-2020-07-06.zip

* dataset: opus
* model: transformer
* source language(s): afr ang_Latn dan deu eng enm_Latn fao frr fry gos got_Goth gsw isl ksh ltz nds nld nno nob nob_Hebr non_Latn pdc sco stq swe swg yid
* target language(s): afr ang_Latn dan deu eng enm_Latn fao frr fry gos got_Goth gsw isl ksh ltz nds nld nno nob nob_Hebr non_Latn pdc sco stq swe swg yid
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-07-06.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-06.zip)
* test set translations: [opus-2020-07-06.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-06.test.txt)
* test set scores: [opus-2020-07-06.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-06.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.afr-ang.afr.ang 	| 16.0 	| 0.062 |
| Tatoeba-test.afr-dan.afr.dan 	| 100.0 	| 1.000 |
| Tatoeba-test.afr-deu.afr.deu 	| 46.7 	| 0.662 |
| Tatoeba-test.afr-eng.afr.eng 	| 57.1 	| 0.715 |
| Tatoeba-test.afr-enm.afr.enm 	| 13.4 	| 0.434 |
| Tatoeba-test.afr-fry.afr.fry 	| 16.0 	| 0.047 |
| Tatoeba-test.afr-gos.afr.gos 	| 3.9 	| 0.193 |
| Tatoeba-test.afr-isl.afr.isl 	| 29.0 	| 0.624 |
| Tatoeba-test.afr-ltz.afr.ltz 	| 3.9 	| 0.198 |
| Tatoeba-test.afr-nld.afr.nld 	| 54.4 	| 0.710 |
| Tatoeba-test.afr-nor.afr.nor 	| 5.9 	| 0.271 |
| Tatoeba-test.afr-swe.afr.swe 	| 100.0 	| 1.000 |
| Tatoeba-test.afr-yid.afr.yid 	| 59.5 	| 0.443 |
| Tatoeba-test.ang-afr.ang.afr 	| 16.0 	| 0.146 |
| Tatoeba-test.ang-dan.ang.dan 	| 1.2 	| 0.149 |
| Tatoeba-test.ang-deu.ang.deu 	| 2.2 	| 0.189 |
| Tatoeba-test.ang-eng.ang.eng 	| 6.0 	| 0.240 |
| Tatoeba-test.ang-enm.ang.enm 	| 2.6 	| 0.208 |
| Tatoeba-test.ang-fao.ang.fao 	| 10.7 	| 0.085 |
| Tatoeba-test.ang-gos.ang.gos 	| 8.1 	| 0.209 |
| Tatoeba-test.ang-isl.ang.isl 	| 10.7 	| 0.129 |
| Tatoeba-test.ang-ltz.ang.ltz 	| 10.7 	| 0.088 |
| Tatoeba-test.ang-yid.ang.yid 	| 1.6 	| 0.135 |
| Tatoeba-test.dan-afr.dan.afr 	| 43.2 	| 0.821 |
| Tatoeba-test.dan-ang.dan.ang 	| 2.4 	| 0.111 |
| Tatoeba-test.dan-deu.dan.deu 	| 47.2 	| 0.673 |
| Tatoeba-test.dan-eng.dan.eng 	| 54.4 	| 0.699 |
| Tatoeba-test.dan-enm.dan.enm 	| 13.6 	| 0.357 |
| Tatoeba-test.dan-fao.dan.fao 	| 8.1 	| 0.135 |
| Tatoeba-test.dan-gos.dan.gos 	| 4.9 	| 0.295 |
| Tatoeba-test.dan-isl.dan.isl 	| 42.7 	| 0.660 |
| Tatoeba-test.dan-ltz.dan.ltz 	| 82.1 	| 0.617 |
| Tatoeba-test.dan-nds.dan.nds 	| 10.2 	| 0.386 |
| Tatoeba-test.dan-nld.dan.nld 	| 59.0 	| 0.740 |
| Tatoeba-test.dan-nor.dan.nor 	| 1.6 	| 0.210 |
| Tatoeba-test.dan-swe.dan.swe 	| 63.8 	| 0.776 |
| Tatoeba-test.dan-swg.dan.swg 	| 5.1 	| 0.240 |
| Tatoeba-test.dan-yid.dan.yid 	| 7.1 	| 0.207 |
| Tatoeba-test.deu-afr.deu.afr 	| 50.8 	| 0.684 |
| Tatoeba-test.deu-ang.deu.ang 	| 0.6 	| 0.105 |
| Tatoeba-test.deu-dan.deu.dan 	| 49.4 	| 0.674 |
| Tatoeba-test.deu-eng.deu.eng 	| 43.8 	| 0.619 |
| Tatoeba-test.deu-enm.deu.enm 	| 7.1 	| 0.300 |
| Tatoeba-test.deu-frr.deu.frr 	| 0.6 	| 0.154 |
| Tatoeba-test.deu-fry.deu.fry 	| 15.5 	| 0.376 |
| Tatoeba-test.deu-gos.deu.gos 	| 1.8 	| 0.235 |
| Tatoeba-test.deu-got.deu.got 	| 0.5 	| 0.013 |
| Tatoeba-test.deu-gsw.deu.gsw 	| 0.9 	| 0.139 |
| Tatoeba-test.deu-isl.deu.isl 	| 24.9 	| 0.507 |
| Tatoeba-test.deu-ksh.deu.ksh 	| 0.6 	| 0.157 |
| Tatoeba-test.deu-ltz.deu.ltz 	| 12.9 	| 0.288 |
| Tatoeba-test.deu-nds.deu.nds 	| 20.3 	| 0.460 |
| Tatoeba-test.deu-nld.deu.nld 	| 47.2 	| 0.659 |
| Tatoeba-test.deu-nor.deu.nor 	| 1.1 	| 0.196 |
| Tatoeba-test.deu-pdc.deu.pdc 	| 7.6 	| 0.178 |
| Tatoeba-test.deu-sco.deu.sco 	| 13.3 	| 0.306 |
| Tatoeba-test.deu-stq.deu.stq 	| 3.9 	| 0.201 |
| Tatoeba-test.deu-swe.deu.swe 	| 49.7 	| 0.660 |
| Tatoeba-test.deu-swg.deu.swg 	| 0.3 	| 0.147 |
| Tatoeba-test.deu-yid.deu.yid 	| 4.1 	| 0.192 |
| Tatoeba-test.eng-afr.eng.afr 	| 54.7 	| 0.720 |
| Tatoeba-test.eng-ang.eng.ang 	| 5.4 	| 0.127 |
| Tatoeba-test.eng-dan.eng.dan 	| 51.8 	| 0.679 |
| Tatoeba-test.eng-deu.eng.deu 	| 35.6 	| 0.573 |
| Tatoeba-test.eng-enm.eng.enm 	| 8.2 	| 0.348 |
| Tatoeba-test.eng-fao.eng.fao 	| 6.7 	| 0.300 |
| Tatoeba-test.eng-frr.eng.frr 	| 6.4 	| 0.156 |
| Tatoeba-test.eng-fry.eng.fry 	| 17.0 	| 0.391 |
| Tatoeba-test.eng-gos.eng.gos 	| 1.4 	| 0.204 |
| Tatoeba-test.eng-got.eng.got 	| 0.3 	| 0.011 |
| Tatoeba-test.eng-gsw.eng.gsw 	| 1.3 	| 0.154 |
| Tatoeba-test.eng-isl.eng.isl 	| 21.6 	| 0.469 |
| Tatoeba-test.eng-ksh.eng.ksh 	| 0.7 	| 0.132 |
| Tatoeba-test.eng-ltz.eng.ltz 	| 13.8 	| 0.293 |
| Tatoeba-test.eng-nds.eng.nds 	| 18.5 	| 0.428 |
| Tatoeba-test.eng-nld.eng.nld 	| 47.5 	| 0.657 |
| Tatoeba-test.eng-non.eng.non 	| 0.6 	| 0.138 |
| Tatoeba-test.eng-nor.eng.nor 	| 1.6 	| 0.197 |
| Tatoeba-test.eng-pdc.eng.pdc 	| 5.6 	| 0.204 |
| Tatoeba-test.eng-sco.eng.sco 	| 36.4 	| 0.579 |
| Tatoeba-test.eng-stq.eng.stq 	| 6.7 	| 0.325 |
| Tatoeba-test.eng-swe.eng.swe 	| 52.1 	| 0.670 |
| Tatoeba-test.eng-swg.eng.swg 	| 1.1 	| 0.171 |
| Tatoeba-test.eng-yid.eng.yid 	| 4.3 	| 0.194 |
| Tatoeba-test.enm-afr.enm.afr 	| 22.9 	| 0.411 |
| Tatoeba-test.enm-ang.enm.ang 	| 0.4 	| 0.059 |
| Tatoeba-test.enm-dan.enm.dan 	| 55.2 	| 0.821 |
| Tatoeba-test.enm-deu.enm.deu 	| 40.5 	| 0.509 |
| Tatoeba-test.enm-eng.enm.eng 	| 18.7 	| 0.467 |
| Tatoeba-test.enm-fry.enm.fry 	| 0.0 	| 0.181 |
| Tatoeba-test.enm-gos.enm.gos 	| 11.8 	| 0.327 |
| Tatoeba-test.enm-isl.enm.isl 	| 59.5 	| 0.534 |
| Tatoeba-test.enm-ksh.enm.ksh 	| 8.4 	| 0.130 |
| Tatoeba-test.enm-nds.enm.nds 	| 17.6 	| 0.479 |
| Tatoeba-test.enm-nld.enm.nld 	| 38.3 	| 0.548 |
| Tatoeba-test.enm-nor.enm.nor 	| 5.3 	| 0.126 |
| Tatoeba-test.enm-yid.enm.yid 	| 3.8 	| 0.189 |
| Tatoeba-test.fao-ang.fao.ang 	| 2.6 	| 0.073 |
| Tatoeba-test.fao-dan.fao.dan 	| 19.3 	| 0.497 |
| Tatoeba-test.fao-eng.fao.eng 	| 22.0 	| 0.429 |
| Tatoeba-test.fao-gos.fao.gos 	| 12.7 	| 0.148 |
| Tatoeba-test.fao-isl.fao.isl 	| 26.3 	| 0.314 |
| Tatoeba-test.fao-nor.fao.nor 	| 1.0 	| 0.185 |
| Tatoeba-test.fao-swe.fao.swe 	| 0.0 	| 0.617 |
| Tatoeba-test.frr-deu.frr.deu 	| 8.8 	| 0.276 |
| Tatoeba-test.frr-eng.frr.eng 	| 7.0 	| 0.148 |
| Tatoeba-test.frr-fry.frr.fry 	| 3.9 	| 0.131 |
| Tatoeba-test.frr-gos.frr.gos 	| 3.3 	| 0.195 |
| Tatoeba-test.frr-nds.frr.nds 	| 12.4 	| 0.155 |
| Tatoeba-test.frr-nld.frr.nld 	| 6.1 	| 0.239 |
| Tatoeba-test.frr-stq.frr.stq 	| 2.5 	| 0.129 |
| Tatoeba-test.fry-afr.fry.afr 	| 0.0 	| 1.000 |
| Tatoeba-test.fry-deu.fry.deu 	| 27.1 	| 0.538 |
| Tatoeba-test.fry-eng.fry.eng 	| 29.0 	| 0.490 |
| Tatoeba-test.fry-enm.fry.enm 	| 10.7 	| 0.211 |
| Tatoeba-test.fry-frr.fry.frr 	| 3.1 	| 0.107 |
| Tatoeba-test.fry-gos.fry.gos 	| 1.6 	| 0.297 |
| Tatoeba-test.fry-ltz.fry.ltz 	| 29.9 	| 0.423 |
| Tatoeba-test.fry-nds.fry.nds 	| 8.1 	| 0.086 |
| Tatoeba-test.fry-nld.fry.nld 	| 42.9 	| 0.626 |
| Tatoeba-test.fry-nor.fry.nor 	| 1.1 	| 0.164 |
| Tatoeba-test.fry-stq.fry.stq 	| 2.7 	| 0.231 |
| Tatoeba-test.fry-swe.fry.swe 	| 30.2 	| 0.587 |
| Tatoeba-test.fry-yid.fry.yid 	| 5.6 	| 0.086 |
| Tatoeba-test.gos-afr.gos.afr 	| 7.2 	| 0.273 |
| Tatoeba-test.gos-ang.gos.ang 	| 5.3 	| 0.162 |
| Tatoeba-test.gos-dan.gos.dan 	| 4.5 	| 0.234 |
| Tatoeba-test.gos-deu.gos.deu 	| 20.9 	| 0.408 |
| Tatoeba-test.gos-eng.gos.eng 	| 15.6 	| 0.325 |
| Tatoeba-test.gos-enm.gos.enm 	| 6.8 	| 0.289 |
| Tatoeba-test.gos-fao.gos.fao 	| 19.0 	| 0.169 |
| Tatoeba-test.gos-frr.gos.frr 	| 3.1 	| 0.161 |
| Tatoeba-test.gos-fry.gos.fry 	| 13.6 	| 0.374 |
| Tatoeba-test.gos-isl.gos.isl 	| 3.8 	| 0.133 |
| Tatoeba-test.gos-ltz.gos.ltz 	| 1.6 	| 0.157 |
| Tatoeba-test.gos-nds.gos.nds 	| 4.8 	| 0.213 |
| Tatoeba-test.gos-nld.gos.nld 	| 16.5 	| 0.405 |
| Tatoeba-test.gos-stq.gos.stq 	| 2.1 	| 0.218 |
| Tatoeba-test.gos-swe.gos.swe 	| 10.2 	| 0.191 |
| Tatoeba-test.gos-yid.gos.yid 	| 2.1 	| 0.119 |
| Tatoeba-test.got-deu.got.deu 	| 0.2 	| 0.042 |
| Tatoeba-test.got-eng.got.eng 	| 0.2 	| 0.033 |
| Tatoeba-test.got-nor.got.nor 	| 16.0 	| 0.022 |
| Tatoeba-test.gsw-deu.gsw.deu 	| 9.1 	| 0.356 |
| Tatoeba-test.gsw-eng.gsw.eng 	| 14.0 	| 0.322 |
| Tatoeba-test.isl-afr.isl.afr 	| 40.9 	| 0.679 |
| Tatoeba-test.isl-ang.isl.ang 	| 5.3 	| 0.082 |
| Tatoeba-test.isl-dan.isl.dan 	| 67.7 	| 0.769 |
| Tatoeba-test.isl-deu.isl.deu 	| 42.8 	| 0.619 |
| Tatoeba-test.isl-eng.isl.eng 	| 43.2 	| 0.608 |
| Tatoeba-test.isl-enm.isl.enm 	| 12.7 	| 0.138 |
| Tatoeba-test.isl-fao.isl.fao 	| 15.6 	| 0.353 |
| Tatoeba-test.isl-gos.isl.gos 	| 10.8 	| 0.284 |
| Tatoeba-test.isl-nor.isl.nor 	| 1.1 	| 0.180 |
| Tatoeba-test.isl-stq.isl.stq 	| 8.1 	| 0.168 |
| Tatoeba-test.isl-swe.isl.swe 	| 48.8 	| 0.682 |
| Tatoeba-test.ksh-deu.ksh.deu 	| 12.7 	| 0.412 |
| Tatoeba-test.ksh-eng.ksh.eng 	| 4.2 	| 0.234 |
| Tatoeba-test.ksh-enm.ksh.enm 	| 13.4 	| 0.354 |
| Tatoeba-test.ltz-afr.ltz.afr 	| 31.4 	| 0.447 |
| Tatoeba-test.ltz-ang.ltz.ang 	| 0.0 	| 0.051 |
| Tatoeba-test.ltz-dan.ltz.dan 	| 91.6 	| 0.811 |
| Tatoeba-test.ltz-deu.ltz.deu 	| 44.7 	| 0.607 |
| Tatoeba-test.ltz-eng.ltz.eng 	| 34.7 	| 0.497 |
| Tatoeba-test.ltz-fry.ltz.fry 	| 31.4 	| 0.527 |
| Tatoeba-test.ltz-gos.ltz.gos 	| 3.8 	| 0.179 |
| Tatoeba-test.ltz-nld.ltz.nld 	| 38.5 	| 0.522 |
| Tatoeba-test.ltz-nor.ltz.nor 	| 7.6 	| 0.121 |
| Tatoeba-test.ltz-stq.ltz.stq 	| 3.6 	| 0.116 |
| Tatoeba-test.ltz-swe.ltz.swe 	| 26.7 	| 0.406 |
| Tatoeba-test.ltz-yid.ltz.yid 	| 0.9 	| 0.171 |
| Tatoeba-test.multi.multi 	| 42.7 	| 0.611 |
| Tatoeba-test.nds-dan.nds.dan 	| 37.0 	| 0.531 |
| Tatoeba-test.nds-deu.nds.deu 	| 37.7 	| 0.596 |
| Tatoeba-test.nds-eng.nds.eng 	| 32.1 	| 0.515 |
| Tatoeba-test.nds-enm.nds.enm 	| 6.4 	| 0.179 |
| Tatoeba-test.nds-frr.nds.frr 	| 8.1 	| 0.076 |
| Tatoeba-test.nds-fry.nds.fry 	| 5.5 	| 0.094 |
| Tatoeba-test.nds-gos.nds.gos 	| 3.1 	| 0.222 |
| Tatoeba-test.nds-nld.nds.nld 	| 43.4 	| 0.630 |
| Tatoeba-test.nds-nor.nds.nor 	| 0.8 	| 0.186 |
| Tatoeba-test.nds-swg.nds.swg 	| 0.3 	| 0.130 |
| Tatoeba-test.nds-yid.nds.yid 	| 37.0 	| 0.445 |
| Tatoeba-test.nld-afr.nld.afr 	| 58.1 	| 0.746 |
| Tatoeba-test.nld-dan.nld.dan 	| 60.8 	| 0.744 |
| Tatoeba-test.nld-deu.nld.deu 	| 48.2 	| 0.670 |
| Tatoeba-test.nld-eng.nld.eng 	| 52.7 	| 0.689 |
| Tatoeba-test.nld-enm.nld.enm 	| 6.6 	| 0.220 |
| Tatoeba-test.nld-frr.nld.frr 	| 2.4 	| 0.196 |
| Tatoeba-test.nld-fry.nld.fry 	| 22.1 	| 0.461 |
| Tatoeba-test.nld-gos.nld.gos 	| 1.9 	| 0.206 |
| Tatoeba-test.nld-ltz.nld.ltz 	| 14.6 	| 0.311 |
| Tatoeba-test.nld-nds.nld.nds 	| 23.2 	| 0.474 |
| Tatoeba-test.nld-nor.nld.nor 	| 2.1 	| 0.211 |
| Tatoeba-test.nld-sco.nld.sco 	| 7.8 	| 0.349 |
| Tatoeba-test.nld-stq.nld.stq 	| 3.1 	| 0.244 |
| Tatoeba-test.nld-swe.nld.swe 	| 79.8 	| 0.860 |
| Tatoeba-test.nld-swg.nld.swg 	| 4.9 	| 0.103 |
| Tatoeba-test.nld-yid.nld.yid 	| 8.5 	| 0.200 |
| Tatoeba-test.non-eng.non.eng 	| 30.5 	| 0.486 |
| Tatoeba-test.nor-afr.nor.afr 	| 51.8 	| 0.722 |
| Tatoeba-test.nor-dan.nor.dan 	| 54.8 	| 0.721 |
| Tatoeba-test.nor-deu.nor.deu 	| 30.7 	| 0.540 |
| Tatoeba-test.nor-eng.nor.eng 	| 35.5 	| 0.543 |
| Tatoeba-test.nor-enm.nor.enm 	| 12.9 	| 0.329 |
| Tatoeba-test.nor-fao.nor.fao 	| 9.2 	| 0.356 |
| Tatoeba-test.nor-fry.nor.fry 	| 14.2 	| 0.364 |
| Tatoeba-test.nor-got.nor.got 	| 10.7 	| 0.014 |
| Tatoeba-test.nor-isl.nor.isl 	| 17.7 	| 0.414 |
| Tatoeba-test.nor-ltz.nor.ltz 	| 5.2 	| 0.135 |
| Tatoeba-test.nor-nds.nor.nds 	| 28.3 	| 0.490 |
| Tatoeba-test.nor-nld.nor.nld 	| 39.2 	| 0.603 |
| Tatoeba-test.nor-nor.nor.nor 	| 2.3 	| 0.235 |
| Tatoeba-test.nor-swe.nor.swe 	| 53.3 	| 0.706 |
| Tatoeba-test.nor-yid.nor.yid 	| 53.3 	| 0.539 |
| Tatoeba-test.pdc-deu.pdc.deu 	| 23.4 	| 0.481 |
| Tatoeba-test.pdc-eng.pdc.eng 	| 27.8 	| 0.447 |
| Tatoeba-test.sco-deu.sco.deu 	| 2.6 	| 0.229 |
| Tatoeba-test.sco-eng.sco.eng 	| 40.3 	| 0.580 |
| Tatoeba-test.sco-nld.sco.nld 	| 34.8 	| 0.514 |
| Tatoeba-test.stq-deu.stq.deu 	| 9.1 	| 0.420 |
| Tatoeba-test.stq-eng.stq.eng 	| 23.0 	| 0.482 |
| Tatoeba-test.stq-frr.stq.frr 	| 2.3 	| 0.155 |
| Tatoeba-test.stq-fry.stq.fry 	| 6.3 	| 0.239 |
| Tatoeba-test.stq-gos.stq.gos 	| 1.3 	| 0.218 |
| Tatoeba-test.stq-isl.stq.isl 	| 16.0 	| 0.127 |
| Tatoeba-test.stq-ltz.stq.ltz 	| 2.2 	| 0.126 |
| Tatoeba-test.stq-nld.stq.nld 	| 14.1 	| 0.356 |
| Tatoeba-test.stq-yid.stq.yid 	| 4.3 	| 0.099 |
| Tatoeba-test.swe-afr.swe.afr 	| 70.9 	| 0.837 |
| Tatoeba-test.swe-dan.swe.dan 	| 64.7 	| 0.781 |
| Tatoeba-test.swe-deu.swe.deu 	| 47.1 	| 0.658 |
| Tatoeba-test.swe-eng.swe.eng 	| 56.1 	| 0.700 |
| Tatoeba-test.swe-fao.swe.fao 	| 0.0 	| 1.000 |
| Tatoeba-test.swe-fry.swe.fry 	| 14.1 	| 0.315 |
| Tatoeba-test.swe-gos.swe.gos 	| 7.5 	| 0.352 |
| Tatoeba-test.swe-isl.swe.isl 	| 42.7 	| 0.622 |
| Tatoeba-test.swe-ltz.swe.ltz 	| 8.6 	| 0.350 |
| Tatoeba-test.swe-nld.swe.nld 	| 85.0 	| 0.904 |
| Tatoeba-test.swe-nor.swe.nor 	| 1.9 	| 0.199 |
| Tatoeba-test.swe-yid.swe.yid 	| 14.5 	| 0.165 |
| Tatoeba-test.swg-dan.swg.dan 	| 7.5 	| 0.319 |
| Tatoeba-test.swg-deu.swg.deu 	| 8.0 	| 0.328 |
| Tatoeba-test.swg-eng.swg.eng 	| 12.4 	| 0.322 |
| Tatoeba-test.swg-nds.swg.nds 	| 0.9 	| 0.192 |
| Tatoeba-test.swg-nld.swg.nld 	| 19.1 	| 0.396 |
| Tatoeba-test.swg-yid.swg.yid 	| 4.3 	| 0.236 |
| Tatoeba-test.yid-afr.yid.afr 	| 30.2 	| 0.654 |
| Tatoeba-test.yid-ang.yid.ang 	| 0.7 	| 0.086 |
| Tatoeba-test.yid-dan.yid.dan 	| 22.5 	| 0.370 |
| Tatoeba-test.yid-deu.yid.deu 	| 21.7 	| 0.419 |
| Tatoeba-test.yid-eng.yid.eng 	| 17.5 	| 0.366 |
| Tatoeba-test.yid-enm.yid.enm 	| 8.8 	| 0.236 |
| Tatoeba-test.yid-fry.yid.fry 	| 9.4 	| 0.139 |
| Tatoeba-test.yid-gos.yid.gos 	| 2.3 	| 0.132 |
| Tatoeba-test.yid-ltz.yid.ltz 	| 2.6 	| 0.224 |
| Tatoeba-test.yid-nds.yid.nds 	| 26.1 	| 0.607 |
| Tatoeba-test.yid-nld.yid.nld 	| 26.3 	| 0.441 |
| Tatoeba-test.yid-nor.yid.nor 	| 3.9 	| 0.216 |
| Tatoeba-test.yid-stq.yid.stq 	| 4.3 	| 0.109 |
| Tatoeba-test.yid-swe.yid.swe 	| 36.0 	| 0.562 |
| Tatoeba-test.yid-swg.yid.swg 	| 1.8 	| 0.141 |

# opus-2020-07-21.zip

* dataset: opus
* model: transformer
* source language(s): afr ang_Latn dan deu eng enm_Latn fao frr fry gos got_Goth gsw isl ksh ltz nds nld nno nob nob_Hebr non_Latn pdc sco stq swe swg yid
* target language(s): afr ang_Latn dan deu eng enm_Latn fao frr fry gos got_Goth gsw isl ksh ltz nds nld nno nob nob_Hebr non_Latn pdc sco stq swe swg yid
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-07-21.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-21.zip)
* test set translations: [opus-2020-07-21.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-21.test.txt)
* test set scores: [opus-2020-07-21.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/gem-gem/opus-2020-07-21.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.afr-ang.afr.ang 	| 8.0 	| 0.062 |
| Tatoeba-test.afr-dan.afr.dan 	| 57.8 	| 0.907 |
| Tatoeba-test.afr-deu.afr.deu 	| 45.1 	| 0.656 |
| Tatoeba-test.afr-eng.afr.eng 	| 56.7 	| 0.711 |
| Tatoeba-test.afr-enm.afr.enm 	| 11.3 	| 0.285 |
| Tatoeba-test.afr-fry.afr.fry 	| 10.7 	| 0.076 |
| Tatoeba-test.afr-gos.afr.gos 	| 1.1 	| 0.170 |
| Tatoeba-test.afr-isl.afr.isl 	| 29.0 	| 0.670 |
| Tatoeba-test.afr-ltz.afr.ltz 	| 2.5 	| 0.218 |
| Tatoeba-test.afr-nld.afr.nld 	| 53.4 	| 0.708 |
| Tatoeba-test.afr-nor.afr.nor 	| 62.4 	| 0.745 |
| Tatoeba-test.afr-swe.afr.swe 	| 67.6 	| 0.910 |
| Tatoeba-test.afr-yid.afr.yid 	| 100.0 	| 1.000 |
| Tatoeba-test.ang-afr.ang.afr 	| 7.8 	| 0.256 |
| Tatoeba-test.ang-dan.ang.dan 	| 5.5 	| 0.189 |
| Tatoeba-test.ang-deu.ang.deu 	| 2.5 	| 0.198 |
| Tatoeba-test.ang-eng.ang.eng 	| 7.5 	| 0.236 |
| Tatoeba-test.ang-enm.ang.enm 	| 1.6 	| 0.181 |
| Tatoeba-test.ang-fao.ang.fao 	| 10.7 	| 0.053 |
| Tatoeba-test.ang-gos.ang.gos 	| 16.0 	| 0.212 |
| Tatoeba-test.ang-isl.ang.isl 	| 0.0 	| 0.126 |
| Tatoeba-test.ang-ltz.ang.ltz 	| 19.0 	| 0.146 |
| Tatoeba-test.ang-yid.ang.yid 	| 4.2 	| 0.134 |
| Tatoeba-test.dan-afr.dan.afr 	| 24.7 	| 0.699 |
| Tatoeba-test.dan-ang.dan.ang 	| 1.0 	| 0.065 |
| Tatoeba-test.dan-deu.dan.deu 	| 46.5 	| 0.669 |
| Tatoeba-test.dan-eng.dan.eng 	| 53.6 	| 0.694 |
| Tatoeba-test.dan-enm.dan.enm 	| 2.7 	| 0.266 |
| Tatoeba-test.dan-fao.dan.fao 	| 9.7 	| 0.178 |
| Tatoeba-test.dan-gos.dan.gos 	| 3.5 	| 0.237 |
| Tatoeba-test.dan-isl.dan.isl 	| 46.7 	| 0.689 |
| Tatoeba-test.dan-ltz.dan.ltz 	| 82.6 	| 0.558 |
| Tatoeba-test.dan-nds.dan.nds 	| 9.7 	| 0.353 |
| Tatoeba-test.dan-nld.dan.nld 	| 58.5 	| 0.738 |
| Tatoeba-test.dan-nor.dan.nor 	| 68.2 	| 0.813 |
| Tatoeba-test.dan-swe.dan.swe 	| 64.7 	| 0.782 |
| Tatoeba-test.dan-swg.dan.swg 	| 2.9 	| 0.208 |
| Tatoeba-test.dan-yid.dan.yid 	| 11.7 	| 0.264 |
| Tatoeba-test.deu-afr.deu.afr 	| 49.0 	| 0.671 |
| Tatoeba-test.deu-ang.deu.ang 	| 0.6 	| 0.135 |
| Tatoeba-test.deu-dan.deu.dan 	| 48.8 	| 0.671 |
| Tatoeba-test.deu-eng.deu.eng 	| 42.2 	| 0.608 |
| Tatoeba-test.deu-enm.deu.enm 	| 2.6 	| 0.167 |
| Tatoeba-test.deu-frr.deu.frr 	| 0.3 	| 0.142 |
| Tatoeba-test.deu-fry.deu.fry 	| 9.3 	| 0.356 |
| Tatoeba-test.deu-gos.deu.gos 	| 0.5 	| 0.176 |
| Tatoeba-test.deu-got.deu.got 	| 0.2 	| 0.008 |
| Tatoeba-test.deu-gsw.deu.gsw 	| 0.5 	| 0.111 |
| Tatoeba-test.deu-isl.deu.isl 	| 23.3 	| 0.492 |
| Tatoeba-test.deu-ksh.deu.ksh 	| 0.8 	| 0.174 |
| Tatoeba-test.deu-ltz.deu.ltz 	| 15.2 	| 0.306 |
| Tatoeba-test.deu-nds.deu.nds 	| 20.5 	| 0.464 |
| Tatoeba-test.deu-nld.deu.nld 	| 46.5 	| 0.653 |
| Tatoeba-test.deu-nor.deu.nor 	| 43.1 	| 0.640 |
| Tatoeba-test.deu-pdc.deu.pdc 	| 3.2 	| 0.128 |
| Tatoeba-test.deu-sco.deu.sco 	| 12.2 	| 0.278 |
| Tatoeba-test.deu-stq.deu.stq 	| 0.6 	| 0.179 |
| Tatoeba-test.deu-swe.deu.swe 	| 49.7 	| 0.663 |
| Tatoeba-test.deu-swg.deu.swg 	| 0.2 	| 0.134 |
| Tatoeba-test.deu-yid.deu.yid 	| 5.4 	| 0.237 |
| Tatoeba-test.eng-afr.eng.afr 	| 53.8 	| 0.710 |
| Tatoeba-test.eng-ang.eng.ang 	| 4.3 	| 0.136 |
| Tatoeba-test.eng-dan.eng.dan 	| 51.7 	| 0.678 |
| Tatoeba-test.eng-deu.eng.deu 	| 34.4 	| 0.565 |
| Tatoeba-test.eng-enm.eng.enm 	| 2.8 	| 0.253 |
| Tatoeba-test.eng-fao.eng.fao 	| 8.7 	| 0.312 |
| Tatoeba-test.eng-frr.eng.frr 	| 1.2 	| 0.084 |
| Tatoeba-test.eng-fry.eng.fry 	| 14.5 	| 0.378 |
| Tatoeba-test.eng-gos.eng.gos 	| 0.5 	| 0.151 |
| Tatoeba-test.eng-got.eng.got 	| 0.2 	| 0.010 |
| Tatoeba-test.eng-gsw.eng.gsw 	| 0.5 	| 0.116 |
| Tatoeba-test.eng-isl.eng.isl 	| 20.5 	| 0.457 |
| Tatoeba-test.eng-ksh.eng.ksh 	| 0.9 	| 0.152 |
| Tatoeba-test.eng-ltz.eng.ltz 	| 13.5 	| 0.304 |
| Tatoeba-test.eng-nds.eng.nds 	| 17.8 	| 0.422 |
| Tatoeba-test.eng-nld.eng.nld 	| 46.4 	| 0.649 |
| Tatoeba-test.eng-non.eng.non 	| 0.3 	| 0.134 |
| Tatoeba-test.eng-nor.eng.nor 	| 46.6 	| 0.643 |
| Tatoeba-test.eng-pdc.eng.pdc 	| 3.2 	| 0.168 |
| Tatoeba-test.eng-sco.eng.sco 	| 36.5 	| 0.574 |
| Tatoeba-test.eng-stq.eng.stq 	| 5.9 	| 0.318 |
| Tatoeba-test.eng-swe.eng.swe 	| 51.9 	| 0.671 |
| Tatoeba-test.eng-swg.eng.swg 	| 1.0 	| 0.150 |
| Tatoeba-test.eng-yid.eng.yid 	| 4.8 	| 0.222 |
| Tatoeba-test.enm-afr.enm.afr 	| 22.8 	| 0.401 |
| Tatoeba-test.enm-ang.enm.ang 	| 0.5 	| 0.064 |
| Tatoeba-test.enm-dan.enm.dan 	| 59.2 	| 0.811 |
| Tatoeba-test.enm-deu.enm.deu 	| 33.8 	| 0.489 |
| Tatoeba-test.enm-eng.enm.eng 	| 28.7 	| 0.541 |
| Tatoeba-test.enm-fry.enm.fry 	| 16.0 	| 0.173 |
| Tatoeba-test.enm-gos.enm.gos 	| 5.6 	| 0.281 |
| Tatoeba-test.enm-isl.enm.isl 	| 59.5 	| 0.651 |
| Tatoeba-test.enm-ksh.enm.ksh 	| 11.4 	| 0.092 |
| Tatoeba-test.enm-nds.enm.nds 	| 17.6 	| 0.443 |
| Tatoeba-test.enm-nld.enm.nld 	| 38.3 	| 0.547 |
| Tatoeba-test.enm-nor.enm.nor 	| 8.0 	| 0.249 |
| Tatoeba-test.enm-yid.enm.yid 	| 5.3 	| 0.236 |
| Tatoeba-test.fao-ang.fao.ang 	| 0.0 	| 0.045 |
| Tatoeba-test.fao-dan.fao.dan 	| 53.7 	| 0.544 |
| Tatoeba-test.fao-eng.fao.eng 	| 23.2 	| 0.427 |
| Tatoeba-test.fao-gos.fao.gos 	| 16.0 	| 0.066 |
| Tatoeba-test.fao-isl.fao.isl 	| 26.3 	| 0.323 |
| Tatoeba-test.fao-nor.fao.nor 	| 34.6 	| 0.564 |
| Tatoeba-test.fao-swe.fao.swe 	| 0.0 	| 1.000 |
| Tatoeba-test.frr-deu.frr.deu 	| 7.8 	| 0.269 |
| Tatoeba-test.frr-eng.frr.eng 	| 8.4 	| 0.148 |
| Tatoeba-test.frr-fry.frr.fry 	| 4.0 	| 0.165 |
| Tatoeba-test.frr-gos.frr.gos 	| 1.0 	| 0.144 |
| Tatoeba-test.frr-nds.frr.nds 	| 12.4 	| 0.207 |
| Tatoeba-test.frr-nld.frr.nld 	| 9.8 	| 0.253 |
| Tatoeba-test.frr-stq.frr.stq 	| 0.7 	| 0.066 |
| Tatoeba-test.fry-afr.fry.afr 	| 0.0 	| 1.000 |
| Tatoeba-test.fry-deu.fry.deu 	| 29.0 	| 0.535 |
| Tatoeba-test.fry-eng.fry.eng 	| 31.7 	| 0.507 |
| Tatoeba-test.fry-enm.fry.enm 	| 0.0 	| 0.154 |
| Tatoeba-test.fry-frr.fry.frr 	| 1.1 	| 0.077 |
| Tatoeba-test.fry-gos.fry.gos 	| 0.8 	| 0.221 |
| Tatoeba-test.fry-ltz.fry.ltz 	| 30.9 	| 0.530 |
| Tatoeba-test.fry-nds.fry.nds 	| 10.7 	| 0.162 |
| Tatoeba-test.fry-nld.fry.nld 	| 42.9 	| 0.630 |
| Tatoeba-test.fry-nor.fry.nor 	| 42.7 	| 0.575 |
| Tatoeba-test.fry-stq.fry.stq 	| 0.3 	| 0.157 |
| Tatoeba-test.fry-swe.fry.swe 	| 30.2 	| 0.587 |
| Tatoeba-test.fry-yid.fry.yid 	| 2.0 	| 0.111 |
| Tatoeba-test.gos-afr.gos.afr 	| 5.1 	| 0.255 |
| Tatoeba-test.gos-ang.gos.ang 	| 0.0 	| 0.045 |
| Tatoeba-test.gos-dan.gos.dan 	| 3.8 	| 0.259 |
| Tatoeba-test.gos-deu.gos.deu 	| 18.7 	| 0.405 |
| Tatoeba-test.gos-eng.gos.eng 	| 14.7 	| 0.327 |
| Tatoeba-test.gos-enm.gos.enm 	| 8.5 	| 0.317 |
| Tatoeba-test.gos-fao.gos.fao 	| 19.0 	| 0.115 |
| Tatoeba-test.gos-frr.gos.frr 	| 3.1 	| 0.147 |
| Tatoeba-test.gos-fry.gos.fry 	| 15.7 	| 0.378 |
| Tatoeba-test.gos-isl.gos.isl 	| 7.5 	| 0.240 |
| Tatoeba-test.gos-ltz.gos.ltz 	| 2.9 	| 0.175 |
| Tatoeba-test.gos-nds.gos.nds 	| 5.6 	| 0.224 |
| Tatoeba-test.gos-nld.gos.nld 	| 16.1 	| 0.402 |
| Tatoeba-test.gos-stq.gos.stq 	| 0.5 	| 0.162 |
| Tatoeba-test.gos-swe.gos.swe 	| 8.2 	| 0.198 |
| Tatoeba-test.gos-yid.gos.yid 	| 3.5 	| 0.150 |
| Tatoeba-test.got-deu.got.deu 	| 0.4 	| 0.040 |
| Tatoeba-test.got-eng.got.eng 	| 0.1 	| 0.020 |
| Tatoeba-test.got-nor.got.nor 	| 0.0 	| 0.000 |
| Tatoeba-test.gsw-deu.gsw.deu 	| 14.5 	| 0.356 |
| Tatoeba-test.gsw-eng.gsw.eng 	| 13.3 	| 0.326 |
| Tatoeba-test.isl-afr.isl.afr 	| 24.9 	| 0.554 |
| Tatoeba-test.isl-ang.isl.ang 	| 5.5 	| 0.092 |
| Tatoeba-test.isl-dan.isl.dan 	| 53.4 	| 0.739 |
| Tatoeba-test.isl-deu.isl.deu 	| 41.7 	| 0.613 |
| Tatoeba-test.isl-eng.isl.eng 	| 42.3 	| 0.601 |
| Tatoeba-test.isl-enm.isl.enm 	| 12.4 	| 0.114 |
| Tatoeba-test.isl-fao.isl.fao 	| 15.6 	| 0.353 |
| Tatoeba-test.isl-gos.isl.gos 	| 7.3 	| 0.266 |
| Tatoeba-test.isl-nor.isl.nor 	| 52.9 	| 0.683 |
| Tatoeba-test.isl-stq.isl.stq 	| 10.7 	| 0.188 |
| Tatoeba-test.isl-swe.isl.swe 	| 67.7 	| 0.818 |
| Tatoeba-test.ksh-deu.ksh.deu 	| 15.5 	| 0.407 |
| Tatoeba-test.ksh-eng.ksh.eng 	| 4.2 	| 0.233 |
| Tatoeba-test.ksh-enm.ksh.enm 	| 11.3 	| 0.261 |
| Tatoeba-test.ltz-afr.ltz.afr 	| 51.1 	| 0.590 |
| Tatoeba-test.ltz-ang.ltz.ang 	| 0.0 	| 0.049 |
| Tatoeba-test.ltz-dan.ltz.dan 	| 84.5 	| 0.682 |
| Tatoeba-test.ltz-deu.ltz.deu 	| 41.6 	| 0.604 |
| Tatoeba-test.ltz-eng.ltz.eng 	| 37.0 	| 0.524 |
| Tatoeba-test.ltz-fry.ltz.fry 	| 19.0 	| 0.562 |
| Tatoeba-test.ltz-gos.ltz.gos 	| 0.3 	| 0.111 |
| Tatoeba-test.ltz-nld.ltz.nld 	| 39.2 	| 0.547 |
| Tatoeba-test.ltz-nor.ltz.nor 	| 16.0 	| 0.345 |
| Tatoeba-test.ltz-stq.ltz.stq 	| 0.7 	| 0.080 |
| Tatoeba-test.ltz-swe.ltz.swe 	| 23.3 	| 0.458 |
| Tatoeba-test.ltz-yid.ltz.yid 	| 1.9 	| 0.158 |
| Tatoeba-test.multi.multi 	| 41.7 	| 0.607 |
| Tatoeba-test.nds-dan.nds.dan 	| 24.3 	| 0.439 |
| Tatoeba-test.nds-deu.nds.deu 	| 38.6 	| 0.603 |
| Tatoeba-test.nds-eng.nds.eng 	| 31.2 	| 0.512 |
| Tatoeba-test.nds-enm.nds.enm 	| 3.9 	| 0.142 |
| Tatoeba-test.nds-frr.nds.frr 	| 10.7 	| 0.131 |
| Tatoeba-test.nds-fry.nds.fry 	| 10.7 	| 0.080 |
| Tatoeba-test.nds-gos.nds.gos 	| 0.6 	| 0.144 |
| Tatoeba-test.nds-nld.nds.nld 	| 42.6 	| 0.624 |
| Tatoeba-test.nds-nor.nds.nor 	| 45.7 	| 0.650 |
| Tatoeba-test.nds-swg.nds.swg 	| 0.4 	| 0.158 |
| Tatoeba-test.nds-yid.nds.yid 	| 4.8 	| 0.258 |
| Tatoeba-test.nld-afr.nld.afr 	| 57.8 	| 0.745 |
| Tatoeba-test.nld-dan.nld.dan 	| 61.1 	| 0.750 |
| Tatoeba-test.nld-deu.nld.deu 	| 47.3 	| 0.663 |
| Tatoeba-test.nld-eng.nld.eng 	| 51.7 	| 0.681 |
| Tatoeba-test.nld-enm.nld.enm 	| 6.2 	| 0.267 |
| Tatoeba-test.nld-frr.nld.frr 	| 0.7 	| 0.142 |
| Tatoeba-test.nld-fry.nld.fry 	| 21.5 	| 0.461 |
| Tatoeba-test.nld-gos.nld.gos 	| 0.8 	| 0.163 |
| Tatoeba-test.nld-ltz.nld.ltz 	| 14.3 	| 0.301 |
| Tatoeba-test.nld-nds.nld.nds 	| 23.4 	| 0.477 |
| Tatoeba-test.nld-nor.nld.nor 	| 52.8 	| 0.699 |
| Tatoeba-test.nld-sco.nld.sco 	| 9.3 	| 0.407 |
| Tatoeba-test.nld-stq.nld.stq 	| 0.5 	| 0.186 |
| Tatoeba-test.nld-swe.nld.swe 	| 73.6 	| 0.841 |
| Tatoeba-test.nld-swg.nld.swg 	| 0.6 	| 0.037 |
| Tatoeba-test.nld-yid.nld.yid 	| 9.3 	| 0.307 |
| Tatoeba-test.non-eng.non.eng 	| 28.0 	| 0.502 |
| Tatoeba-test.nor-afr.nor.afr 	| 50.9 	| 0.711 |
| Tatoeba-test.nor-dan.nor.dan 	| 68.9 	| 0.819 |
| Tatoeba-test.nor-deu.nor.deu 	| 40.5 	| 0.628 |
| Tatoeba-test.nor-eng.nor.eng 	| 48.8 	| 0.654 |
| Tatoeba-test.nor-enm.nor.enm 	| 7.3 	| 0.229 |
| Tatoeba-test.nor-fao.nor.fao 	| 11.9 	| 0.409 |
| Tatoeba-test.nor-fry.nor.fry 	| 4.1 	| 0.298 |
| Tatoeba-test.nor-got.nor.got 	| 1.1 	| 0.000 |
| Tatoeba-test.nor-isl.nor.isl 	| 32.2 	| 0.537 |
| Tatoeba-test.nor-ltz.nor.ltz 	| 27.8 	| 0.621 |
| Tatoeba-test.nor-nds.nor.nds 	| 26.7 	| 0.522 |
| Tatoeba-test.nor-nld.nor.nld 	| 48.9 	| 0.665 |
| Tatoeba-test.nor-nor.nor.nor 	| 57.5 	| 0.761 |
| Tatoeba-test.nor-swe.nor.swe 	| 67.5 	| 0.806 |
| Tatoeba-test.nor-yid.nor.yid 	| 61.7 	| 0.635 |
| Tatoeba-test.pdc-deu.pdc.deu 	| 34.6 	| 0.521 |
| Tatoeba-test.pdc-eng.pdc.eng 	| 28.7 	| 0.449 |
| Tatoeba-test.sco-deu.sco.deu 	| 15.2 	| 0.312 |
| Tatoeba-test.sco-eng.sco.eng 	| 32.4 	| 0.563 |
| Tatoeba-test.sco-nld.sco.nld 	| 23.2 	| 0.486 |
| Tatoeba-test.stq-deu.stq.deu 	| 5.0 	| 0.383 |
| Tatoeba-test.stq-eng.stq.eng 	| 10.5 	| 0.423 |
| Tatoeba-test.stq-frr.stq.frr 	| 2.8 	| 0.084 |
| Tatoeba-test.stq-fry.stq.fry 	| 6.8 	| 0.293 |
| Tatoeba-test.stq-gos.stq.gos 	| 0.3 	| 0.180 |
| Tatoeba-test.stq-isl.stq.isl 	| 8.1 	| 0.119 |
| Tatoeba-test.stq-ltz.stq.ltz 	| 3.5 	| 0.140 |
| Tatoeba-test.stq-nld.stq.nld 	| 15.4 	| 0.401 |
| Tatoeba-test.stq-yid.stq.yid 	| 7.0 	| 0.182 |
| Tatoeba-test.swe-afr.swe.afr 	| 66.7 	| 0.852 |
| Tatoeba-test.swe-dan.swe.dan 	| 64.7 	| 0.784 |
| Tatoeba-test.swe-deu.swe.deu 	| 46.2 	| 0.652 |
| Tatoeba-test.swe-eng.swe.eng 	| 54.8 	| 0.691 |
| Tatoeba-test.swe-fao.swe.fao 	| 0.0 	| 0.098 |
| Tatoeba-test.swe-fry.swe.fry 	| 42.7 	| 0.621 |
| Tatoeba-test.swe-gos.swe.gos 	| 7.5 	| 0.291 |
| Tatoeba-test.swe-isl.swe.isl 	| 46.7 	| 0.730 |
| Tatoeba-test.swe-ltz.swe.ltz 	| 5.5 	| 0.402 |
| Tatoeba-test.swe-nld.swe.nld 	| 77.9 	| 0.829 |
| Tatoeba-test.swe-nor.swe.nor 	| 66.4 	| 0.793 |
| Tatoeba-test.swe-yid.swe.yid 	| 11.0 	| 0.368 |
| Tatoeba-test.swg-dan.swg.dan 	| 6.9 	| 0.321 |
| Tatoeba-test.swg-deu.swg.deu 	| 8.2 	| 0.327 |
| Tatoeba-test.swg-eng.swg.eng 	| 8.3 	| 0.285 |
| Tatoeba-test.swg-nds.swg.nds 	| 0.9 	| 0.196 |
| Tatoeba-test.swg-nld.swg.nld 	| 4.9 	| 0.286 |
| Tatoeba-test.swg-yid.swg.yid 	| 2.6 	| 0.204 |
| Tatoeba-test.yid-afr.yid.afr 	| 23.6 	| 0.552 |
| Tatoeba-test.yid-ang.yid.ang 	| 0.3 	| 0.069 |
| Tatoeba-test.yid-dan.yid.dan 	| 17.4 	| 0.360 |
| Tatoeba-test.yid-deu.yid.deu 	| 21.2 	| 0.422 |
| Tatoeba-test.yid-eng.yid.eng 	| 17.2 	| 0.360 |
| Tatoeba-test.yid-enm.yid.enm 	| 1.5 	| 0.156 |
| Tatoeba-test.yid-fry.yid.fry 	| 4.8 	| 0.198 |
| Tatoeba-test.yid-gos.yid.gos 	| 1.6 	| 0.158 |
| Tatoeba-test.yid-ltz.yid.ltz 	| 3.8 	| 0.240 |
| Tatoeba-test.yid-nds.yid.nds 	| 26.1 	| 0.596 |
| Tatoeba-test.yid-nld.yid.nld 	| 25.7 	| 0.441 |
| Tatoeba-test.yid-nor.yid.nor 	| 47.1 	| 0.650 |
| Tatoeba-test.yid-stq.yid.stq 	| 1.2 	| 0.091 |
| Tatoeba-test.yid-swe.yid.swe 	| 46.4 	| 0.601 |
| Tatoeba-test.yid-swg.yid.swg 	| 1.1 	| 0.121 |

