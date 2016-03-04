#OI-FRONT-END TEST



###Exercício A : HTML e CSS
Utilizando-se do _workflow_ e _tools_ que quiser, crie uma página em HTML a partir do layout do arquivo [oi-frontend-test.pdf](./test-assets/oi-frontend-test.pdf)

A página deve ter as seguintes características:

* a imagem em background deve ocupar 100% da tela do browser, e o rosto do rapaz, assim como o logotipo, devem estar sempre aparecendo, não importando a largura do browser (layout responsivo);

*  o botão **[ SAIBA MAIS ]** deve fazer um _toggle_ de visibilidade no logotipo;

As fontes utilizadas no layout, assim como o logo e a imagem de background, estão na pasta [test-assets](./test-assets)




###Exercício B : JavaScript

####1. Considere o código abaixo:

```JS
(function() {
  'use strict';
  var a = b = 5;
})();

console.log(b);
```

a. O que será mostrado no console ?

b. O que será mostrado no console se retirar a linha `'use strict';` ?



####2. Qual é o resultado do código abaixo, e por que ?

```JS
function test() {
   console.log(a);
   console.log(foo());
   
   var a = 1;
   function foo() {
      return 2;
   }
}

test();
```


####3. Qual é o resultado do código abaixo? Explique sua resposta.

```JS
var fullname = 'Nestor';
var obj = {
   fullname: 'Sergio',
   prop: {
      fullname: 'Luiz',
      getFullname: function() {
         return this.fullname;
      }
   }
};

console.log(obj.prop.getFullname());

var test = obj.prop.getFullname;

console.log(test());
```
