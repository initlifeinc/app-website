# InitLife apps website

Static product showcase at https://app.initlife.com/.

Exported with history from the `dist/` directory of `initlifeinc/initlife`, branch `app_webpage`, source commit `64af5cda08da77c666de44987f3265ae3c02911f`.

The repository root is the published site. GitHub Pages uses `main` at `/`; `.nojekyll` keeps assets static and `CNAME` declares `app.initlife.com`. No build or external scripts are required.

Preview: `python3 -m http.server 4181`.

The parent InitLife repository includes this repository at `app-website/` as a Git submodule. After changes, commit and push here, then commit the updated submodule pointer in the parent repository. Personal homepage: https://initlife.com/.
