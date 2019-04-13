Programming Fonts
================

Test drive programming fonts [online in your browser](https://app.programmingfonts.org/).

# Schema validation

```bash
ajv -s fonts-schema.json -d fonts.json
```

# Compiling stylesheets

```bash
cd fonts/stylesheets/ && lessc fonts.less stylesheet.css
```
