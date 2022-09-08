# Vuetify browser reloadds

This is reproduction repo for `vite-plugin-vite` regrading browser reloads due to new object based style config.

## Steps

1. Run the project using `yarn dev` (_It will use `--force` to clean the cached dependencies_)
2. Visit the URL
3. Open the about page (😵‍💫 Browser reloads)

---

## Using old config

However, if we use old config `styles: 'expose'` then it works fine.

1. use `styles: 'expose'` in vite config for `vite-plugin-vuetify`
2. Run the project using `yarn dev` (_It will use `--force` to clean the cached dependencies_)
3. Visit the URL
4. Open the about page (_No reloads_)
