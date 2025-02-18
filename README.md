# Math API

[![workflow-badge]][workflow-url]

[workflow-badge]: https://github.com/uetchy/math-api/workflows/test/badge.svg
[workflow-url]: https://github.com/uetchy/math-api/actions?workflow=test

Place LaTeX Math equation on anywhere as `<img>` tag.

- https://math.now.sh
- [Online Editor](https://math.now.sh/#online-editor)

## Usage

```
curl https://math.now.sh?from=\sum^{N}_{i}x_i
```

### HTML

```
<img src="https://math.now.sh?from=\log\prod^N_{i}x_{i}=\sum^N_i\log{x_i}" />
```

<img src="https://math.now.sh?from=\log\prod^N_{i}x_{i}=\sum^N_i\log{x_i}" />

```
<img src="https://math.now.sh?inline=\log\prod^N_{i}x_{i}=\sum^N_i\log{x_i}" />
```

<img src="https://math.now.sh?inline=\log\prod^N_{i}x_i=\sum^N_i\log{x_i}" />
    
### Markdown

```
![](https://math.now.sh?from=\LaTeX)
```

![Equation 1](https://math.now.sh?from=\LaTeX)

## Option

### **.svg** extension

URL ends with **.svg** extension will be treated as a normal math formula.

Some Markdown blog services won't treat image tags correctly whose URL has no any image extension in it. This option may give fixes to these situations.
