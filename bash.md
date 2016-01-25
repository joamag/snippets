## Bash Snippets

### Patches

    diff -urN ${DIR}-orig ${DIR} > ${DIR}.patch
    patch -p1 < ${DIR}.patch

### Execute detached

    <command> < /dev/null &> /dev/null &
    <command> < /dev/null &> ~/<command>.log &
