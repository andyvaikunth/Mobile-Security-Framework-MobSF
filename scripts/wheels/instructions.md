```bash
git clone --recursive https://github.com/VirusTotal/yara-python
git checkout tags/v3.11.0
git submodule update --recursive
#Mac
python3 setup.py bdist_wheel --python-tag cp36.cp37.cp38 build --enable-dex
```