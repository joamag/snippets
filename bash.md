## Bash Snippets

### Patches

    diff -urN ${DIR}-orig ${DIR} > ${DIR}.patch
    patch -p1 < ${DIR}.patch
