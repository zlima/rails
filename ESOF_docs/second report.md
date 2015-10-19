Relatório 2 - ESOF
=================

 ***Rails* gestão de Requisitos** 



Elicitação
-------------
<br><br>
&nbsp;&nbsp;&nbsp;Sendo o *rails* um projecto open-source já num estado avançado, com mais de 4000 contribuidores, os novos requisitos podem ser propostos de algumas maneiras diferentes, colaboradores podem fazer  *pull-requests* no *github*, para serem mais tarde analisados pela comunidade e pela *core team*, enviar e-mail directamente para a core team ou até mesmo reportar issues  no github.<br>
&nbsp;&nbsp;&nbsp;A *core-team* do *rails* não tem nenhuma lista de requisitos publicada, o que nos leva a acreditar que novos requisitos são só mesmo apenas através das validações de novas propostas.<br>
&nbsp;Para um *developer* contribuir para o projecto com novo código existem algumas regras a seguir :<br>

	1.  O *developer* deve criar um ambiente onde consiga correr os testes feitos pela equipa do *rails*, podendo descarregar uma máquina virtual já configurada ou configurar o ambiente ele próprio;
	2. Fazer clone ao repositório do *rails* no *github*;
	3.	Instalar as gems necessárias;
	4. Correr uma aplicação contra o *branch* local;
	5. Deve ser seguida uma convenção de identação especificada no *site* do *rails*;
	6. Se o novo código tiver um impacto na performance do rails, efectuar um teste de benchmark;
	7. Correr os testes fornecidos pelo *rails*;
	8. Corrigir erros detectados nos testes;
	9. Fazer update ao *ChangeLog*;
	10. Actualizar o *Gem.lock*
	11. Fazer *commit* para o *github*;
	12. Actualizar a *branch*;
	13. Fazer *Fork* ao projeto do rails e criar um novo *Pull-request* e esperar por *feedback* da comunidade.
<br>

Estas informações podem ser consultadas com mais detalhe neste link [Contribution detalis](http://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html).<br><br>





Validação
------------------
<br><br>
&nbsp;&nbsp;&nbsp;Como já foi dito o Rails é um projecto onde qualquer pessoa pode contribuir.  Após a criação de um novo *pull-request* este é analisado pela comunidade, tendo o contribuidor de esperar por feedback em relação ao seu pedido para corrigir ou melhorar alguma coisa. Como todas as pessoas que trabalham para o rails são voluntarias este processo por vezes pode ser lento, eventualmente a nova contibuição será aprovada pela *core-team*.<br>
&nbsp;&nbsp;&nbsp;Grande parte da validação é feita também pelos testes fornecidos pela comunidade do *rails*.<br>


&nbsp;&nbsp;&nbsp;Como forma de contextualização, a figura abaixo mostra o número de *pull-requests* recebidos no período entre 11 de Outubro e 18 de Outubro de 2015. Foram recebidos 39 pull-requests numa semana, o que demonstra uma clara necessidade de uma seleção criteriosa destes pedidos.<br>

![enter image description here](http://i.imgur.com/e23PRhM.png)


&nbsp;&nbsp;&nbsp;A imagem abaixo demonstra os *issues* que foram submetidos no período entre 11 de Outubro 11 e 18 de Outubro de 2015. Foram recebidos 27 issues estando 18 já resolvidos e 9 sendo novos.<br>

![enter image description here](http://i.imgur.com/SXtciqI.png)


&nbsp;&nbsp;&nbsp;Como podemos concluir atráves de uma análise do github a comunidade está atenta e ajuda resolução destes issues mas por vezes com alguma lentidão, tendo alguns destes sido criados à mais de uma semana.
<br><br>


Use Case
-------------------------------
<br><br>

Elaboramos um diagrama UML onde tentamos representar muito genericamente o que um developer pretende quando utiliza o *rails*.<br>


![enter image description here](http://i.imgur.com/uOBPHSf.png)

<br><br>

Conclusão
----------------------------
<br><br>
&nbsp;&nbsp;&nbsp;O processo de Engenharia de Requisitos no desenvolvimento da *framework rails* parece-nos bastante adequado uma vez que o *rails* foi retirado de um projecto e tornado *open-source* pelo seu criador para que *developers* o pudessem utilizar e contribuir para o seu crescimento, podendo utilizar módulos já feitos nos seus seus projectos,  evitando uma repetição de código e tornando o desenvolvimento mais rápido.<br>
&nbsp;&nbsp;&nbsp;Uma vez que o projecto segue uma metodologia *agile*  enquanto a comunidade for activa novos requisitos vão sempre aparecendo à medida que forem necessários, o que é bastante interessante pois pode aumentar a longitivade da utilização do *rails* garantindo uma constante actualização das suas funcionalidades.<br>
&nbsp;&nbsp;&nbsp;O facto de novas contribuições terem que cumprir regras establecidas facilita bastante na compreensão do novo código pela comunidade, sendo também as ferramentas do *github* cruciais na organização e na dinâmica deste projecto.<br><br>
