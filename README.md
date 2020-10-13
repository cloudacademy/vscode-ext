# vscode-ext
Public host of `.vsix` files to use in the THEIA IDE Docker environments.

### How to add VSCode Extensions

You can lookup code extensions at the [Visual Studio Marketplace](https://marketplace.visualstudio.com/). You'll have to do some exploring for each project to find the `.vsix` file which is used to load the plugin into Theia. Upload the `.vsix` file into this repository.

Put the link in the `theiaPlugins` field of the `package.json` file:
```
"theiaPluginsDir": "plugins",
  "theiaPlugins": {
    "vscode-terraform": "https://github.com/cloudacademy/ca-theia-lab-env/raw/master/terraform/vscode-ext/joaompinto.vscode-graphviz-0.0.6.vsix",
```

