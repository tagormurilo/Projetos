# **Fazendo uma Pequisa Cognitiva no Azure**

## Criando um serviço de pesquisa

1. Entre na página da Azure e coloque seu e-mail e senha;

2. Após logado, no painel inicial procure por **Mais serviços** ou vá na lupa e pesquise por **IA+Machine Learning**;
![pagina inicial](images/Laz1)

3. Você será direcionado para página de **Todos os serviços** usando a primeira forma, clique no filtro **Tudo** e procure por **IA+Machine Learning**, vá no segundo filtro e pesquise **Serviço de Pesquisa**, selecione o mesmo;

4. Ao ser direcionado pra pagina de **Serviço de Pesquisa**, selecione criar

5. Você necessitará fazer algumas configurações, primeiro em Detalhes do projeto, coloque sua **Assinatura** e o **Grupo de recursos**, onde queres deixar o novo recurso;
![detalhes do projeto](images/Sch1)

6. Em **Detalhes da instância**, escrever um **Nome**, vamos escolher a **Localização** e por fim colocar o **Tipo de preço**, *nesta etapa caso esteja fazendo um teste coloque a opção **Gratuito***, preenchido selecione **Revisa + criar**;
![detalhes da_instancia](images/Sch2)
![nome](images/Sch2.1)
![localiza](images/Sch2.2)
![tipo_preco](images/Sch2.3)

7. Vá até o fim da pagina e selecione **Criar**;
![Criar](images/Sch3)

8. Será executado uma validação dos dados;

9. Após a validação concluída será redirecionado para pagina de inicialização do recurso, aguarde até ser redirecionado para pagina dos recursos e pronto é só utilizar este recurso.

## Criando um serviço cognitivo

1. No painel inicial procure por **Mais serviços**;
![pagina inicial](images/Laz1)

2. Você será direcionado para página de **Todos os serviços** usando a primeira forma, vá no segundo filtro e pesquise **Serviços Cognitivos**, selecione o mesmo;

3. Ao ser direcionado pra pagina de **Serviços Cognitivos**, selecione criar

4. Você necessitará fazer algumas configurações, primeiro em Detalhes do projeto, coloque sua **Assinatura** e o **Grupo de recursos**, onde queres deixar o novo recurso;
![detalhes do projeto](images/Sch4)

5. Em **Detalhes da instância**, vamos escolher a **Região**, escrever um **Nome** e por fim colocar o **Tipo de preço**, *nesta etapa caso esteja fazendo um teste coloque a opção **S0***, após ler os termos, selecione acaixa, então selecione **Exminar + criar**;
![detalhes da_instancia](images/Sch5)
![preco](images/Sch5.1)
![examinar](images/Sch5.2)

7. Vá até o fim da pagina e selecione **Criar**;

8. Será executado uma validação dos dados;

9. Após a validação concluída será redirecionado para pagina de inicialização do recurso, aguarde até ser redirecionado para pagina dos recursos e pronto é só utilizar este recurso.

## Criando uma conta de armazenamento

1. No painel inicial procure por **Mais serviços**;
![pagina inicial](images/Laz1)

2. Você será direcionado para página de **Todos os serviços** usando a primeira forma, vá no segundo filtro e pesquise **Conta de armazenamento**, selecione o mesmo;

3. Ao ser direcionado pra pagina de **Conta de armazenamento**, selecione criar

4. Você necessitará fazer algumas configurações, primeiro em Detalhes do projeto, coloque sua **Assinatura** e o **Grupo de recursos**, onde queres deixar o novo recurso;
![detalhes do projeto](images/Sch6)

5. Em **Detalhes da instância**, escrever um **Nome**, vamos escolher a **Região**, colocar o **Tipo de preço**, *nesta etapa caso esteja fazendo um teste coloque a opção **Standart***, em **Redundâcia**, selecione **LRS**, então selecione **Exminar + criar**;
![detalhes da_instancia](images/Sch7)
![preco](images/Sch7.1)

7. Vá até o fim da pagina e selecione **Criar**;

8. Será executado uma validação dos dados;

9. Após a validação concluída será redirecionado para pagina de inicialização do recurso, aguarde até ser redirecionado para pagina dos recursos e pronto é só utilizar este recurso.

## Configurando e Carregando a Conta de Armazenamento

1. Vá até seu grupo de recursos e entre na sua conta de armazenamento criada;

2. Role a pagina para baixo ou vá em configurações;

3. Para a primeira opção ache **Acesso anônimo ao blob** e siga o passo abaixo;
![ache](images/Sch8)

4. Para a segunda opção pule o passo anterior e siga apenas este, marque a caixa de **Habilitado** e **Salvar**, para manter a mudança, *lembrando que isso só se faz para o teste*;
![habilitar](images/Sch8.1)

5. Agora volte para o inicio do recurso e clique em **Carregar**;

6. Abrirá uma caixa para arrastar documentos, porém terá que criar um contêiner;

7. Abaixo da opção **Selecionar um contêiner existente**, em azul há a opção **Criar**
![container](images/Sch9)

8. Apenas coloque o nome no seu contêiner e coloque os documentos no mesmo.

## Fazendo a busca

1. Vá até seu grupo de recursos e entre no seu Serviço de Pesquisa criado;

2. Na parte superior selecione **Importar dados**;
![dados](images/Sch10)

3. Selecione seu contêiner e faça as devidas configurações;

4. E pronto faça suas pesquisas e tire os melhores insights.
