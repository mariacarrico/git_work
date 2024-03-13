# PROJETO FINAL GIT

## Descrição do Projeto 

O projeto final foi desenvlovido pelo grupo 3, constituido por 2FURR Brás, 2CAB Costa e 2CAB Carriço, foi uma prática colaborativa entre Git e GitHub, focado bo controlo de versões e trabalho em equipa. Desenvolvemos e aprimoramos um script Python no repositório git_work, onde foram aplicadas técnicas como merges, rebase, cherry-pick, e uso de tags.

## Objetivos do Projeto

- Aplicar técnicas de Git/GitHub para desenvolvimento colaborativo.
- Praticar operações chave do Git, como merges, rebase e cherry-picks.
- Aprofundar habilidades de resolução de conflitos e trabalho em equipe.
- Contribuir para um projeto comum, enfatizando a importância da comunicação eficaz.

## Processo de Desenvolvimento

### Costa Work-Flow

### Create Repo
Inicialmente foi criado um repositório no GitHub com o nome de git_work com a finalidade de conjugar todas as ações do nosso projeto.

![create_repo](https://github.com/nooblord26/git_work/assets/162144349/d1cc78fa-6382-4e10-9d19-3a3dd08a151a)

### Create 2 files
Foram criados dois ficheiros onde que por sua vez foram utilizados para a realização do projeto ( README.md e script.py).

![files](https://github.com/nooblord26/git_work/assets/162144349/227d9908-d98c-4e59-a785-6913a9cf79cb)

### Clone
Foi feito o Clone do repositório para podermos trabalhar localmente

![git_clone](https://github.com/nooblord26/git_work/assets/162144349/7850ea55-bf26-454d-8878-b798d6637eb2)

Foram criadas 3 branches para trabalho, costa_branch, costa_merge, costa_rebase

### Costa_branch

![branch_costa](https://github.com/nooblord26/git_work/assets/162144349/4a7053db-471c-4421-aab1-04fa5b258e51)

### Costa_merge

![branch_merge](https://github.com/nooblord26/git_work/assets/162144349/47961c8b-d4ab-4f0c-bb5c-9251d69563f3)

### Costa_rebase

![branch_rebase](https://github.com/nooblord26/git_work/assets/162144349/f5a9f534-1108-405b-94c6-7761a25be92f)

### Merge
O merge foi feito na costa_branch através de uma alteração no ficheiro script.py e um commit na branch costa_merge, onde depois foi feito o checkout para a costa_branch e o merge da costa_merge.

![commit_merge](https://github.com/nooblord26/git_work/assets/162144349/761a4ad9-2698-4d30-89a3-26ddbe4a136b)

![merge_done](https://github.com/nooblord26/git_work/assets/162144349/563411ca-d779-4c92-9ddb-19863703fc88)

### Rebase
O rebase foi feito na costa_branch através de uma alteração ficheiro script.py e um commit na branch costa_rebase, onde depois foi feito o checkout para a costa_branch e o rebase da costa_rebase.

![rebase_done](https://github.com/nooblord26/git_work/assets/162144349/f9bf1468-d015-45df-ad99-c181b2a5734a)

### Cherry-pick
Foram adicionados mais 2 commits na branch costa_rebase on foram adicionadas novas linhas ao script.py, em seguida foi feito checkout para a branch costa_branch e foi feito o cherry-pick de um dos commits feitos.

![create_commits_cherrypick](https://github.com/nooblord26/git_work/assets/162144349/6b0e5169-8059-4e10-8007-f8a786847068)

![cherrypick_done_conflit](https://github.com/nooblord26/git_work/assets/162144349/c27c3ff4-4e06-4a50-b1c9-1ba54eb6b337)

![conflit_correction](https://github.com/nooblord26/git_work/assets/162144349/ebae3efd-4934-4574-8b14-e4e396a7acfa)


### Tags
Foram criadas tags para realizar o controlo das versões ao longo do projeto, as versões foram numeradas de 0.1 a 1, com um intervalo entre 0.6 e 1 pois 1 é a versão final

![first_tag](https://github.com/nooblord26/git_work/assets/162144349/f4315ae6-f84d-4dd0-a39c-8cbbd3b9b0c9)

![all_tags](https://github.com/nooblord26/git_work/assets/162144349/8239d2a8-71aa-4109-b2cb-e94003429f4f)

![push_tags](https://github.com/nooblord26/git_work/assets/162144349/44331d48-48b6-4457-8f75-442364f5a20f)

### Pull-Requests
Teve de ser feito pull-requests sempre que os camaradas quiseram atualizar os seus repositorios locais.

![pullrequest_merged](https://github.com/nooblord26/git_work/assets/162144349/ae5e82c0-a7d6-465a-a482-e21491cb7143)

![pullrequest_merged_carrico](https://github.com/nooblord26/git_work/assets/162144349/a93a6485-d54d-4164-8f5d-84faf02b9033)

### Final version
![final_ver](https://github.com/nooblord26/git_work/assets/162144349/196548eb-2ee6-4d9f-897a-2b9330339967)

## Brás work-flow

### Fork
Após a criação do repositório "git_work" foi feito um Fork para possibilitar o trabalho no mesmo localmente.


### Clone
Após a criação do Fork foi feito um clone do repositório.

![Print1_Bras_git](https://github.com/xiribi-astrolabio/git_work/assets/162144401/6674661e-8c69-4dc9-9cd1-fa8723ce3eda)

### Branch
Para o trabalho foram criadas 3 branches, bras, bras_merge e bras_rebase

###Branch bras

![Print2_Bras_git](https://github.com/xiribi-astrolabio/git_work/assets/162144401/807c90b5-62a4-4cce-a90d-e24b40828213)


###Branch bras_merge
Esta branch foi criada para a alteração do ficheiro script.py para posteriormente fazer merge desta branch com a branch "bras"


![merge](https://github.com/xiribi-astrolabio/git_work/assets/162144401/f5f68278-fdc6-436d-a686-c44930824b0a)



###Branch bras_rebase
Esta branch foi criada para a alteração do ficheiro script.py para posteriormente fazer rebase com a branch "bras"


![rebase](https://github.com/xiribi-astrolabio/git_work/assets/162144401/7a9809f7-e228-4761-9a0a-4241100092d4)




###Cherry-Pick
Para o Cherry-Pick foram adicionadas linhas ao ficheiro script.py e realizados 2 commits, após os commits foi feito o Cherry-Pick de um deles através da branch "bras"


![cherry-pick](https://github.com/xiribi-astrolabio/git_work/assets/162144401/822953bb-a2d3-4967-b956-b2c281395c6a)



###Pull-Request
Após o término de todos os exercícios, foi feito um Pull-Request de forma a fazer "push" de todas as alterações feitas.



![pull_request](https://github.com/xiribi-astrolabio/git_work/assets/162144401/f7d36b2e-9c82-4116-8758-32d606f10b66)

## Carriço Work-Flow

##Fork
Após ter sido criado o repositório "git_work" foi feito um Fork para podermos trabalhar no mesmo localmente.


### Clone
Depois fizemos um clone do repositório "git_work".

![1clone](https://github.com/nooblord26/git_work/assets/162144506/edbe9178-73d0-4d41-9497-e80393ad5e49)

### Branch
Para o trabalho foram criadas 3 branches: carrico, carrico_merge e carrico_rebase.

### Branch carrico

![branch](https://github.com/nooblord26/git_work/assets/162144506/59e7a0c6-26e2-439a-8831-9b06e01eee75)

### Branch carrico_merge
Esta branch foi criada para alterar o ficheiro "script.py" para que posteriormente fosse possível fazer merge desta branch com a branch "carrico".


![git merge](https://github.com/nooblord26/git_work/assets/162144506/3f6aed97-c5ef-4aff-91f0-3b3107d0790d)


### Branch carrico_rebase
Esta branch foi criada para alterar o ficheiro "script.py", de modo a que posteriormente fosse possível fazer rebase com a branch "carrico".


![gitrebase](https://github.com/nooblord26/git_work/assets/162144506/fb99281e-297c-44fd-b765-76727349ddf7)


### Cherry-Pick
Para o Cherry-Pick foram adicionadas linhsa ao ficheiro "script.py" e realizados 2 commits, após os este commits terem sido feitos foi feito um Cherry-Pick de um deles através da branch "carrico".

![dcherrypick](https://github.com/nooblord26/git_work/assets/162144506/5b3b6973-be18-4b2d-81e2-b8b521d5197b)

###Pull-Request
Quando terminamos todos os exercícios, fizemos um Pull-Request de forma a fazer "push" de todas as alterações que foram feitas.

![pull_request](https://github.com/nooblord26/git_work/assets/162144506/398d6171-b93d-4db5-8798-9e625a43d270)


## Reflexões sobre o Processo de Colaboração e Aprendizagem
Este projeto foi uma oportunidade valiosa para o gripo 3 praticar o controlo de versões. Foram enfrentados desafios, especialmente na resolução de conflitos, mas o mais importante foi a comunicação entre os membros do grupo e a utilizar recursos do Git para encontrar soluções. A conclusão que retiramos deste projeto é a mais valia que o GIT traz para a gestão e organização de um projeto em grande escala.










