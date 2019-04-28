# sentinel2-notebook

## good goby
* http://www.acgeospatial.co.uk/jupyter-notebooks-and-satellite-imagery/

## Build environment
```bash
conda create --name s2-processing-env python=3 opencv jupyter notebook --yes 
```

## get the data
* preselected a low cloud obsecurity S2 granule covering part of the UK
```
wget --content-disposition --continue --user=myusername --password=mypassword "https://scihub.copernicus.eu/dhus/odata/v1/Products('ae5834dd-e906-4c31-a38b-7481fbd8eae8')/\$value"
```
* this s2 Level 1C download has the following product-id `S2B_MSIL1C_20190420T112119_N0207_R037_T30UVC_20190420T132504`

