# fntToXml
This is a simple script.
Convert bitmap fonts.

fnt -> xml

## Instructions

```bash
git clone https://github.com/speaker73/fntToXml.git
npm -i
```

Then, copy the `FNT` bitmap font you want to convert in the root directory and run this on the command line:

```bash
node index.js fontFileName
```
(Note: The `.fnt` extension should be excluded)

You could also create a `/fonts` directory and copy FNT fonts into it. In that case, you would run something like this:

```
node index.js fonts/fontFileName
```



