
An image, ready to be used with cypress but also provides all the dependencies we need for testing specter-desktop.
Use versions of cypress as the version part of the tag. So e.g.:

```
docker build . -t registry.gitlab.com/cryptoadvance/specter-desktop/cypress-python-jammy:v9.7.0
docker push registry.gitlab.com/cryptoadvance/specter-desktop/cypress-python-jammy:v9.7.0
```

Search for `cypress-python` on where this is used in the project.
