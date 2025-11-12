```
#init
dir_local/
├── .env
│   └── Configurar váriaveis de apontamento dos diretórios de PROJETOS e RELATÓRIOS    
│   └── Garantir que os projetos a serem escaneados estão no diretório de PROJETOS configurado no .env.
├── Baixar imagem e subir aplicação
│   └── docker compose up -d
└── Aguardar e validar os logs dos containers
    └── Containers que ficarão UP durante a execução
        ├── manager = Responsável por detectar a quantidade de projetos e subir/derrubar N containers.
        └── scan_projetoN = Container temporário responsável pelo scan no projeto específicado (projetoN)
          ⚠️ A quantidade de containers UP estará de acordo com a quantidade de projetos adicionados no diretório de PROJETOS (configurado no .env)
          projetos_dir/
          ├── projeto1
          └── projeto2
          containers/
          ├── manager
              ├── scan_projeto1
              └── scan_projeto2
```

