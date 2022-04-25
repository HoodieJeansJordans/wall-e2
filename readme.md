# project robotrun software

- [link naar robot productpagina](https://www.pololu.com/product/975/resources)
- [link naar wixel productpagina](https://www.pololu.com/product/1336/resources)

## make gedoe

deze commando's kun je uitvoeren op de command-line als je alle build tools
goed geïnstalleerd hebt. er hoort ook een configuratie te zijn voor visual
studio code. hievoor moet je de [makefile tools
extensie](https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools)
installeren.

```sh
make                    # build
make flash              # upload executable to robot
make clean              # clean working directory
make format             # format source and header files
make compile_commands   # generate compile_commands.json (clangd)
```

