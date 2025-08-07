# vpn
Para conseguir acessar sites restritos no seu computador usando seu celular como intermediário, você pode criar uma **VPN (Virtual Private Network)** pessoal. O processo envolve instalar um aplicativo de VPN no seu celular para que ele funcione como um servidor, e então configurar seu computador para se conectar a ele.

---

### Passo 1: Configure seu celular como um servidor VPN

A forma mais simples de fazer isso é usando um aplicativo que cria um **túnel HTTP** ou um **proxy SOCKS**. Esses aplicativos transformam seu celular em um servidor proxy, permitindo que outros dispositivos se conectem a ele para acessar a internet.

Você pode usar aplicativos como:
* **HTTP Injector**: Disponível para Android. Ele permite criar configurações de túnel HTTP ou SOCKS.
* **OpenVPN Connect**: Disponível para Android e iOS. Ele pode ser usado tanto para se conectar a servidores quanto para criar um.

#### Configurando o aplicativo (exemplo com o HTTP Injector):
1.  Instale o aplicativo no seu celular.
2.  Nas configurações, você precisará criar um arquivo de configuração (chamado de **payload**) que irá direcionar o tráfego da sua conexão de internet através do aplicativo.
3.  Inicie o servidor dentro do aplicativo para que ele comece a "escutar" por conexões.

---

### Passo 2: Conecte seu computador ao servidor VPN do celular

A próxima etapa é configurar o seu computador para usar o celular como o servidor proxy.

1.  **Obtenha o endereço IP do seu celular:** Verifique qual é o endereço IP do seu celular na rede em que ele está conectado.
2.  **Defina a porta de conexão:** Verifique nas configurações do aplicativo no celular qual a porta que ele está usando para o túnel.
3.  **Configure o navegador no computador:**
    * Vá para as configurações do seu navegador (Google Chrome, Firefox, etc.).
    * Procure pela seção de **proxy** ou **configurações de rede**.
    * Insira o endereço IP do seu celular e o número da porta nas configurações de proxy.

Ao fazer isso, todo o tráfego do seu navegador passará primeiro pelo seu celular, que está em uma rede diferente e sem as restrições que o computador tem. A partir daí, o tráfego será direcionado para os sites que você deseja acessar.

**Importante:** Essa é uma forma de contornar as restrições de forma temporária e não é a forma mais segura. Sempre tenha cuidado com as informações que você acessa.
