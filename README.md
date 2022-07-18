# PBI Formatting Utils Size Comparison

This is the Power BI Visual repository for **PBI Formatting Utils Size Comparison**.

## build commands

For development, use

```bash
npm run start
```

For production build, use

```bash
npm run build
```

## ⚡️⚡️ Faster Compilation with `SWC`

The package also supports faster compilation using `swc` (rust based typescript/javascript compiler). Use the below commands for faster build times. Below are the reference commands for development and production usage. You will need to use node > `12.x.x`, npm >= `7.x`.

If someone face any issue pls use

```
npm i -D @swc/core @swc/cli
```

## Update not triggering issue:

When we switch to edit view from reading view visual update is not triggering when we have `view type set to Actual size`. Please find the pbiviz file in the repo.

<!-- ## Package size comparison:

After building the visual check the webpack.statistic.html for bundle size of Formatting Utils.

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/webpack-stats.png)

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/with-formatting-utils.png)

Remove the getFormattedText() function from the visual.ts and check the bundle size of the visual.

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/without-formatting-utils.png) -->
