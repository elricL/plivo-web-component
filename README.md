# &lt;Plivo Web Component&gt;

> A bare minimum plivo custom element starter-kit using [Polymer](http://www.polymer-project.org/).
>
> Looking for a working example? Check [hello-world-polymer](https://github.com/webcomponents/hello-world-polymer).

## Demo

[Check it live!](http://elricl.github.io/plivo-web-component)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install plivo-web-component --save
```

Or [download as ZIP](https://github.com/elricL/plivo-web-component/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/plivo-web-component/dist/plivo-web.html">
    ```

3. Start using it!

    ```html
    <plivo-web></plivo-web>
    ```

## Options

Attribute          | Options     | Default      | Description
---                | ---         | ---          | ---
`username`         | *string*    | `""`         | Endpoint Username.
`password`         | *string*    | `""`         | Endpoint Password

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---

## Events

Event         | Description
---           | ---

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/elricl/plivo-web-component/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
