# things-card

## 이는 List 형식으로 여러 개의 card를 보여주고, 상세정보를 클릭하여 보여주는 컴포넌트이다.

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

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-card`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-card/`를 통해 이를 미리 확인할 수 있다. 
