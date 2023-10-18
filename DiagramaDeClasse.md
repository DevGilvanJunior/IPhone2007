## DIAGRAMA DE CLASSE IPHONE 2007

```mermaid
classDiagram
  class iPhone2007 {
    + ReprodutorMusical
    + AparelhoTelefonico
    + NavegadorInternet
  }
  class ReprodutorMusical {
    + tocar()
    + pausar()
    + selecionarMusica()
  }
  class AparelhoTelefonico {
    + ligar()
    + atender()
    + iniciarCorreioVoz()
  }
  class NavegadorInternet {
    + exibirPagina()
    + adicionarNovaAba()
    + atualizarPagina()
  }

  iPhone2007 --> ReprodutorMusical
  iPhone2007 --> AparelhoTelefonico
  iPhone2007 --> NavegadorInternet
