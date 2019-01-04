> 当你与一个人相处久了 , 你会发现他能(也只能)得到(主观感受上的)5分

# Get Facescore With Faceplusplus

## Attention
* **Now there are something wrong with file upload , don't use like 'python facescore.py -f mypic.jpg'**

* You need a JSON configure file like 
```js
{
    "api_key":"Your API Key"
    "api_secret":"Your Secret"
}
```

## How To Use
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
