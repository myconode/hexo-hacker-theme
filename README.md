# Hacker
__Hacker is a simple style of theme for blog, hoping you focus on writing more rather than the typesetting.__  

Forked from [DaraW's](http://blog.daraw.cn/) port of [moyo](http://liuxinyu.me/).
Later, DaraW ported it to Hexo.

## Installation
Create a folder `Hacker` in the folder `themes`, and copy all the theme files to the folder `Hacker`.  

Then apply the theme in hexo global configuration file `_config.yml`:

```yaml
theme: Hacker
```
Now all is in order, just enjoy~

__Notice: After every update, you'd better run command `hexo clean` to clean cache files before Hexo generating, in case of some problems cache files bring.__


## Configure
In the theme configuration file `_config.yml`:

```yaml
# disqus comment
disqus: false
disqus_shortname:

# google analytics
googleTrackId:
```

`disqus`: `boolean`, use disqus or not;  
`disqus_shortname`: your disqus site shortname.

`googleTrackId`: your Google Analytics ID, Hacker will not use Google Analytics if it's empty.
