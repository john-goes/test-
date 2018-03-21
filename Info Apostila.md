<img src="https://svgshare.com/i/5nn.svg"><br><br>
Conteúdo em Segurança da Informação e PCI para a apostila do On-Boarding:

<h4>Segurança da Informação</h4>
Conforme a sociedade vai evoluindo e inserindo a tecnologia na vida das pessoas, vai tornando-se cada vez mais latente e necessária a conscientização em segurança digital. Porém, uma vez que o digital é protegido por cadeados, portas e métodos de segregação/proteção físicos, a Segurança da Informação vem para englobar todo o modo como lidamos com informação. Os 4 preceitos principais que a Segurança da Informação está fundamentada é:<br>
  <strong>a) Confidencialidade</strong> - Proteção da privacidade da informação, segurança na comunicação e matenteneção da confidencialidade do dado.<br>
  <strong>b) Autenticidade</strong> - Proteção da veracidade da informação e do remetente da mesma e manteneção da autenticidade do dado ou do remetente/destinatário do mesmo.<br>
  <strong>c) Integridade</strong> - Proteção da integridade da informação, garantindo que a mesma foi inalterada e continua em seu formato original, estabelecendo a manteneção da integridade do conteúdo de uma mensagem ou dado.<br>
  <strong>d) Disponibilidade</strong> - Proteção da disponibilidade da informação, garantindo que a mesma é acessível por quem deve acessar.<br><br>
 Além de Segurança da Informação ser importante para qualquer organização ou pessoa, deve-se ter um cuidado especial quando em uma instituição financeira (isso inclui bancária e de pagamentos), como a Stone, pois é um alvo muito visado pelos crackers (hackers mal-intencionados) que buscam ter acesso a ativos valiosos como os dados que essas instituições detém, e isso inclui o dinheiro (pois ele também é um ativo, e o mais visado). Para que fiquemos seguros contra ataques visados contra nossa companhia, que pode impedir que estejamos do lado da nossa razão, o cliente, precisamos nos atentar para alguns cuidados muito importantes.
 Contudo, é necessário que se tenha a consciência que por sermos uma empresa financeira, é extremamente essecial que tenhamos <strong>credibilidade</strong>. Ninguém colocaria o dinheiro em algo conhecidamente não seguro (seja por uma matéria no jornal ou porque realmente a empresa foi atacada e considerada insegura).
<br><br>
<h4>PCI</h4>
 O PCI-DSS (abreviado por PCI), acrônimo para Payment Card Industry - Data Security Standards (Padrão de Segurança de Dados da Indústria de Cartões de Pagamento), é um padrão que prevê a proteção da confidencialidade de dados de cartões de pagamento. Sendo uma empresa que opera com serviços no mercado de pagamentos, somos certificados e portanto estamos em conformidade com as regras do PCI.<br>
 Todos os dados de um portador de cartão (CHD - Card Holder Data) são extremamente sensíveis e a regra padrão é que você não deva trafegá-los através de nenhum meio de comunicação. Logo, você não poderá receber, manusear ou enviar estes dados por E-mail, WhatsApp, Slack, incluindo qualquer outra ferramenta de comunicação externa ou interna da empresa.<br>
Há, porém, dados que são especialmente regulados e auditados pelo PCI-DSS, são eles:<br>
- PAN (Primary Account Number): número do cartão de crédito (ex. 4462 4763 9074 9123)<br>
- CVV (Card Verification Value): código de verificação do cartão de crédito (ex. 766)<br>
<br>
<img src="https://openclipart.org/image/2400px/svg_to_png/182038/credit-card-front.png" width="420" height="250">
<br>
Para você entender o nível de segurança investido para manter estes dados protegidos, o PCI DSS requer mais de 200 regras e diretrizes para garantir esta segurança. Caso todas as medidas não sejam cumpridas e mantidas periodicamente (sujeitas a revalidação periódica), nossa empresa sofre tanto o risco deste tipo de informação ser roubada, quanto o PCI DSS retirar nossa certificação, causar um prejuízo de imagem incalculável e ainda automaticamente perder clientes que requerem este tipo de certificação para operarem conosco.<br><br>
Atentem-se para os cuidados a seguir:<br>
- Saiba que no mundo da Segurança da Informação, não é apenas dados de cartão que são sensíveis. Chaves de API, senhas e PII (informação pessoalmente identificável) também são exemplos de dados que devem ser bem cuidados, uma vez que são sensíveis.<br>
- Seu crachá pode ser clonado, até a informação que ele passa (de que você trabalha em uma financeira) pode ser perigosa de se expor totalmente na rua. Inclusive, nomes são informações pessoalmente identificáveis, então passíveis de serem alvo de pessoas mal intencionadas. Então, por favor, guarde-o sempre no bolso ao sair da empresa.<br>
- Certifique-se que a porta do seu andar está fechada sempre, ela é a porta de entrada para alguém com acesso ao prédio.<br>
- Nunca anote suas senhas em post-its ou qualquer lugar que possam ser visualizadas por outras pessoas. Use um gerenciador de senhas caso tenha dificuldade para lembrar senhas.<br>
- Não enfraqueça a segurança do seu celular (com senha/PIN/padrão/etc simples ou até mesmo sem). Muita gente usa o e-mail da empresa, Slack ou qualquer outro meio sincronizado no dispositivo. Caso o celular seja roubado, perdido ou algo do tipo, será um prato cheio pra qualquer atacante. Então utilize senhas e padrões complexos. Se possível, utilize uma senha adicional no seu cliente de e-mail.<br>
- Use 2FA (segundo fator de autenticação). Caso um atacante obtenha sua senha de qualquer maneira (pode até ser por vazamento do banco de dados do site que armazena ela), ele pode acessar o serviço relacionado irrestritamente. Portanto, habilite 2FA em todos os serviços que ofereçam esse suporte (nosso e-mail, GitHub e Slack são exemplos).<br>
- Criptografe seu pendrive/notebook. É normal que percamos objetos, e esses podem ser perdidos. Qualquer um que os encontrasse e estivesse sem criptografia, poderia extrair as informações nele contidas. Caso seja um notebook de trabalho, códigos-fonte, credenciais, e-mail e muito mais pode ser comprometido. Portanto, use sempre dispositivos criptografados.<br>
- Evite falar sobre projetos ou informações internas da empresa em ambientes alheios a ela. Qualquer pessoa que estiver próximo pode ouvir e usar essas informações como bem entender.<br>
- Tenha extrema cautela ao se conectar no Wi-Fi de lugares públicos. Principalmente em redes populares como shoppings ou Starbucks. Você pode utilizar uma VPN para maior segurança.<br>
- Não se cale. Se você tiver conhecimento de um cliente ou colega de trabalho fazendo algo considerado inseguro, instrua-o. Ao não dizer nada, você está permitindo que essa situação perdure, então sempre faça algo. Se não conseguir instruí-lo, peça ajuda a equipe de segurança, mas nunca se omita.<br>
<b>- Bom senso!</b><br><br>
<i>Pagar.me Security Team - security@pagar.me</i><br>

<img src="https://i.imgur.com/DOY3ZsA.png" width="100" height="100">
