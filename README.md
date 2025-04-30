# 🍀 Número da Sorte

## 🗒️ Descrição

O **Número da Sorte** é um aplicativo móvel desenvolvido como parte da disciplina _Software para Smartphone_, do curso de Engenharia Eletrônica e de Computação da UFRJ.  
O aplicativo tem como objetivo gerar números aleatórios que podem ser utilizados em sorteios, jogos, entre outros.

## 💡 Funcionalidades

- **Geração de Números Aleatórios**: permite ao usuário gerar números aleatórios entre 0 e 60.

## ⚙️ Tecnologias Utilizadas

- **Plataforma**: Android / iOS / Windows  
- **Linguagem de Programação**: C#  
- **Framework**: .NET MAUI

## 📱 Como Rodar o Aplicativo no Visual Studio

### Pré-requisitos

- Visual Studio 2022 (ou superior) com suporte ao **.NET MAUI**
- Android SDK instalado (para execução em emulador ou dispositivo Android)

### Passo a Passo

1. **Clone este repositório**

   ```bash
   git clone https://github.com/felipevascon/AppNumeroDaSorte
   cd AppNumeroDaSorte

2. **Abra o projeto no Visual Studio**  
   - Vá em `File > Open > Project/Solution`  
   - Selecione o arquivo `.sln` da solução  

3. **Restaure os pacotes NuGet**  
   - Caso esse passo não tenha sido executado de forma automática pelo Visual Studio, clique com o botão direito na solução e selecione **Restore NuGet Packages**.  

4. **Configure o dispositivo de execução**  
   - Na barra superior do Visual Studio, escolha o destino:  
     - `Windows Machine`  
     - `Android Emulator`  
     - `Dispositivo físico Android (Seu)`  

5. **Compile e execute o aplicativo**  
   - Pressione `F5` ou clique no botão **Start** (ícone ▶️).

## 🎥 Gravação da execução do app em um smartphone Android

[▶ **Vídeo Demonstração**](https://github.com/user-attachments/assets/1610b2dd-cb15-4fda-bd68-d1026d495af1)

## Screenshots das simulações em diferentes plataformas

### Windows

#### Passo 1 - Após o run no modo "Windows Machine" do Visual Studio 2022
![AppNumeroDaSorte-Windows](https://github.com/user-attachments/assets/dc36f8a5-3db0-4a70-9f01-121f9476f212)

#### Passo 2 - Após o uso do botão
![AppNumeroDaSorte-Windows2](https://github.com/user-attachments/assets/abe53726-9c10-4194-b19a-c7323e6685a2)

### Android

#### Tela 1 - Tela de carregamento do app
![AppNumeroDaSorte-Android1](https://github.com/user-attachments/assets/e6523153-864d-4abf-acfb-810a637dbc0f)

#### Tela 2 - Tela inicial do app
![AppNumeroDaSorte-Android2](https://github.com/user-attachments/assets/30b49629-a281-46c8-9b44-8e98b97f2549)

#### Tela 3 - Após o uso do botão
![AppNumeroDaSorte-Android3](https://github.com/user-attachments/assets/02badbea-30d6-488f-bb11-dcd93cade728)

#### Tela 4 - Caso o botão seja acionado novamente, nova sequência é gerada
![AppNumeroDaSorte-Android4](https://github.com/user-attachments/assets/bb87d5f9-90c6-42f7-91ac-301add852668)
