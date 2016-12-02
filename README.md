# sasper

The modified default theme for [Ghost](http://github.com/tryghost/ghost/).

To download, visit the [releases](https://github.com/sesser/sasper/releases) page.

## Key Differences

### Disqus Support
Added [disqus](https://disqus.com/) support (thanks to [Uno-Zen](https://github.com/Kikobeats/uno-zen) theme by @kikobeats). To make it work, signup for an account and add the following to your Code Injection > Blog Header:

```html
<script> var disqus_shortname = 'your-shortname'; </script>
```
### Google Analytics support
Added Google Analytics support (thanks to [Uno-Zen](https://github.com/Kikobeats/uno-zen) theme by @kikobeats). Just add the following to your Code Injection > Blog Header:

```html
<script>var ga_id = 'your-ga-account';</script>
```

### Photo Captions
Added some styles to support a small caption under photos. Just add an element after each image with a class of `photo-caption` and your ready to rock.

```html
<small class="photo-caption">This is a photo caption</small>
```

## Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
