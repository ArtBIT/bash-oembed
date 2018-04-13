# Bash oEmbed Consumer
[![Build Status](https://travis-ci.org/ArtBIT/bash-oembed.svg)](https://travis-ci.org/ArtBIT/bash-oembed) [![GitHub license](https://img.shields.io/github/license/ArtBIT/bash-oembed.svg)](https://github.com/ArtBIT/bash-oembed) [![GitHub stars](https://img.shields.io/github/stars/ArtBIT/bash-oembed.svg)](https://github.com/ArtBIT/bash-oembed)  [![awesomeness](https://img.shields.io/badge/awesomeness-maximum-red.svg)](https://github.com/ArtBIT/bash-oembed)

This is a small bash script that tries to determine the correct oEmbed provider depending on the given URL, and then makes a cURL request to their endpoint and returns the response.

# Installation
```
git clone https://github.com/ArtBIT/bash-oembed.git
```

# Usage

```
./oembed https://youtu.be/dQw4w9WgXcQ

```

NOTE: You can pipe the result to a JSON processor like [jq](https://github.com/stedolan/jq):
```
./oembed https://youtu.be/dQw4w9WgXcQ | jq .title

```

# License

[MIT](LICENSE.md)
