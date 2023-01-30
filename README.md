<!--
    TITLE:      README
    AUTOR:      GUSTAVO GONÇALVES DIAS NEVES
    DATA_INIT:  26.01.2023

    PROJECT:    APP 5S - POWER APPS (LOWER-CODE)
    
    CONNECT ME:
        Linkedin: https://www.linkedin.com/in/gustavo-gon%C3%A7alves-dias-neves-3b76b3252/
        github (curr-account): https://github.com/gustavogoncalvesdiasneves/
        
 -->


<h1 align="center" alt="Aplicativo de Gestão 5S"><strong>Aplicativo 5S</strong></h1>

<br/>

<p align="center" alt="objetivo do projeto">Esse projeto tem o objetivo de ajudar as empresas com a Gestão do 5S, por base do Microsoft Power Apps (Microsoft 365 - Plataforma de Apps Intranet).</p>

<br/>
<p align="center">
<img style="margin:auto" src="OpenScreenApp.gif" width="200" />
<p />

**OBS: Borrei a Logo por integridade a Empresa.** 

<br/><hr/>

<h2>Índice</h2>

- **[Descrição](#descrição)**<br/>
- **[Características](#características)**<br/>
- **[Futuras Novidades](#futuras-novidades)**<br />


<hr/>
<br/><br/>


## **Descrição**
[APP 5S][link-app-5s] é um Aplicativo de Gestão 5S, mais voltado a gestão de preenchimento de check-lists dos setores da empresa, podendo ter a visualização por Graficos Power BI (Graficos Inteligentes), e premiações utilizando notificações quando se é premiado (OBS: essas premiações passava para um grafico de controle geral que a empresa tinha acesso para premiar o funcionario), O App possui tela Admin para não precisar do Gestor do App para funções mais especificas, como: Cadastrar Funcionarios Novos, Remover ou Editar(Podendo editar o previlegio de um usuario que não tem acesso a tela Admin para ter acesso), Adicionar Mais Opções na Check-List de um Setor, ou Remover ou Editar, Visualizador dos PDFs gerados quando enviados os checklists (também havendo possibilidade de remover), Tela de Premiações, IMG para JSON (Tela do Gestor - Um Conversor de IMG para formato JSON, utilizados na automação de criação de PDFs), entre outras muitas funções =D.

<br/><br/>


## **Características**
A aplicação fornece os seguintes recursos:
- [CheckList](#checklist) (Baseada no Share-Point como Banco de Dados)
- [FocalPoints](#focalpoints) (Tela onde o usuario pode verificar oque cada FocalPoint faz em sua aréa)
- [Indicadores](#indicadores) (Graficos Inteligentes e Comparativos)  
- Meus CheckLists (Podendo Visualizar Todos os Checklist's que o usuario enviou até o momento utilizando o app)
- Tela Admin (Contendo Funções Previlegiadas, Somente Admins e Gestor tem Acesso á essa tela)

## **Futuras Novidades**
- APLICATIVO DESCONTINUADO

<br/><br/>


## **CheckList**

CheckList foi baseado em uma Lista de Share-point-sever, tendo todos seu dados armazendos na nuvem.


<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
	<tbody>
		<tr>
			<td>
<img style="margin:auto" src="PESSOA1.png" width="300" /></td>
			<td>
			<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
				<tbody>
					<tr>
						<td><strong><p align="center"><img style="margin:auto" src="VERMELHO - CheckList1.png" width="500" /> <br> VERMELHO - Quando o usuario <ins>NÂO</ins> enviou nenhum CheckList</p></strong></td></td>
					</tr>
					<tr>
						<td><strong><p align="center"><img style="margin:auto" src="AMARELO-CheckList.png" width="500" /> <br> AMARELO - Quando o usuario enviou <ins>APENAS UM</ins> CheckList</p></strong></td>
					</tr>
					<tr>
						<td><strong><p align="center"><img style="margin:auto" src="VERDE - CheckList1.png" width="500" /><br> VERDE - Quando o usuario enviou <ins>TODOS</ins> os CheckLists (2 Checklists)</p><strong></td>
					</tr>
				</tbody>
			</table>
			</td>
		</tr>
	</tbody>
</table>

<br/>

## **FocalPoints**

Tela onde os usuarios podem ver oque cada setor segundo a orientação do 5S da empresa necesita que ele realize.

<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
	<tbody>
		<tr>
			<td><strong><p align="center"><img style="margin:auto" src="FocalPoints1.png" width="300" /><br> Lista de <ins>TODOS</ins> os FocalPoints</p><strong></td>
			<td><strong><p align="center"><img style="margin:auto" src="FocalPoints2.png" width="300" /><br> Orientação do <ins>Atual FocalPoint</ins> da Pessoa.</p><strong></td>
		</tr>
	</tbody>
</table>
		
<br/>

## **Indicadores**
		
**Grafico Geral**

Tela onde o usuario pode e Administradores podem ver um **Grafico Geral** e um Grafico com **Valores Unicos** de cada setor.
		
<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
	<tbody>
		<tr>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Geral.png" width="600" /><br> Grafico Geral</p><strong></td>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Geral2.png" width="380" /><br> Possibilidade de <ins>Filtrar por Datas</ins></p><strong></td>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Geral3.png" width="300" /><br> Basta selecionar a <ins>Data</ins> que deseje que o Grafico Filtre.</p><strong></td>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Geral4.png" width="330" /><br> Possibilidade de  <ins>visualizar outros setores</ins></p><strong></td>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Geral5.png" width="150" /><br> Depois de selecionar o <ins>Setor</ins> e <ins>Datas</ins> desejadas o grafico automaticamente filtrará :D <p><strong></td>
		</tr>
	</tbody>
</table>
				
**Grafico Unico**
				
<hr />
				
<h3 align="center">IMPORTANTE</h3>
				
<strong><p align="center"><img style="margin:auto" src="G1_to_G2.png" width="300" /><br> Para passar do <ins>Grafico Geral</ins> para o <ins>Grafico Unico</ins> Clique no Botão da Seta para Direita.</p><strong>
	
<hr />

Grafico onde pode ver as diferenças de cada setor por **S** Separados. (Com Bonus de Soma Geral de Todos os S)
				
<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
	<tbody>
		<tr>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico.png" width="300" /><br> Grafico Mostrando somente o <ins>1S</ins></p><strong></td>
			<td>
			<table border="0" cellpadding="1" cellspacing="1" style="width:500px">
				<tbody>
					<tr>
						<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico2.png" width="100" /><br> Grafico Mostrando somente o <ins>2S</ins></p><strong></td>
						<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico3.png" width="100" /><br> Grafico Mostrando somente o <ins>3S</ins> </p><strong></td>
					</tr>
					<tr>
						<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico4.png" width="100" /><br> Grafico Mostrando somente o  <ins>4S</ins></p><strong></td>
						<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico5.png" width="100" /><br> Grafico Mostrando somente o <ins>5S</ins><p><strong></td>
					</tr>
				</tbody>
			</table>
			</td>
			<td><strong><p align="center"><img style="margin:auto" src="Grafico_Unico6.png" width="300" /><br> Grafico Mostrando a soma de  <ins>Todos os 5S</ins><p><strong></td>
		</tr>
	</tbody>
</table>



<!-- 
    LOCAL VARIABLES
 -->

[link-app-5s]: https://github.com/gustavogoncalvesdiasneves/Aplicativo_5S_-PowerApps-/
[link-executavel]: https://github.com/gustavogoncalvesdiasneves/BOT_LinkedIn/tree/main/build/Executavel
[link-video]: https://www.youtube.com/channel/UC_9SeJaG7zalUCosUt8BnFA
[link-pdf-navegador]: http://www.gestaoescolar.diaadia.pr.gov.br/arquivos/File/pde_roteiros/como_identificar_versao_navegador_pronto.pdf
[chrome-driver-link]: https://chromedriver.chromium.org/downloads
