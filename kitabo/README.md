## Claude 3.5 Sonnet

```sh
cd ~/documents/memos/jam/kitabo/ensi
pip install -r requirements.txt && jupyter-book build .
cp -r foreword/app/* _build/html/foreword/app
cd ~/documents/chords/
new/jbb_https.sh
```

Only need the app to be present as you `ghp-import`. The embedding will still work as a webApp in its absence