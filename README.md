# Docpad boilerplate

[Docpad](https://docpad.org/)を使った静的/動的Webページ製作用のテンプレート

## Environment

- Node 10.13.0
- NPM 6.7.0
- docpad 6.82.5

## Installation

```
git clone https://github.com/arsley/docpad-boilerplate.git
npm i
```

## Usage

```shell
# watching file change and browser reload
npm start
```

## Structure

```
.
├── README.md
├── docpad.js
├── package-lock.json
├── package.json
└── src
    ├── documents
    │   ├── scripts          # Your JS here
    │   └── styles           # Your stylesheets here
    ├── layouts
    │   └── default.html.eco # Default layout
    ├── pages                # Your pages (.html, .html.eco) here
    └── static
        ├── images           # Your images here
        └── vendor           # Another libraries here (e.g. jquery.min.js, bootstrap.min.css etc.)
```

## Attention

- `npm start` をしても `Cannot get /` と表示される場合
  - `*.html` (表示させたいHTML)を変更・保存すると再読み込みがされます
