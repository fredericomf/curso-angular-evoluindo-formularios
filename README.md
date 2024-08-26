# Angular: Evoluindo com formulários e roteamento
Repositório para o curso Alura - Angular: evoluindo com formulários e roteamento


### Remover versões anteriores do Angular:
```
npm uninstall -g @angular/cli
```

### Instalar a versão 14 do Angular:
```
npm install -g @angular/cli@17.0.0
```

### Instalar o projeto
```
npm install
```

### Inicializar o projeto
```
ng serve --open
```

### Nota:
Se você estiver no Linux é possível que a instalação do Angular Cli quebre o terminal, fazendo com que ele não carregue corretamente. Caso isso aconteça:

1. Edite o arquivo oculto **~/.bashrc**.
2. Remova a última linha do comando Angular: "source <(ng completion script)".
3. Salve o arquivo.


### Sobre Databinding

Data Binding é o processo pelo qual o Angular sincroniza os dados entre o modelo (a classe do componente) e a view (o template). Existem quatro formas principais de Data Binding no Angular:

1. Interpolação ({{ valor }}): usa-se para exibir propriedades da classe do componente no template.

2. Property Binding ([propriedade]="valor"): usa-se para vincular uma propriedade de um elemento HTML a uma propriedade da classe do componente.

3. Event Binding ((evento)="handler()"): permite ouvir eventos do DOM e reagir a eles na classe do componente.

4. Two-way Binding ([(ngModel)]="propriedade"): combina Property e Event Binding para criar uma via de mão dupla entre a classe e o template.

