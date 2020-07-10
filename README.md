# acaochego
Site da ONG Acãochego

O site foi construído utilizando o padrão MVC com o framework 4.5. Criamos uma controller para cada página do site onde a view Index representa o html da respectiva página, a única exceção é a controller Materias que possui uma view para cada matéria e o redirecionamento para cada página de matéria é feito no HTML da view Index.

As seguintes bibliotecas externas (plugins) foram utilizados: 
JQUERY 
POPPER.JS 
BOOTSTRAP 
FONT-AWESOME

Esses plugins estão referenciados na página master (\Shared_Layout.cshtml) via CDN (via url), o ideal é que no projeto oficial a referência seja feita via pacote nuget para que haja maior integridade e controle de versão dos pacotes.
