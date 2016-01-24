# `npm` Front-End Starter

If you're starting a front-end project, and would like to use `npm`, you can
give this repository a start. It's a slim project that uses `npm` features to
leverage the `npm` package manager to get started on a front-end project. This
repository is most useful to you if you want to reliably test any front-end
focused `npm` packages within a simple `npm` project.

## Installation

```
    git clone https://github.com/rogeruiz/npm-front-end-starter.git
    cd npm-front-end-starter
    npm install
    # Followed by any other npm packages you'd like to test
    # npm install --save jquery politespace @18f/private-eye tooltipster
```

### Developing / Testing

I recommend using the `python -m SimpleHTTPServer` module that allows you to
turn any directory you're terminal is in into a tiny web-server. You can use the
following command after following the previous steps.

```
    python -m SimpleHTTPServer
```

Once the server is running, it will be available at [`http://127.0.0.1:8000`](http://127.0.0.1:8000)
and you can then edit the `assets/src.js` and `assets/style.scss` files to
ingest projects from `npm`. Once you've edited those files to your choosing, you
can rebuild them with `npm run build` using `browserify` and `node-sass` to
build the JavaScript and Sass files respectively. You may edit the `build`
command by looking under `scripts` in the `package.json` file.

## Useful tips

While this project isn't set out to teach beginners how to use `npm` explicitly,
since the code should be able to do that more implicitly, this space will
contain some helpful advice on how to use this project with popular `npm`
libraries. More information on this will be coming soon.
