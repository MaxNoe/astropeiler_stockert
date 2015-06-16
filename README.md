# Stockert 15.06.2015

all data files are available through git annex
Installation instructions here: https://git-annex.branchable.com/install/

then clone the repo and do:
```
git annex init
git annex get .
```
Or instead of the dot any file you want to download

You can get all needed python packages with
```
pip install -r requirements.txt
```
They are also included in anaconda

## Resolution 
* data/sto25_CAS_A_cont_10781.csv
* Cassiopaia A
* columns:
	* timestamp
	* azimuth / degrees
	* elevation / degrees
	* right ascension / degrees
	* declination / degrees
	* phase  (to be ignored)
	* intensity horizontal
	* intensity vertical

## Pulsar 0329+54

* Datenbank: AINF Pulsar catalogue
* Software _SigProc_

## OH Maser in the W3 HII Region
* on:  data/sto25_W3OH_spec_10782.csv
* off: data/sto25_W3OH_spec_10783.csv
* columns:
	* channel number
	* frequency / Hz
	* 4 data columns
	* sum of the data columns
* for us only the sum is needed

## Extragalactic HI
* Source: Holmberg 2
* on: 10784.csv
* off: 10785.csv
* columns:
	* channel number
	* frequency / Hz
	* 4 data columns
	* sum of the data columns
* for us only the sum is needed
