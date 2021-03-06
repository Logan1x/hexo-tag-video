# hexo-tag-video

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]

This is a tag plugin of Hexo to insert a video on your blog posts.

If you insert each video `<iframe>` directly into your markdown file, the video which in the generated page is not responsive......so I made this plugin.

如果用每个视频的 `<iframe>` 通用分享代码直接插入到 markdown 文件中，则生成的页面中视频不是响应式的……所以就做了这个插件。

## Installation

Run the following command in the root directory of hexo:

```sh
npm install hexo-tag-video --save
```

And enable the plugin in your `_config.yml.` if your Hexo version is below 3.0.

```
plugins:
  - hexo-tag-video
```

## Usage

The following code insert the video player in your post:

```
{% video 'videoCode' %}
```

This `videoCode` is the **embed code** of each video. In general, the `videoCode` can be finded when you click the **Share** button under the video.

#### Example

```
{% video '<iframe height=498 width=510 src="http://player.youku.com/embed/XNTkyMTM0MzY4" frameborder=0 allowfullscreen></iframe>' %}
```



[npm-image]: https://img.shields.io/npm/v/hexo-tag-video.svg
[npm-url]: https://npmjs.org/package/hexo-tag-video
[downloads-image]: https://img.shields.io/npm/dm/hexo-tag-video.svg
[downloads-url]: https://npmjs.org/package/hexo-tag-video
