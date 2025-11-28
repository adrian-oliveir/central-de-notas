central-de-notas
Este projeto é usado como um consolidador pessoal para organizar seu dia a dia.

Diagrama de entidade de relacionamento:

<img width="1241" height="761" alt="Diagrama sem nome drawio" src="https://github.com/user-attachments/assets/244cc299-2d66-4834-8d0c-71735544b370" />

diagrama de classes:

<img width="1500" height="975" alt="__dynobird com__2025-11-27 22_49_55" src="https://github.com/user-attachments/assets/eff51942-1196-4f25-93ce-5cfb25792adf" />

muckup1 login:

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 22-04-05" src="https://github.com/user-attachments/assets/0c96e567-26ac-4422-bbb6-c301db6d0609" />

muckup2 cadastro:

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 22-53-49" src="https://github.com/user-attachments/assets/a354004f-93e6-4e7b-aec5-fbfeb3f11998" />

muckup3

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 22-57-13" src="https://github.com/user-attachments/assets/b7e92f4e-6172-4209-9452-6b5e2303e351" />

muckup4

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 22-58-17" src="https://github.com/user-attachments/assets/e84edd57-3461-4d45-be1b-c8f197d4bdf8" />

muckup5 

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 22-59-24" src="https://github.com/user-attachments/assets/66aaf1e0-b1fb-436e-b5a1-3293e0001ef5" />

muckup6

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-00-05" src="https://github.com/user-attachments/assets/1a36b663-c1e4-4ae8-8b76-3af9f15d5f48" />

muckup7

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-00-50" src="https://github.com/user-attachments/assets/eb8f8bfb-2cae-43f5-8fb2-353a9caed0b9" />

muckup8

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-01-36" src="https://github.com/user-attachments/assets/2be59cd2-a01a-4930-a663-998930217044" />

muckup9

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-02-34" src="https://github.com/user-attachments/assets/19c7fc4e-38cd-4d94-8b14-9af31dee4c66" />

muckup10

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-03-14" src="https://github.com/user-attachments/assets/7ab209bf-ab94-46b6-9323-7eef2aca334c" />

muckup11

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-04-13" src="https://github.com/user-attachments/assets/349d1257-37cf-4a21-abd7-9feed491e323" />

muckup12

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-04-54" src="https://github.com/user-attachments/assets/5781bdc1-181a-4614-aea7-93af1b5dd769" />

muckup13

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-05-41" src="https://github.com/user-attachments/assets/34949fd4-7dea-4ae7-95e8-9499f276bbfd" />

muckup14

<img width="1362" height="644" alt="Captura de tela de 2025-11-27 23-08-23" src="https://github.com/user-attachments/assets/4ae6ee47-3d09-43d5-a306-c9b8ceaf4ce9" />

muckup15

<img width="1362" height="171" alt="Captura de tela de 2025-11-27 23-09-17" src="https://github.com/user-attachments/assets/c9f92f30-6faa-45f0-94da-94af9bf1b98d" />

relatorio: 

Relatório de Arquitetura Back-End - Consolidador Pessoal

🔥 Integração com Firebase

A Escolha Estratégica: Flask + Firebase

A decisão de utilizar Flask integrado com Firebase foi tomada para criar uma arquitetura que combina o melhor de ambos. Esta abordagem permite controle total sobre a lógica de negócio, aproveitando simultaneamente serviços geridos para funcionalidades complexas.

Porquê Esta Combinação Funciona Bem?

Para o Desenvolvimento:
O Flask oferece uma curva de aprendizagem suave e controle total sobre o código, enquanto o Firebase disponibiliza serviços prontos que poupam tempo de desenvolvimento. É como ter ferramentas manuais para trabalhos precisos e ferramentas automáticas para tarefas repetitivas.

Para a Experiência do Utilizador:
Os utilizadores terão uma aplicação com resposta rápida, atualizações em tempo real e sincronização entre dispositivos sem esforço. O Firebase garante que as alterações feitas num dispositivo aparecem instantaneamente nos outros.

Vantagens Práticas:

O Firebase gere a autenticação de utilizadores de forma segura e simples.

A base de dados Firestore oferece sincronização em tempo real gratuita.

O Flask mantém o controlo sobre cálculos financeiros complexos e relatórios.

A combinação reduz a necessidade de configurar servidores complexos.

Custo-Benefício:

O Firebase tem um nível gratuito generoso para projetos pequenos.

O Flask funciona em servidores simples e económicos.

Não é necessário configurar serviços separados para notificações push ou WebSockets.

💻 Explicação Detalhada do JavaScript
Como o JavaScript Foi Organizado
O JavaScript do projeto foi estruturado para ser mantido e eficiente, seguindo boas práticas de desenvolvimento front-end moderno.

Arquitetura de Pastas do JavaScript:
1. Sistema de Módulos:
O código está dividido em módulos especializados – um para finanças, outro para saúde, projetos, etc. Cada módulo trata apenas da sua área, como departamentos numa empresa, onde cada um tem a sua especialidade.

2. Comunicação com o Backend:
Foram criadas funções específicas para comunicar com a API do Flask. Em vez de espalhar código de comunicação por toda a aplicação, existe um serviço centralizado que faz todas as chamadas ao servidor.

3. Gestão de Estado:
O sistema mantém uma fonte central de dados com toda a informação da aplicação. Quando algo muda, todas as partes da interface que dependem dessa informação são atualizadas automaticamente.

4. Tratamento de Erros:
O código está preparado para lidar com problemas de rede ou respostas inesperadas do servidor, mostrando mensagens amigáveis ao utilizador sem bloquear a aplicação.

Fluxo de Funcionalidades:
Quando um utilizador adiciona uma transação:

O JavaScript recolhe os dados do formulário

Valida se estão corretos

Envia para o Flask por requisição HTTP

Atualiza a interface com a nova transação

Recalcula totais e progressos

Mostra confirmação ao utilizador

Para atualizações em tempo real:

O Firebase monitoriza alterações na base de dados.

Quando deteta uma alteração, notifica o JavaScript.

O JavaScript atualiza apenas a parte necessária do ecrã.

O utilizador vê a mudança instantaneamente.

Benefícios desta organização:
Manutenção fácil: Encontrar e corrigir problemas é simples, pois o código está bem organizado.

Adição de novas funcionalidades: É fácil acrescentar novas funções sem comprometer as existentes.

Performance: A aplicação responde rapidamente porque só atualiza o necessário.

Experiência do utilizador: Transições suaves e feedback imediato das ações.

Como isto se traduz para o utilizador final:
O utilizador percebe uma aplicação que:

Responde rapidamente aos seus cliques.

Mantém os dados sincronizados entre separadores e dispositivos.

Não perde dados mesmo com falhas de ligação.

Oferece uma experiência fluida e profissional.

Funciona igualmente bem em telemóvel e computador.

Esta arquitetura garante que o Consolidador Pessoal seja não só funcional, mas também agradável e fiável para uso diário.

<img width="1021" height="386" alt="Captura de tela de 2025-11-27 23-43-05" src="https://github.com/user-attachments/assets/c40e1118-c270-41bf-b5fc-ed6f2c5ac791" />


<img width="1021" height="386" alt="Captura de tela de 2025-11-27 23-45-21" src="https://github.com/user-attachments/assets/9bb81b63-bf21-43b4-973d-6ed8898884c9" />
