# 🔬 Open Molecular Printing Platform & Applied Ionic Technologies

![Licença: Hardware](https://img.shields.io/badge/Hardware_License-CERN--OHL--S-blue.svg)
![Licença: Software](https://img.shields.io/badge/Software_License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Research_%26_Development-orange)
![Open Collective](https://img.shields.io/badge/Open_Collective-Apply_in_Progress-lightgrey)

## 📌 Resumo Executivo

O projeto **Open Molecular Printing** é uma iniciativa pioneria de Hardware de Código Aberto (OSHW) dedicada a democratizar e expandir as fronteiras da **Impressão Molecular Aplicada** e da manufatura aditiva de materiais ativos. 

Nosso objetivo fundamental é transitar da impressão 3D geométrica tradicional para a construção funcional de dispositivos a nível molecular e estrutural. Desenvolvemos o ecossistema completo — desde a engenharia de impressoras com atmosfera controlada até as formulações químicas de tintas iônicas e poliméricas — permitindo a fabricação sob demanda de sistemas energéticos e funcionais diretamente na mesa de trabalho, .

Para validar o potencial desta tecnologia revolucionária, iniciamos o projeto com aplicações práticas de ponto de partida (*start applications*): a substituição de fontes de energia tradicionais, como **pilhas alcalinas de uso cotidiano**, e a evolução para sistemas avançados, como **baterias estruturais de Magnésio e Dióxido de Manganês ($Mg-MnO_2$)**, culminando em fuselagens de drones de alto desempenho impressas de forma monolítica.

---

## ⚠️ Aviso de Segurança (Safety Disclaimer)

**ESTE É UM PROJETO DE PESQUISA AVANÇADA EM QUÍMICA DE MATERIAIS E MANUFATURA.**
A replicação e os testes documentados neste repositório envolvem a manipulação de pós metálicos altamente reativos, solventes orgânicos, resinas curáveis por radiação e ambientes de gás inerte.
* A manipulação e a extrusão das tintas moleculares devem ser conduzidas estritamente em áreas ventiladas ou sob capela de exaustão.
* Equipamentos de Proteção Individual (EPIs), incluindo luvas nitrílicas/butílicas, óculos de segurança e proteção respiratória para particulados, são **obrigatórios**.
* Os mantenedores deste ecossistema isentam-se de responsabilidade por incidentes resultantes da replicação incorreta dos processos químicos e físicos descritos.

---

## 🏗️ Arquitetura do Repositório

O projeto é estruturado de forma modular para incentivar contribuições especializadas em diferentes frentes tecnológicas:

* 📁 **/Chemistry & Inks:** Formulações abertas de tintas funcionais, incluindo compostos catódicos ($MnO_2$ + aditivos condutores de carbono), ligantes poliméricos ativados e eletrólitos sólidos/gel.
* 📁 **/Printer & Atmosphere:** Projetos mecânicos, eletrônicos e de firmware para impressoras adaptadas à extrusão de fluidos viscosos (*Direct Ink Writing* - DIW), módulos de cura UV integrada e câmaras seladas de atmosfera controlada para evitar oxidação indesejada.
* 📁 **/Applications (Start & Scale):**
  * `/Micro_Power:` Modelos paramétricos e arquivos CAD para a impressão de células de energia compactas (alternativas totalmente abertas e customizáveis às pilhas alcalinas tradicionais para eletrônicos e dispositivos IoT).
  * `/Structural_LFSD:` Arquiteturas avançadas em estruturas celulares (favo de mel e Voronoi) para baterias estruturais aplicadas à fuselagem de veículos aéreos não tripulados.
* 📁 **/Software:** Scripts de controle de trajetória, geração de G-code paramétrico adaptado para fluidos não-newtonianos e automação do ambiente controlado.

---

## 🚀 Roadmap Tecnológico

Nossa jornada de desenvolvimento escala desde os fundamentos moleculares até aplicações industriais descentralizadas:

- [ ] **Fase 1: Formulação de Tintas e Reologia** - Otimização das proporções de misturas baseadas em $MnO_2$ e carbono para garantir comportamento tixotrópico ideal na extrusão.
- [ ] **Fase 2: O *Toolhead* Open Source** - Desenvolvimento e liberação de projetos de cabeças de extrusão de alta precisão para impressoras 3D acessíveis.
- [ ] **Fase 3: Aplicações "Start" (Pilha Aberta)** - Impressão bem-sucedida de células de energia primária de pequeno porte com geometrias customizadas, provando a viabilidade comercial frente às pilhas alcalinas convencionais.
- [ ] **Fase 4: Atmosfera Controlada e Escalabilidade** - Implementação de gabinetes de gás inerte de baixo custo para permitir o manuseio seguro de ânodos metálicos reativos (como o magnésio puro).
- [ ] **Fase 5: Integração Estrutural de Alto Desempenho** - Concretização do projeto LFSD (drone com fuselagem geradora de energia) e consolidação da plataforma global de impressão molecular aberta.

---

## 🤝 Como Contribuir

A evolução da manufatura molecular aberta exige colaboração multidisciplinar. Convidamos químicos de materiais, engenheiros mecânicos, desenvolvedores de software e entusiastas de hardware a somarem forças.

Consulte o nosso [Guia de Contribuição](CONTRIBUTING.md) e o [Código de Conduta](CODE_OF_CONDUCT.md) para iniciar suas interações e submissões.

---

## 💡 Financiamento e Transparência

Este projeto opera sob os princípios do desenvolvimento totalmente aberto e transparente. Buscamos a hospedagem fiscal junto à **Open Source Collective (OSC)** para garantir a integridade e a gestão comunitária de quaisquer recursos obtidos.

Os fundos coletados são aplicados exclusivamente em:
* Aquisição de reagentes químicos de pureza analítica e insumos laboratoriais.
* Usinagem e prototipagem de componentes mecânicos e câmaras de atmosfera controlada.
* Infraestrutura computacional para modelagem molecular e simulações assistidas por IA.

---

## 📄 Licenciamento

O ecossistema é regido por licenças abertas rigorosas:
* **Hardware, Mecânica e CAD:** [CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S)](https://ohwr.org/cern_ohl_s_v2.txt)
* **Firmware, Scripts e Código:** [Licença MIT](LICENSE-MIT.txt)
* **Documentação, Manuais e Textos:** [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)
