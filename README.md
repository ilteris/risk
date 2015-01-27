Install grunt if you haven't already
```
npm install -g grunt-cli
```
Then run the following to download version 0.12.2 of atom-shell
```
cd ./build
npm install
grunt download-atom-shell
```

if that doesn't work do:
```
grunt download-atom-shell --verbose
```


Then you should be able to run the app:

```
./build/atom-shell/Atom.app/Contents/MacOS/Atom ./risk
```

