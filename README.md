# MuseStudio
实现 Muse 数据可视化的一个很好的python应用；适合开发一些美学展示系统，与OpenCV的视频数据流实时分析相结合。
<img width="1242" alt="屏幕截图 2023-03-03 152341" src="https://user-images.githubusercontent.com/105711458/224209543-122adf3a-2331-4716-9d39-df1259339741.png">



[![DOI](https://zenodo.org/badge/334904649.svg)](https://zenodo.org/badge/latestdoi/334904649)
[![PyPI](https://img.shields.io/pypi/v/musestudio)](https://pypi.org/project/musestudio/)
[![PyPI - License](https://img.shields.io/pypi/l/musestudio)](https://github.com/miguelascifo/MuseStudio/blob/main/LICENSE)

MuseStudio allows managing data associated to a single or multiple sessions with Muse devices. Additionally, the library allows viewing brain activity data in real time from individuals wearing Muse.

Features:
* Import raw data from recordings (in XDF file format)
* Convert brain activity data to MNE and Pandas compatible formats
* Import and export following the BIDS standard
* View real time data in web browser

Templates are necessary for BIDS import and export.

This library is compatible with all Muse hardware versions.

## Templates
```python
setup = [
    {
        'subject': None,
        'session': None,
        'task': None,
        'acquisition': None,
        'run': None,
        'processing': None,
        'recording': None,
        'space': None,
        'split': None,
        'root': None,
        'suffix': None,
        'extension': None
    }
]

participants = [
    {
        'subject': None,
        'age': None,
        'sex': None,
        'hand': None,
        'root': None
    }
]
```

## Citing
Sánchez-Cifo, M. Á., Montero, F., & López, M. T. (2021). MuseStudio: Brain Activity Data Management Library for Low-Cost EEG Devices. Applied Sciences, 11(16), 7644. MDPI AG. Retrieved from http://dx.doi.org/10.3390/app11167644

Miguel Ángel Sánchez-Cifo, Francisco Montero, & Maria Teresa López (2021). MuseStudio (0.1.0). Zenodo. https://doi.org/10.5281/zenodo.4564083
