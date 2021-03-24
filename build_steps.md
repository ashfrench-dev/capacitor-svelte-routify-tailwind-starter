SONGRNG BUILD STEPS
===================

## Install Routify

https://routify.dev/guide/installation

    npx @roxi/routify init


## Install TailwindCSS

    npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
    npm i autoprefixer tailwindcss postcss-import cssnano svelte-preprocess postcss -D
    npx tailwindcss init

Config tailwind to work with routify

https://routify.dev/examples/use-tailwind-css


## Set up Capacitor

https://capacitorjs.com/docs/getting-started

    npm install @capacitor/core @capacitor/cli
    npx cap init

Follow prompts.
    
### Install Capacitor Electron

https://capacitor-community.github.io/electron/#/./getting-started/index

    npm i @capacitor-community/electron

### Set up platforms

    npx cap add @capacitor-community/electron
    npx cap add android (not done yet)
    npx cap add ios (not done yet)

### Electron dependencies

    cd electron
    npm install --save @types/fs-extra@9.0.7


## Install kivy

https://kivy.org/doc/stable/gettingstarted/installation.html

    python -m pip install --upgrade pip setuptools virtualenv
    python -m virtualenv kivy_venv
    kivy_venv\Scripts\activate
    python -m pip install kivy[base,media]


## Run app

Start server:

    npm run dev

Electron:

    npx cap open @capacitor-community/electron