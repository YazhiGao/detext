Uploading new releases of DeText to PyPi
=========
NOTE: this guide is for DeText owners to publish new versions to PyPi

1. Make sure you have the correct permission to release DeText packages. Only owners and maintainers can upload new releases for DeText. Check more details at https://pypi.org/project/detext/.

2. Create a source distribution by:
``
python setup.py sdist
```

3. Install `twine` for uploading to PyPi
```
pip install twine
```

4. Upload the distribution
```
twine upload dist/*
```

You can verify the release upload at https://pypi.org/manage/project/detext/releases/
