# daniel-schmitz-react-extension-pack

Esta é uma forma que eu uso para ter profiles diferentes para cada tipo de configuração no VSCODE. Por exemplo, o `daniel-schmitz-react-extension-pack` traz apenas extensões do react,
então quando eu estou desenvolvendo em react eu desabilito todos os outros packs e deixo apenas este funcionando.

Esta extension pack nao está publicada no vscode, é necessário instalar o `vsce` e gerar um pack (arquivo vsix). Então, com o pack pronto, instalo ela. 

## install

```
npm install -g vsce
git clone https://github.com/Daniel-Schmitz-VSCode-Extension-Packs/daniel-schmitz-react-extension-pack.git
cd daniel-schmitz-react-extension-pack
vsce package
code --install-extension daniel-schmitz-react-extension-pack-0.0.1.vsix
```

