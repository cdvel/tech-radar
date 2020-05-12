# Tech Radar

Expanded from Zalando's [public Tech
Radar](http://zalando.github.io/tech-radar/) and [bgardan/techradar](https://github.com/bdargan/techradar) as a way to visualize technologies and how they shift within a developer's toolbox. The original idea comes from [ToughWorks' technology radar: an opiniated guide to technology frontiers](https://www.thoughtworks.com/radar)

Categories in this version are:
- Techniques & Practices
- Languages & Frameworks
- Platforms & Tools
- Data & Analytics

Adapt to your own datasource by updating `source` in [index.html](blob/master/docs/index.html) with your own csv file.
```
label, quadrant, description, ring, active, moved, link
```

![](https://res.cloudinary.com/cdvel/image/url2png/https://cdvel.github.io/tech-radar)

## Development

```
yarn
yarn start
```

## Dependencies

[D3.js](https://github.com/d3/d3)


## Original License
```
The MIT License (MIT)

Copyright (c) 2017 Zalando SE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
