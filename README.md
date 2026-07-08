# Otto-Canteiro
🤖 Robótica Aplicada à Engenharia: Evolução do Projeto Otto

Universidade do Estado da Bahia (UNEB)
Disciplina: Computação Aplicada à Engenharia | Orientador: Prof. Robson Marinho
Discentes: Ariele Gomes, Luis Gustavo, Micaele Pereira e Raiane Borges

📝 1. Introdução

Este repositório documenta a evolução do robô Otto DIY. Após a conclusão e validação do modelo bípede, iniciamos uma nova etapa de desenvolvimento focada em adaptar a plataforma para o canteiro de obras. O objetivo desta fase é transformar o robô em uma ferramenta de assistência técnica, capaz de realizar inspeções e transporte de materiais leves, garantindo maior estabilidade e eficiência em ambientes de construção civil.

📊 2. Modelagem do Sistema

Para a nova etapa, atualizamos a modelagem para atender às mudanças mecânicas:

    Adaptação Operacional: Ajuste nos fluxos de controle para suportar a transição do movimento bípede para tração por esteiras.

    Redes de Petri: Atualização dos modelos teóricos para contemplar as novas funções de transporte de carga e monitoramento de distâncias em obra.

    Segurança: Refinamento dos parâmetros de detecção de obstáculos, visando uma navegação mais segura em ambientes dinâmicos.

⚙️ 3. Implementação e Hardware

    Microcontrolador: Arduino Nano ().

    Sistema de Tração: Motores DC com tração por esteiras (substituindo os servomotores originais para ganho de torque e estabilidade).

    Estrutura: Chassis impresso em 3D, projetado para maior durabilidade e proteção dos componentes eletrônicos.

    Funcionalidade: Caçamba articulada e trailer acoplado para transporte de ferramentas e insumos leves.

    Firmware: Código em C++ adaptado para controle de motores DC e gerenciamento da nova configuração do robô.

📂 4. Estrutura do Repositório

    📂 Codigo/: Firmware de controle para o sistema de tração por esteiras.

    📂 documentacao/: Relatórios técnicos sobre as alterações mecânicas e testes realizados.

    📂 hardware/: Arquivos CAD (.STL) do novo chassis, esteiras e módulos de carga.

    📂 modelagem/: Modelos de Redes de Petri atualizados.

    📂 processo-montagem/: Registros em foto e vídeo da evolução do protótipo.

🚀 5. Objetivo desta Etapa

Diferente do modelo bípede anterior, o objetivo desta etapa de otimização é transformar o Otto em um assistente de transporte e inspeção com as seguintes características:

    Sistema de Locomoção: Transição para tração por esteiras (lagartas) motorizadas (Motores + Driver ) para maior estabilidade e transposição de obstáculos em superfícies irregulares de obra.

    Função de Monitoramento: Detecção autônoma de distância de paredes e obstáculos para auxílio na conferência de medidas de projeto e navegação segura.

    Capacidade de Transporte: Implementação de caçamba de carga articulada e trailer para deslocamento de pequenas ferramentas, componentes leves e insumos de obra. o Otto como um protótipo funcional para a automação de processos produtivos e suporte à gestão de materiais em obras.    
    
