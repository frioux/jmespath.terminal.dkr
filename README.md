# JMESPath terminal Container

## Usage

```
docker run -it    \
  --user $(id -u) \
  frew/jpterm
```

(I tend to use a user for increased insulation against kernel vulnerabilities.)

## Description

This image contains everything you need to use [JMESPath
Terminal](https://github.com/jmespath/jmespath.terminal) without installing
python modules system-wide.
