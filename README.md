# umi-plugin-antd-theme-v2

> antd theme plugin

[![NPM version](https://img.shields.io/npm/v/umi-plugin-antd-theme-v2.svg?style=flat)](https://npmjs.org/package/umi-plugin-antd-theme-v2) [![NPM downloads](http://img.shields.io/npm/dm/umi-plugin-antd-theme-v2.svg?style=flat)](https://npmjs.org/package/umi-plugin-antd-theme-v2)

## Usage

```js
export default {
  antdTheme: {
    themes: [
      {
        key: "dust-red",
        fileName: "dust-red.css",
        modifyVars: {
          "@primary-color": "#f5222d",
        },
      },
      {
        key: "volcano",
        fileName: "volcano.css",
        modifyVars: {
          "@primary-color": "#fa541c",
        },
      },
      {
        key: "sunset-orange",
        fileName: "sunset-orange.css",
        modifyVars: {
          "@primary-color": "#fa8c16",
        },
      },
      {
        key: "calendula-gold",
        fileName: "calendula-gold.css",
        modifyVars: {
          "@primary-color": "#faad14",
        },
      },
      {
        key: "sunrise-yellow",
        fileName: "sunrise-yellow.css",
        modifyVars: {
          "@primary-color": "#fadb14",
        },
      },
      {
        key: "lime",
        fileName: "lime.css",
        modifyVars: {
          "@primary-color": "#a0d911",
        },
      },
      {
        key: "polar-green",
        fileName: "polar-green.css",
        modifyVars: {
          "@primary-color": "#52c41a",
        },
      },
      {
        key: "cyan",
        fileName: "cyan.css",
        modifyVars: {
          "@primary-color": "#13c2c2",
        },
      },
      {
        key: "daybreak-blue",
        fileName: "daybreak-blue.css",
        modifyVars: {
          "@primary-color": "#1890ff",
        },
      },
      {
        key: "geek-blue",
        fileName: "geek-blue.css",
        modifyVars: {
          "@primary-color": "#2f54eb",
        },
      },
      {
        key: "golden-purple",
        fileName: "golden-purple.css",
        modifyVars: {
          "@primary-color": "#722ed1",
        },
      },
      {
        key: "magenta",
        fileName: "magenta.css",
        modifyVars: {
          "@primary-color": "#eb2f96",
        },
      },
      {
        key: "dark-dust-red",
        theme: "dark",
        fileName: "dark-dust-red.css",
        modifyVars: {
          "@primary-color": "#f5222d",
        },
      },
      {
        key: "dark-volcano",
        theme: "dark",
        fileName: "dark-volcano.css",
        modifyVars: {
          "@primary-color": "#fa541c",
        },
      },
      {
        key: "dark-sunset-orange",
        theme: "dark",
        fileName: "dark-sunset-orange.css",
        modifyVars: {
          "@primary-color": "#fa8c16",
        },
      },
      {
        key: "dark-calendula-gold",
        theme: "dark",
        fileName: "dark-calendula-gold.css",
        modifyVars: {
          "@primary-color": "#faad14",
        },
      },
      {
        key: "dark-sunrise-yellow",
        theme: "dark",
        fileName: "dark-sunrise-yellow.css",
        modifyVars: {
          "@primary-color": "#fadb14",
        },
      },
      {
        key: "dark-lime",
        theme: "dark",
        fileName: "dark-lime.css",
        modifyVars: {
          "@primary-color": "#a0d911",
        },
      },
      {
        key: "dark-polar-green",
        theme: "dark",
        fileName: "dark-polar-green.css",
        modifyVars: {
          "@primary-color": "#52c41a",
        },
      },
      {
        key: "dark-cyan",
        theme: "dark",
        fileName: "dark-cyan.css",
        modifyVars: {
          "@primary-color": "#13c2c2",
        },
      },
      {
        key: "dark-daybreak-blue",
        theme: "dark",
        fileName: "dark-daybreak-blue.css",
        modifyVars: {
          "@primary-color": "#1890ff",
        },
      },
      {
        key: "dark-geek-blue",
        theme: "dark",
        fileName: "dark-geek-blue.css",
        modifyVars: {
          "@primary-color": "#2f54eb",
        },
      },
      {
        key: "dark-golden-purple",
        theme: "dark",
        fileName: "dark-golden-purple.css",
        modifyVars: {
          "@primary-color": "#722ed1",
        },
      },
      {
        key: "dark-magenta",
        theme: "dark",
        fileName: "dark-magenta.css",
        modifyVars: {
          "@primary-color": "#eb2f96",
        },
      },
      {
        key: "dark",
        theme: "dark",
        fileName: "dark.css",
        modifyVars: {},
      },
    ],
    options: {
      // 是否压缩css
      min: true,
      // css module
      isModule: true,
      // 忽略 antd 的依赖,用于打包 antd 自己的依赖
      ignoreAntd: false,
      // 忽略 pro-layout 的依赖
      ignoreProLayout: false,
      // 不使用缓存
      cache: true,
      filterFileLess: (filename) => boolean,
      extraLibraries: [],
    },
  },
};
```

you can get themes in `window.antd_themes`.

## LICENSE

MIT
