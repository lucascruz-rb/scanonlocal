# scanonlocal
.env => Configurar váriaveis de apontamento dos diretórios de PROJETOS e RELATÓRIOS
 -> Baixar imagem e subir aplicação
      `docker compose up -d`
 -> Aguardar e validar os logs dos containers
      -> Containers que ficarão no ar durante a execução
            Manager = Responsável por detectar a quantidade de projetos e subir N containers.
            scan_projetoN = Container temporário responsável pelo scan no projeto específicado (projetoN)

