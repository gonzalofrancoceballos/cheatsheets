### Build wheel file
This needs to be run for every release
```bash
python setup.py bdist_wheel
```

### Upload release to PyPI test repository
twine upload --repository testpypi dist/*

### Upload release to PyPI
twine upload dist/*