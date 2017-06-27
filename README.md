# things-card

## List 형식으로 여러개의 card를 보여주고 상세정보를 클릭하여 보여주는 컴포넌트

Example:

```html
     <things-card-list
       items="[[items]]"
       selected="{{selectedItem}}">
     </things-card-list>
```

```html
     <things-img-card id="things-img-card"
       card="{{resource}}">
     </things-img-card>
```
*****
</br></br>

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-alarm/`, where `things-alarm` is the name of the directory containing it.
