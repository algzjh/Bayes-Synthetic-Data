# 文件说明

- GenerateCertainNumberData: 利用drawdata.xyz生成特定数量的数据
- PrivDataVis-Artificial: 利用人造数据比较差分前后的可视化差别

# 运行

远程连接vai-server

```shell
conda activate privacy
pip install -r requirements.txt
jupyter-lab --ip=0.0.0.0 --port=30001
# VS Code 中设置Jupyter Server: Remote，选择包含token的URL
```

生成requirements.txt

```shell
pip install pipreqsnb
pipreqsnb .
```