# PBI Visual Update not triggering when visual size is set to `Actual`

# Issue detail:
While switching to edit view from reading view visual update is not triggering when we have `visual size set to Actual`. Please find the pbiviz file in the repo.

Added a console in update function to check if the update is triggering. We need some update to tell the visual is in edit mode.

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


<!-- ## Package size comparison:

After building the visual check the webpack.statistic.html for bundle size of Formatting Utils.

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/webpack-stats.png)

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/with-formatting-utils.png)

Remove the getFormattedText() function from the visual.ts and check the bundle size of the visual.

![alt](https://github.com/manikandanvengatesan/pbi-formatting-utils-size-comparison/blob/main/assets/without-formatting-utils.png) -->
