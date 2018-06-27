# frames-javadocs

After *frames* api is compiled run:

```sh
#n below is the prescene release
$ cd framesjs/distribution/frames-n/reference
$ git init
$ git remote add origin https://github.com/VisualComputing/frames-javadocs.git
$ git add *
$ git commit -am'init commit'
$ git pull --allow-unrelated-histories origin gh-pages -Xours
$ git push origin master:gh-pages
```
