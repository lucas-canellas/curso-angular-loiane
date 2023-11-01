# Curso Angular Loiane

### Comandos
#### Instalando a CLI

```bash
  npm install -g @angular/cli
```

#### Gerar um novo projeto

```bash
  ng ng new nome-do-projeto
```

### Angular Material

#### Instalando o Angular Material

```bash
  ng add @angular/material
```

#### Exibir um componente

Vamos exibir um componente de alternância de slide em seu aplicativo e verificar se tudo funciona.

Você precisa importar o MatSlideToggle que deseja exibir adicionando as seguintes linhas a seu arquivo Moduleapp.module.ts.

```bash
  import { MatSlideToggleModule } from '@angular/material/slide-toggle';

  @NgModule ({
    imports: [
      MatSlideToggleModule,
    ]
  })
  class AppModule {}

```

Adicione a tag <mat-slide-toggle> ao app.component.html assim

```bash
  <mat-slide-toggle>Toggle me!</mat-slide-toggle>
```



