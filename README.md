# Random JPG Glitcher
Randomly glitches JPGs and saves output as image or video file

## install
```
pip install -r requirements.txt
```

## usage
```
./rjg.py -h
tbd...

```

## Sample Video output
```
./rjg.py --mutations 5-10 vid --mode seq --mspf=250 --seq-rounds=15
```
[watch video](https://raw.githubusercontent.com/zrthstr/random-jpg-glitcher/master/output/sample-seq.mp4)


## Sample image output
```
for e in $(seq 10); do ./rjg.py img ; done
```

![](output/sample1.png) ![](output/sample5.png)
![](output/sample3.png) ![](output/sample6.png)
![](output/sample7.png) ![](output/sample8.png)
![](output/sample9.png) ![](output/sample10.png)
![](output/sample11.png) ![](output/sample12.png)


