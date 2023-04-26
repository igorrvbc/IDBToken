
IDBToken

Repositório para desenvolvimento de token na rede Goerli TestNet ETH .

Projeto realizado durante o bootcamp 'Formação Web3 Fundamentals'.

Descrição do Desafio

Neste Desafio você irá criar, a partir das instruções do Instrutor Ricardo Zago, um Token do zero. Para isso, é importante que você siga o passo a passo de configuração da Wallet Metamask e do RPC info. Posteriormente, a partir do código base e das instruções dos vídeos "Configurando Metamask" e "Criando o seu Token", você irá fazer as alterações necessárias utilizando a IDE REMIX e então fazer o deploy do seu Token.

Objetivo:

    Criar um novo repositório (sempre público) através do link https://github.com/new (acessível pelo site através do botão "+", depois "Novo repositório").

    Neste repositório, insira todos os arquivos relevantes para seu projeto. No caso, sugerimos que você adicione um arquivo com o código do seu Token. Além disso, seria extremamente importante a elaboração de um README contendo links úteis e imagens que evidenciem o sucesso da sua criação.

Links úteis:

https://metamask.io/
https://rpc.info/
https://remix.ethereum.org/

Resolução:

    Criação de Repositório no GitHub para alocar arquivos do projeto;

    Conectei a rede Sepolia Testnet;

    Resgatei faucets através do site "https://faucetlink.to/sepolia" para criação criação de token na rede Sepolia TestNet;

    Utilizei a IDE do site "https://remix.ethereum.org/" para editar os arquivos e desenvolver o TOKEN pensando em jogos IDB Coin;

    Criação do arquivo "token.sol" e edição das informações sobre 'endereço público' da carteira metamask;

    Em "Solidity compiler" clico em 'Compile token.sol' e aguardo a confirmação; compilerSolidity

    Na aba "Deploy & run transactions" seleciono o meu contrato criado que se chama 'IDBTOKEN - token.sol' na opção 'CONTRACT' e clico em 'Deploy' deploy run

OBS: O sucesso da operação pode ser observado no link "https://sepolia.etherscan.io/" introduzindo na barra do pesquisa a chave pública da carteira metamask do criador do token.

RESULTADO: IDB_token

TOKEN CRIADO !!!




REMIX DEFAULT WORKSPACE

Remix default workspace is present when:
i. Remix loads for the very first time 
ii. A new workspace is created with 'Default' template
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

1. 'contracts': Holds three contracts with increasing levels of complexity.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules.
For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin.
For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.
