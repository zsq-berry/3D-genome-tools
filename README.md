# hic_tools

Dependence:
```
pip install cooler
pip install pandas
```
juicer_tools: https://github.com/aidenlab/juicer/wiki/Feature-Annotation

1, cool2hic.py

Transfer cool to matrix text.
```
python3 cool2hic.py -i test.mcool/test.cool -r resolution
```

2, juicer_tools transfer from matrix text to hic.
```
java -Xmx20g -jar ~/packages/juicer_tools.jar pre -r resolution -d matrix.txt.gz name.hic genome
```
