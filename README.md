# Resumo-Artigo
# Projeto ReSist
O projeto ReSist visa criar uma solução robusta para identificar e restringir conteúdos nocivos com contextos discursivos injuriosos acessados ​​na internet dentro de instituições de ensino, garantindo um ambiente digital mais seguro e controlado. A proposta combina tecnologias avançadas, como o servidor proxy Squid, usado para monitoramento e filtragem de páginas da web, e inteligência artificial baseada na arquitetura BERT, uma poderosa ferramenta para compreensão semântica de textos. A iniciativa busca não apenas bloquear conteúdos tóxicos, como discurso de ódio, mas também aprimorar continuamente sua capacidade de detecção por meio de aprendizado contínuo. Os registros de acesso são processados ​​e analisados ​​em um banco de dados NoSQL (MongoDB), permitindo que a IA classifique o conteúdo em categorias como insultos, ameaças e ataques de identidade. Se um conteúdo for identificado como nocivo, ele é bloqueado e usado para retreinar o modelo, aprimorando sua eficiência e precisão ao longo do tempo. Além de fornecer proteção em tempo real, o sistema reflete um compromisso com a inovação tecnológica e a responsabilidade digital, visando salvaguardar usuários e organizações contra interações online prejudiciais.

## Tecnologias Utilizadas
- **Squid Proxy Server**: monitoramento e filtragem de páginas da web.  
- **Inteligência Artificial (BERT)**: modelo avançado para compreensão semântica de textos.  
- **MongoDB (NoSQL)**: armazenamento e análise dos registros de acesso.  

## Funcionamento
1. **Monitoramento**  
   O tráfego é inspecionado pelo servidor proxy Squid.  
   
2. **Classificação**  
   A IA baseada em BERT analisa os conteúdos acessados e os categoriza em:  
   - Insultos  
   - Ameaças  
   - Ataques de identidade  

3. **Bloqueio e Aprendizado Contínuo**  
   Conteúdos nocivos são bloqueados imediatamente e utilizados para **re-treinamento do modelo**, aprimorando a precisão ao longo do tempo.  

## Objetivo
O ReSist não apenas bloqueia discursos de ódio e outras interações prejudiciais em tempo real, mas também evolui continuamente, refletindo um compromisso com:  
- **Inovação tecnológica**  
- **Responsabilidade digital**  
- **Proteção de usuários e organizações**  

##Link: https://docs.google.com/document/d/17eBzEnra7r-OvuVe5xkdMqUalgODq83M/edit?usp=sharing&ouid=106564744839702055734&rtpof=true&sd=true





