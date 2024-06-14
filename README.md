
# Projeto de Medidas de Vieses Cognitivos

Este repositório contém várias tarefas relacionadas à medição de vieses cognitivos. Cada diretório contém scripts e recursos necessários para realizar experimentos específicos. A seguir, uma descrição de cada tarefa:

## APASAT
Esta tarefa utiliza o Paced Auditory Serial Addition Test (PASAT) para medir a capacidade de atenção sustentada e a velocidade de processamento. O diretório contém arquivos de áudio e scripts para a execução do teste.

- Arquivos de áudio numerados de 1 a 18 (.wav)
- `pasat_adaptive.iqx` - Script principal do PASAT adaptativo
- `pasat_adaptive_ctrl.iqx` - Script de controle do PASAT adaptativo

## Attention Bias Measure
Este diretório contém scripts e páginas HTML para a realização de uma tarefa de viés de atenção utilizando o paradigma do dot-probe.

- `Atention Bias_dotprobe.iqx` - Script principal da tarefa de dot-probe
- `dotprobe_macleod_intro1.htm` - Página de introdução
- `dotprobe_macleod_teststart.htm` - Página de início do teste

## CBM-a
Contém scripts para a realização de uma tarefa de modificação de viés atencional (Attention Bias Modification, ABM).

- `dotprobe_ABM.iqx` - Script principal da tarefa ABM
- `dotprobe_ABM_ctrl.iqx` - Script de controle da tarefa ABM

## CBM-i
Contém scripts para a realização de uma tarefa de modificação de viés interpretativo (Interpretation Bias Modification, CBM-i).

- `CBM-i_with_neg &_pos_probes - controlo.iqx` - Script de controle da tarefa CBM-i
- `CBM-i_with_neg &_pos_probes.iqx` - Script principal da tarefa CBM-i

## Interpretation Bias Measure
Este diretório contém arquivos de imagem e um script para a realização de uma tarefa de medição de viés interpretativo.

- `intro1.jpg`, `intro2.png`, `intro2.jpg`, `intro3.jpg`, `intro3.png` - Imagens de introdução
- `scrambledsentencestask.iqx` - Script da tarefa de frases embaralhadas

## Memory Bias Measure
Contém um script para a realização de uma tarefa de medição de viés de memória.

- `selfreferentencodingtask.iqx` - Script da tarefa de codificação autorreferente

## Working Memory Capacity
Contém um diretório com recursos para a medição da capacidade de memória de trabalho.

- `2n-back` - Diretório com recursos para a tarefa n-back

## Estrutura do Projeto
```
APASAT/
├── 1.wav
├── 2.wav
...
├── pasat_adaptive.iqx
└── pasat_adaptive_ctrl.iqx

Atention Bias Measure/
├── Atention Bias_dotprobe.iqx
├── dotprobe_macleod_intro1.htm
└── dotprobe_macleod_teststart.htm

CBM-a/
├── dotprobe_ABM.iqx
└── dotprobe_ABM_ctrl.iqx

CBM-i/
├── CBM-i_with_neg &_pos_probes - controlo.iqx
└── CBM-i_with_neg &_pos_probes.iqx

Interpretation Bias Measure/
├── intro1.jpg
...
└── scrambledsentencestask.iqx

Memory Bias Measure/
└── selfreferentencodingtask.iqx

Working Memory Capacity/
└── 2n-back/
```
