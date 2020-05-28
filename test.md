## 文件说明

* info.txt为隐藏的信息

* LSBSteg.py为隐藏算法

* picture.jpg为原图片

* test.png为隐藏信息处理后的图片

* result.txt为解密出的结果

## 操作

加密

```bash
python LSBSteg.py encode -i picture.jpg -o test.png -f info.txt
```

解密

```bash
python LSBSteg.py decode -i test.png -o result.txt
```
