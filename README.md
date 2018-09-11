[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-prism-marked-element)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/LostInBrittanygranite-prism-marked-element.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-prism-marked-element)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LostInBrittany/granite-prism-marked-element)


# granite-prism-marked-element

> Based on Polymer 2.x

An element extending marked-element with encapsulated prism-element and prism-theme-default to be more easily used in non-polymer apps

See https://www.webcomponents.org/element/PolymerElements/marked-element for more info

## Usage example

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../polymer/polymer.html">
    <link rel="import" href="granite-prism-marked-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<granite-prism-marked-element >
    <script type="text/markdown">
        # Does it works?

        I am not sure! 

        Let's test

        ```html
        <div>There is no div here</div>
        <i>
            console.log('And no log');
        </i>
        ```

        **Yes it works!**
    </script>
</granite-prism-marked-element>
```


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.



## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT](https://opensource.org/licenses/mit)
