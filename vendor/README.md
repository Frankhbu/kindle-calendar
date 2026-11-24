# vendor

第三方依赖的本地副本，保证页面**断网也能用**、不依赖 CDN，也不需要任何授权/登录。

| 文件 | 来源 | 版本 | 许可 |
|---|---|---|---|
| `html2canvas.min.js` | https://github.com/niklasvh/html2canvas | 1.4.1 | MIT |
| `lunar.min.js` | https://github.com/6tail/lunar-javascript | 1.7.7 | MIT |
| `jszip.min.js` | https://github.com/Stuk/jszip | 3.10.1 | MIT |

三个库都是 MIT 许可，下面是 lunar-javascript 的许可原文（其余两个同样是 MIT）。

```
MIT License

Copyright (c) 2018 6tail

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 为什么不用在线接口

农历/节气/干支这类数据完全可以在本地算出来（`lunar.min.js` 就是纯计算，不联网）。
用在线接口会引入跨域、限流、可用性和授权问题，和本项目的静态约定冲突。
