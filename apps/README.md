# meta info

metas are structured like:
```
apps:
	demo:demo/app.py tags:demo
```
if you were to have more, you would do

```
apps:
	demo:demo/app.py tags:demo
        searchname:dirname/main.py tags:tag1, tag2, etc
```
this should hopefully explain it

searchname = when you search for it or install it using package managers, this is what is shown as the "official name" that get shown to the user

dirname = directory name where the app is located

main.py = can be anything else binary

tags = search tags
