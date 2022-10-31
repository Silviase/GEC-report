# Dataset Preparation

## JFLEG 

```sh
git clone https://github.com/keisks/jfleg.git
```

## CWEB 

```sh
git clone https://github.com/SimonHFL/CWEB.git
```

## CoNLL-2013

```sh
mkdir conll-2013
cd conll-2013
wget https://www.comp.nus.edu.sg/~nlp/conll13st/release2.3.1.tar.gz
tar -xvzf release2.3.1.tar.gz
```

## CoNLL-2014

```sh
❯ mkdir conll-2014
❯ cd conll-2014
❯ wget https://www.comp.nus.edu.sg/~nlp/conll14st/conll14st-test-data.tar.gz
❯ tar zxvf conll14st-test-data.tar.gz
```

## AESW 

```sh
❯ wget 'http://textmining.lt/aesw/aesw2016(v1.2)_train.xml.bz2'
❯ wget 'http://textmining.lt/aesw/aesw2016(v1.2)_dev.xml.bz2'
❯ bunzip2 aesw2016\(v1.2\)_train.xml.bz2
❯ bunzip2 aesw2016\(v1.2\)_dev.xml.bz2
```

## FCE

```sh
wget https://www.cl.cam.ac.uk/research/nl/bea2019st/data/fce_v2.1.bea19.tar.gz
tar zxvf fce_v2.1.bea19.tar.gz
```

## Falko-MERLIN (German)

```sh
wget 'http://www.sfs.uni-tuebingen.de/~adriane/download/wnut2018/data.tar.gz'
tar zxvf data.tar.gz
```

## AKCES-GEC (Czech)

```sh
❯ curl --remote-name-all https://lindat.mff.cuni.cz/repository/xmlui/bitstream/handle/11234/1-3057{/AKCES-GEC.zip}
❯ mkdir akces-gec
❯ mv AKCES-GEC.zip akces-gec
❯ cd akces-gec
❯ unzip AKCES-GEC.zip
```