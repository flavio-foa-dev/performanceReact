# performanceReact
React | componentes | performance

- Como funciona o JSX;
- O que é React.createElement;
- Como o React transforma os códigos JSX em objetos;
- O que é Virtual DOM;
- Como funciona uma estrutura React.
- O que é Reconciliation;
- O que é Imutabilidade e o que isto tem a ver com React;
- O que é memoização e como utilizar o React.memo;
- Como controlar com memo quando um componente deve atualizar ou não.


Dentro do vídeo sobre key, vimos passar bem despercebido a prop ref, e para que ela serve afinal?

A prop ref, assim como a prop key, é uma prop que não é reconhecida como prop no componente filho, e ela pode ser usada em qualquer elemento. Ao contrário do key, ela não é uma prop obrigatória, e sim uma prop opcional que pode ser utilizada a qualquer momento.

A palavra ref é uma abreviação de reference, ou referência em português, e ela serve exatamente para isso: fazer uma referência ao elemento real. Isso mesmo! Com o ref, você consegue acessar todos os atributos do DOM real dentro do React, como se estivesse utilizando o document.querySelector ou seletores parecidos!

Ref é uma arma poderosíssima para acessar o elemento diretamente, mas ela não é recomendada! O objetivo do React é abstrair o DOM e fazer tudo de forma declarativa, e o ref faz o exato oposto, agindo de forma imperativa.

Tá Luiz. Se você está me dizendo que não é recomendado, por que ele existe e por que eu usaria? Aí que está! Existem momentos em que ele é necessário, como por exemplo:

Quando precisamos dar foco a um elemento input;
Quando precisamos executar algo imperativo como forçar uma animação etc;
Quando precisamos reproduzir uma mídia ou um vídeo ou algo relacionado a isto (como o Picture-in-picture por exemplo);
Quando precisamos integrar o React com alguma biblioteca de terceiros e esta biblioteca exige imperatividade.

- O que é e para que serve a prop key;
- O que é a extensão React Developer Tools;
- Como utilizar a aba components da extensão;
- Como utilizar a aba profiler da extensão;
- Como avaliar se um componente está renderizando ou não utilizando a extensão.
- Como memoizar componentes de pacotes externos;
- Como analisar se um componente deve ser memoizado;
- A diferença entre memo e useMemo.
- O que é Lazy Loading;
- O que é Dynamic import;
- O que é Code splitting;
- Como utilizar o React.lazy.