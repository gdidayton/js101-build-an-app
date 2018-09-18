## DOM Access by ID

You can find nodes by `ID` using the method:

```
document.getElementById(id);
```

For example, to find:

```
<img id="kittenPic" src="http://placekitten.com/g/200/300" alt="cat"/>
```

We would use:

```
const imgKitten = document.getElementById('kittenPic');
```