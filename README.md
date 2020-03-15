<h1 align="center">Atividades de Nivelamento - Linux</h1>
<p align="center">UNIVERSIDADE FEDERAL DO PARÁ</p>
<p align="center">COORDENADORIA DE SEGURANÇA DE INFORMAÇÃO E COMUNICAÇÃO</p>
<p align="center">
<img src="https://portal.ufpa.br/images/icones_portal/ufpa (2).png" height="70px">
<img src="https://csirt.ufpa.br/images/ctic1112.png" height="70px">
</p>
## Introdução

As atividades estão divididas em 3 partes, cada uma com a finalidade de desenvolver e testar suas habilidades na solução de problemas, que ~~sempre temos~~ venham a fazer o ambiente não funcionar da forma devida. Importante ressaltar que os sistemas sempre estão em desenvolvimento, e recomendamos fazer as atividades com suas versões mais recentes. A par disso, saiba que pode encontrar "tutoriais" que podem não satisfazer sua necessidade, por está defasado, e cabe a você encontrar a solução, nesses casos é interessante que comunique tais mudanças para atualizarmos nossa lista de atividades e procedimentos ~~em nossa área isso é de suma importância~~.

Depois de tanto sermão, **vamos ao que interessa**.

Na **parte 1**, requeremos um conhecimento básico sobre redes e ~~hypervisors~~ softwares de virtualização, recomendamos o [Virtualbox](https://www.virtualbox.org/) por sua simplicidade, eficiência e facilidade de operação.

Caso, já tenha conhecimento/prática sobre algum outro software do gênero use-o ~~tempo é dinheiro~~. No entanto saiba que nosso suporte, caso precise e envolva problemas com o software de virtualização é voltado ao virtualbox.

Na **parte 2**, vamos a instalação e configuração dos serviços nas 3 VMs.

- Servidor Web;
- Geração, compartilhamento e utilização de chaves assimétricas SSH/PGP;
- Compartilhamento de arquivos por NFS/SCP/RSYNC;
- Servidor de Logs;
- Servidor LDAP;

Na **parte 3**, utilização básica do sistema de controle de versões [git](https://git-scm.com/book/pt-br/v2/) e um serviço de hospedagem de código fonte ex: [github](https://github.com/), [gitlab](https://gitlab.com/).

As atividades estão ordenadas de forma que acreditamos ser mais fácil assimilar os conteúdos, sendo a posterior dependendo de um conhecimento adquirido na anterior, e por facilidade. No entanto, todas são igualmente importantes.

``Boa Sorte, e caso precise de ajuda não hesite em nos procurar.``

## Detalhamento das tarefas.

### Parte 1
1. Introdução a rede de computadores
   1. identificação de rede.
   2. máscara de rede.
   3. cálculo de hosts possíveis na rede.
   4. tipos de tradução de rede NAT, DNAT, SNAT.

2. Conexões de rede com o VirtualBox.
   1. Entender o funcionamento de conexões *host-only*, *bridge* e *nat*.

### Parte 2
3. Instalar/configurar uma VM com servidor web (apache ou nginx) - VM1.

4. Fazer acesso via SSH com key
   1. Entender o funcionamento do esquema de chaves assimétricas.

5. Para aqueles que ainda não possuem chave PGP criar uma e mandar um e-mail assinado e criptografado.
   - https://wiki.ctic.ufpa.br/index.php/Criar_e_publicar_chaves_PGP
   - https://wiki.ctic.ufpa.br/index.php/Enviando_e-mail_criptografado

6. Criar, na VM1, uma partição e formatar e compartilhar via NFS com a VM2.

7. Transferir arquivos via scp e rsync entre as VMs
   1. Entender o funcionamento desses métodos e suas aplicações.

8. Instalar/configurar uma VM com servidor de Logs syslog - VM3

9. Instalar/configurar uma VM com servidor openLDAP - VM2.

10. Configurar a VM3 para autenticar usuário ssh na base LDAP (VM2).

### Parte 3
1. Instalar o git na máquina física.

2. Gerar uma chave ssh e autenticar em um gerenciador de repositórios na nuvem (exemplo:gitlab)

3. Criar um repositório local e depois enviar para um gerenciador de repositórios na nuvem (exemplo:gitlab)

4. Criar arquivos (ex: .txt ou .html) dentro do repositório local e depois enviar para o gerenciador de repositório na nuvem.

5. Clonar, modificar e enviar as modificações o gerenciador. 
