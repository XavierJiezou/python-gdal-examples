# Python-GDAL-Examples

Code examples for Python module GDAL.

## Install

### Windows

1. Download the `whl` file

> [https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal](https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal)

2. Install

```bash
pip install GDAL-3.3.3-cp38-cp38-win_amd64.whl
```

3. View the version

```python
>>> from osgeo import gdal
>>> gdal.__version__
'3.3.3'
```

### Unix

> [https://gdal.org/api/python.html#unix](https://gdal.org/api/python.html#unix)

## Usage

```bash
git clone https://github.com/XavierJiezou/python-gdal-examples.git
cd python-gdal-examples
```

- [1_three_bands_stacked](./examples/1_three_bands_stacked.py): Three bands stacked into an RGB image.
- ……: ……

## Reference

> [https://github.com/OSGeo/gdal](https://github.com/OSGeo/gdal)

## Recommend

> - osgeo中国的中文文档：[栅格API教程 - GDAL 文档](https://www.osgeo.cn/gdal/tutorials/raster_api_tut.html#)
> - gdal官方提供的API文档：[https://gdal.org/python/index.html](https://gdal.org/python/index.html)
> - 慧地球公众号文章：[遥感影像的输出](https://mp.weixin.qq.com/s?__biz=Mzg4MTIyMjY3MQ==&mid=2247483686&idx=1&sn=9413db843fca4a0e1c35f99778f987bd&chksm=cf687446f81ffd50ed1154b959dd1f11723becec8fe3a08b10093aeb4ab2cd3b59dd064c65db&scene=21#wechat_redirect)
> - Python与开源GIS网站：[使用GDAL处理栅格数据 GDAL简介](https://www.osgeo.cn/pygis/gdal-gdalintro.html)
> - 开放地理空间实验室：犹他州立大学笔记：[Python GDAL课程笔记](https://www.osgeo.cn/python_gdal_utah_tutorial/index.html)
> - Python GDAL/OGR Cookbook: [http://pcjericks.github.io/py-gdalogr-cookbook/#](http://pcjericks.github.io/py-gdalogr-cookbook/#)
> - Code for the book Geoprocessing with Python: [https://github.com/cgarrard/osgeopy-code](https://github.com/cgarrard/osgeopy-code)