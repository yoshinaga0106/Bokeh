# Bokeh
使い方をメモする

## Install
* Anaconda or pip

```shell
$ conda install bokeh
```

## Using Sample Data
* 初めてなのでsampleから

### Bokehコマンド
```shell
$ bokeh sampledata
```

* 以下のようにDownloadされる

```
Creating /Users/yoshinaga/.bokeh directory
Creating /Users/yoshinaga/.bokeh/data directory
Using data directory: /Users/yoshinaga/.bokeh/data
Downloading: CGM.csv (1589982 bytes)
   1589982 [100.00%]
Downloading: US_Counties.zip (3182088 bytes)
   3182088 [100.00%]
Unpacking: US_Counties.csv
Downloading: us_cities.json (713565 bytes)
    713565 [100.00%]
Downloading: unemployment09.csv (253301 bytes)
    253301 [100.00%]
Downloading: AAPL.csv (166698 bytes)
    166698 [100.00%]
Downloading: FB.csv (9706 bytes)
      9706 [100.00%]
Downloading: GOOG.csv (113894 bytes)
    113894 [100.00%]
Downloading: IBM.csv (165625 bytes)
    165625 [100.00%]
Downloading: MSFT.csv (161614 bytes)
    161614 [100.00%]
Downloading: WPP2012_SA_DB03_POPULATION_QUINQUENNIAL.zip (5148539 bytes)
   5148539 [100.00%]
Unpacking: WPP2012_SA_DB03_POPULATION_QUINQUENNIAL.csv
Downloading: gapminder_fertility.csv (64346 bytes)
     64346 [100.00%]
Downloading: gapminder_population.csv (94509 bytes)
     94509 [100.00%]
Downloading: gapminder_life_expectancy.csv (73243 bytes)
     73243 [100.00%]
Downloading: gapminder_regions.csv (7781 bytes)
      7781 [100.00%]
Downloading: world_cities.zip (646858 bytes)
    646858 [100.00%]
Unpacking: world_cities.csv
Downloading: airports.json (6373 bytes)
      6373 [100.00%]
Downloading: movies.db.zip (5067833 bytes)
   5067833 [100.00%]
Unpacking: movies.db

```

あとはNotebookでサンプルをまとめる

## 注意
* Jupyterlabだと素の状態で可視化できない
```shell
Loading BokehJS ...
JavaScript output is disabled in JupyterLab
```

### 解決策
* githubのissue
  * https://github.com/jupyterlab/jupyterlab/issues/2710
* jupyterlabへのextension
  * https://github.com/bokeh/jupyterlab_bokeh

### 方法
* node.js, npmを入れる
  * 素朴にhomebrewで
