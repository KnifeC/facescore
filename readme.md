# Get Facescore With Faceplusplus
> Everyone will tend to get the score 5

# Attention
**Now there are something wrong with file upload , don't use like 'python facescore.py -f mypic.jpg'**

You need a JSON configure file like 
```js
{
    "api_key":"Your API Key"
    "api_secret":"Your Secret"
}
```

# How To Use
``` bash
python facescore.py 
[-c configure_file_path] 
(choose 1 in 3)
[-u url]
[-f file]
[-b base64code]
```
* if dont have -c arguments ,the programming will read the default configure file

* use like

```bash
python facescore.py -c facescore.conf -u https://mypic.jpg
```
