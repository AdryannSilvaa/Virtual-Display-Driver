<p align="center">
  <h1 align="center">Driver de Monitor Virtual</h1>
  <p align="center">
    Adicione monitores virtuais ao seu dispositivo com Windows 10/11!  
    <br />
    Funciona com VR, OBS, Sunshine e/ou qualquer software de compartilhamento de área de trabalho.  
    <br />
    Agora com um assistente de instalação fácil de seguir!
  </p>
</p>

<br>

## ℹ Sobre

Este projeto é baseado no projeto "Virtual Display Driver" e busca aprimorá-lo.

> Baseado no exemplo oficial de Driver de Exibição Indireta da Microsoft (Microsoft Indirect Display Driver Sample). Este driver cria um monitor virtual no Windows que se comporta exatamente como um monitor físico. É útil para streaming, realidade virtual, gravação de tela, servidores headless, etc. A vantagem sobre um monitor físico é a possibilidade de ajustar resoluções e taxas de atualização além das capacidades do hardware. Por exemplo, seria possível fazer streaming de um jogo em 8K a 240Hz mesmo possuindo apenas um monitor 1080p a 60Hz (exemplo irreal, mas ilustra o potencial). Em servidores sem tela, isso permite uso de Área de Trabalho Remota e streaming de tela como se houvesse um monitor instalado.

> Suporta emulação de resoluções de 640x480 até 7680x4320 (8K), e taxas de atualização como 60Hz, 75Hz, 90Hz, 120Hz, 144Hz, 165Hz, 240Hz, 480Hz e 500Hz.

> Este projeto utiliza o driver oficial de Exibição Indireta do Windows combinado com a extensão de classe `IddCx`.

Este projeto adiciona um **assistente de instalação fácil de seguir**, permitindo que você escolha quantos monitores virtuais deseja adicionar ao seu sistema, sem a necessidade de editar arquivos de configuração manualmente.

Espero que você goste deste projeto! Se gostar, deixe uma estrela no repositório ⭐😊

---

## 📥 Baixar Versão Estável

> ⚠️ **IMPORTANTE**
> Certifique-se de baixar a versão correta para o seu sistema operacional!

* [Windows 10 e 11 (sem HDR)](https://github.com/timminator/Virtual-Display-Driver/releases/tag/v1.0.1)
* [Windows 11 23H2+ (com HDR)](https://github.com/timminator/Virtual-Display-Driver/releases/tag/v1.0.1)

## 🔁 Baixar Versão Beta

* [Driver Universal - 24.10.27 (Windows 10/11)](https://github.com/timminator/Virtual-Display-Driver/releases/tag/24.11.01)

---

## ✅ Como usar:

1. Baixe a versão mais recente.
2. Execute o instalador e siga as instruções do assistente de instalação.

Isso é tudo! Um monitor virtual será adicionado ao seu sistema automaticamente!

---

## 📝 Observações

* Se o Windows Defender exibir um alerta ao executar o instalador, clique em **“Mais informações”** e depois em **“Executar assim mesmo”**.

---

## ⚙️ Observações adicionais sobre a criação do instalador

* O instalador não usa a versão mais recente do `nefconw.exe` porque a versão `v1.11.0` não desinstalava corretamente o driver.
  Em vez disso, a versão `v1.10.0` é utilizada durante a criação do instalador com o **Inno Setup**.
