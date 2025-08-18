#  Alerta-Urbano-Projeto-Integrador

> Projeto desenvolvido para fins educacionais no âmbito da disciplina Projeto Integrador I, Curso de Ciência da Computação, UniCEUB.

Este projeto propõe o desenvolvimento do "Alerta Urbano", uma plataforma digital que capacita cidadãos, motoristas de aplicativos e moradores a monitorarem problemas de infraestrutura urbana, incluindo espaços públicos como escolas e praças, por meio de registros rápidos e acionáveis via aplicativo mobile.



##  Objetivo

Desenvolver uma solução digital que facilite a fiscalização de problemas urbanos, promovendo participação cidadã e integração com sistemas de Smart Cities, com foco inicial no Distrito Federal (Plano Piloto, Brasília) e potencial expansão para todo o Brasil ou estados/municípios interessados.



##  Informações Gerais

### Descrição
O "Alerta Urbano" é uma plataforma mobile que permite o registro de ocorrências de infraestrutura urbana (ex.: buracos, falhas de iluminação, problemas em escolas públicas e praças) com fotos, localização e data/hora. Utilizando princípios de Design Thinking, o projeto integra entrevistas com usuários reais, mapas de empatia, jornadas do usuário e requisitos funcionais/não funcionais para criar uma solução prática e escalável. A plataforma visa aumentar a transparência, reduzir riscos cotidianos e fortalecer a cidadania digital, com foco em decisões públicas baseadas em dados reais.

### Contexto
Conforme as normas ABNT NBR 14724:2011 (trabalhos acadêmicos) e NBR 6023:2018 (referências), este projeto consolida dados de imersão e análise de requisitos. Inicialmente concebido para o Distrito Federal, o aplicativo tem potencial para expansão nacional, adaptando-se às necessidades de estados ou municípios interessados. A ideia do "Alerta Urbano" foi parcialmente inspirada no aplicativo "SnapCrap", conhecido em contextos informais como "Poop Map", uma ferramenta mobile desenvolvida em San Francisco em 2018. Esse aplicativo permite que usuários registrem e compartilhem a localização de fezes humanas ou animais em vias públicas, enviando relatórios geolocalizados com fotos diretamente ao serviço municipal de limpeza. No "Alerta Urbano", adaptamos essa abordagem para criar uma ferramenta de fiscalização urbana, onde cidadãos registram problemas, compartilham evidências e validam ocorrências coletivamente, promovendo engajamento comunitário com foco em infraestrutura urbana e espaços públicos.



##  Objetivos do Projeto

### Objetivo Geral
Desenvolver um aplicativo mobile escalável e seguro que permita o registro, monitoramento e exportação de ocorrências de infraestrutura urbana, incluindo a fiscalização de espaços públicos como escolas públicas e praças, com evidências básicas e integração com gestores públicos e sistemas de Smart Cities.

### Objetivos Específicos
- Registrar ocorrências com localização, fotos e data/hora, abrangendo problemas em espaços públicos.
- Gerar pacotes de evidências (PDF/JSON) para cobranças ou reclamações.
- Disponibilizar mapas acessíveis com status das ocorrências e indicadores locais.
- Integrar via APIs com sistemas municipais e dispositivos IoT para priorização de respostas.
- Aumentar denúncias com campanhas locais, gamificação simples e canais como WhatsApp.
- Garantir conformidade com a LGPD e integridade das evidências.



##  Papéis dos Membros da Equipe

- **Líder do Projeto**: [Arthur Ramalho Hoffmann] 
- **Desenvolvedor Frontend**: [Arthur Ramalho Hoffmann] 
- **Desenvolvedor Backend**: [Arthur Ramalho Hoffmann] 
- **Documentador/Analista de Requisitos**: [Arthur Ramalho Hoffmann] 
- **Tester/Designer**: [Arthur Ramalho Hoffmann]   

> Obs: Sim… sou só eu mesmo, fazendo tudo… #TeamSolo 😭



##  Mapas de Empatia
Os mapas de empatia foram elaborados com base em entrevistas com usuários do Plano Piloto (Asa Sul e Asa Norte, Brasília, DF).

### Mapa de Empatia – João Souza (Motorista de Aplicativo – Asa Sul)
| Quadrante     | Descrição |
|---------------|-----------|
| Pensa e Sente | Preocupado com custos e segurança, frustrado com processos demorados, deseja provas rápidas e desconfia dos resultados da prefeitura. |
| Ouve          | Amigos relatando prejuízos com pneus furados e alinhamento desalinhado, grupos de WhatsApp com denúncias sem retorno oficial. |
| Vê            | Buracos nas ruas, iluminação falha, fotos de danos em grupos. |
| Diz e Faz     | "Putz, caí num buraco, isso vai me custar caro!" Tira fotos para postar em grupos do WhatsApp e evita ruas ruins. |
| Dores         | Falta de feedback, riscos ao veículo, prejuízos como tempo perdido, dificuldade de identificar o órgão responsável. |
| Ganhos        | Registro rápido, notificações, feedback mais rápido e data para resolver o problema. |

### Mapa de Empatia – Maria Silva (Moradora / Professora – Asa Norte)
| Quadrante     | Descrição |
|---------------|-----------|
| Pensa e Sente | Desconfia de canais oficiais por falta de retorno. Preocupa-se com segurança infantil em áreas obstruídas ou mal iluminadas. Sente frustração com ineficiência pública. |
| Ouve          | Reclamações de vizinhos e pais sobre problemas não resolvidos (vazamentos, iluminação, manutenção em praças). |
| Vê            | Observa degradação gradual e falta de reparos visíveis em escolas e praças. |
| Diz e Faz     | Conversa com pais sobre problemas, faz denúncias informais em grupos, altera caminhos diários. |
| Dores         | Burocracia excessiva, falta de feedback e medo de ineficácia. |
| Ganhos        | Mapa público com atualizações em tempo real e histórico auditável. |

### Mapa de Empatia – Associação de Moradores (Coletivo – Plano Piloto)
| Quadrante     | Descrição |
|---------------|-----------|
| Vê            | Alta incidência de problemas em áreas específicas, incluindo escolas e praças públicas. |
| Ouve          | Demandas replicadas por moradores em reuniões sobre manutenção de espaços públicos. |
| Pensa e Sente | Necessidade de ferramentas que centralizem provas e embasem demandas. |
| Fala e Faz    | Organiza abaixo-assinados, reuniões e pressão política. |
| Dores         | Falta de dados confiáveis e agregados para ações coletivas. |
| Ganhos        | Ferramenta que agrega denúncias, gera relatórios técnicos e facilita monitoramento comunitário. |



## 📂 Estrutura do Repositório
- `/docs`: Documentação (ex.: `relatorios.pdf`, `relatorio-tecnico.pdf`).
- `/assets`: Imagens e logos (ex.: `logo-alerta-urbano.png`).
- `/mapas`: Mapa mental e outros mapas (ex.: `mapa-mental-alerta-urbano.png`).



## 📚 Referências
- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **NBR 14724**: Informação e documentação - Trabalhos acadêmicos - Apresentação. Rio de Janeiro: ABNT, 2011.
- ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **NBR 6023**: Informação e documentação - Referências - Elaboração. Rio de Janeiro: ABNT, 2018.
- Lei Geral de Proteção de Dados (LGPD) - **Lei nº 13.709/2018**.

---
