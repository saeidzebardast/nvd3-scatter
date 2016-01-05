# &lt;nvd3-scatter&gt; [![Build Status](https://travis-ci.org/saeidzebardast/nvd3-scatter.svg?branch=master)](https://travis-ci.org/saeidzebardast/nvd3-scatter)

Scatter chart element for [Polymer](https://www.polymer-project.org) using [nvd3](http://nvd3.org/). It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install

```
bower install nvd3-scatter
```

## Usage

### Tag

```
<nvd3-scatter data="[[data]]" auto-resize></nvd3-scatter>
```

### Data Format

```
[
  {
    "key": "Group One",
    "values": [
      {
        "x": 10,
        "y": 20,
        "size": 69
      }, {
        "x": 15,
        "y": 19,
        "size": 85
      }
    ]
  },
  {
    "key": "Group Two",
    "values": [
      {
        "x": 14,
        "y": 17,
        "size": 85
      }, {
        "x": 33,
        "y": 12,
        "size": 69
      }
    ]
  }
]
```

## License

MIT © [Saeid Zebardast](http://zebardast.com)
