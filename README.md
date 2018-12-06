## Guia de Instalação do Angular2

[edite este documento no GitHub](https://github.com/rcadecaro/docblock-angular/edit/master/README.md)

### Instalação com npm

Para instalar o angular rode o seguinte comando

```markdown
> npm install -g @angular/cli

> ng version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 7.1.1
Node: 10.9.0
OS: linux x64
Angular: 
... 

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.11.1
@angular-devkit/core         7.1.1
@angular-devkit/schematics   7.1.1
@schematics/angular          7.1.1
@schematics/update           0.11.1
rxjs                         6.3.3
typescript                   3.1.6

```
Caso esteja em um projeto desatualizado rode o comando apra ver as atualizações possíveis:
```markdown
> ng update
```

A atualização somente ocorre com o parametro all. Verifique o package.json
Rode o comando duas vezes.
```markdown
> ng update --all
```

### Criando um novo projeto
A ferramenta ng cria uma nova estrutura do projeto com o seguinte comando
```markdown
> ng new angular-teste

? Would you like to add Angular routing? No
? Which stylesheet format would you like to use? 
SASS   [ http://sass-lang.com]

CREATE angular-teste/README.md (1029 bytes)
CREATE angular-teste/angular.json (3922 bytes)
CREATE angular-teste/package.json (1312 bytes)
CREATE angular-teste/tsconfig.json (435 bytes)
CREATE angular-teste/tslint.json (2824 bytes)
CREATE angular-teste/.editorconfig (246 bytes)
CREATE angular-teste/.gitignore (576 bytes)
CREATE angular-teste/src/favicon.ico (5430 bytes)
CREATE angular-teste/src/index.html (299 bytes)
CREATE angular-teste/src/main.ts (372 bytes)
CREATE angular-teste/src/polyfills.ts (3234 bytes)
CREATE angular-teste/src/test.ts (642 bytes)
CREATE angular-teste/src/styles.sass (80 bytes)
CREATE angular-teste/src/browserslist (388 bytes)
CREATE angular-teste/src/karma.conf.js (980 bytes)
CREATE angular-teste/src/tsconfig.app.json (166 bytes)
CREATE angular-teste/src/tsconfig.spec.json (256 bytes)
CREATE angular-teste/src/tslint.json (314 bytes)
CREATE angular-teste/src/assets/.gitkeep (0 bytes)
CREATE angular-teste/src/environments/environment.prod.ts (51 bytes)
CREATE angular-teste/src/environments/environment.ts (662 bytes)
CREATE angular-teste/src/app/app.module.ts (314 bytes)
CREATE angular-teste/src/app/app.component.sass (0 bytes)
CREATE angular-teste/src/app/app.component.html (1120 bytes)
CREATE angular-teste/src/app/app.component.spec.ts (999 bytes)
CREATE angular-teste/src/app/app.component.ts (218 bytes)
CREATE angular-teste/e2e/protractor.conf.js (752 bytes)
CREATE angular-teste/e2e/tsconfig.e2e.json (213 bytes)
CREATE angular-teste/e2e/src/app.e2e-spec.ts (305 bytes)
CREATE angular-teste/e2e/src/app.po.ts (204 bytes)
```

Para rodar um servidor web de teste do projeto rode o seguinte comando
```markdown
> cd projeto
> ng serve
** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **
 10% building modules 0/1 modules 1 active ...grant/vm/code/angular-teste/src/ma 10% building modules 1/2 modules 1 active 92% after chunk asset optimization SourceMapDevToolPlugin styles.js generate So 92% after chunk asset optimization SourceMapDevToolPlugin vendor.js generate So 92% after chunk asset optimization SourceMapDevToolPlugin main.js attach Source 92% after chunk asset optimization SourceMapDevToolPlugin polyfills.js attach S 92% after chunk asset optimization SourceMapDevToolPlugin runtime.js attach Sou 92% after chunk asset optimization SourceMapDevToolPlugin styles.js attach Sour 92% after chunk asset optimization SourceMapDevToolPlugin vendor.js attach Sour                                                          
Date: 2018-12-06T21:31:42.569Z
Hash: 4283074660892983475098237409e92416360552d989c
Time: 8366ms
chunk {main} main.js, main.js.map (main) 9.83 kB [initial] [rendered]
chunk {polyfills} polyfills.js, polyfills.js.map (polyfills) 223 kB [initial] [rendered]
chunk {runtime} runtime.js, runtime.js.map (runtime) 6.08 kB [entry] [rendered]
chunk {styles} styles.js, styles.js.map (styles) 16.7 kB [initial] [rendered]
chunk {vendor} vendor.js, vendor.js.map (vendor) 3.43 MB [initial] [rendered]
Compiled successfully.

```







Lembre-se
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
```
