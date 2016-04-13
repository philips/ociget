# ociget - fetch images over any URL

```
git clone https://github.com/philips/oci-transport-example
cd oci-transport-example
```

## Over local filesystems

```
./ociget file://$PWD/example
```

## Over HTTP

```
cd image
python -m SimpleHTTPServer
```

```
./ociget http://localhost:8000/manifest-list
```
