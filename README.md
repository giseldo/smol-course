![smolcourse image](./banner.png)

# a smol course

Este é um curso prático sobre como alinhar modelos de linguagem para casos de uso específicos. É uma maneira prática de começar a trabalhar com o alinhamento de modelos de linguagem, pois tudo pode ser executado na maioria das máquinas locais. Os requisitos de GPU são mínimos e não há necessidade de serviços pagos. O curso é baseado na série de modelos [SmolLM2](https://github.com/huggingface/smollm/tree/main), mas as habilidades aprendidas aqui podem ser transferidas para modelos maiores ou outros modelos de linguagem pequenos.

## Course Outline

Este curso oferece uma abordagem prática e prática para trabalhar com pequenos modelos de linguagem, desde o treinamento inicial até a implantação em produção.

| Module | Description | Status | Release Date |
|--------|-------------|---------|--------------|
| [Instruction Tuning](./1_instruction_tuning) | Learn supervised fine-tuning, chat templating, and basic instruction following | ✅ Ready | Dec 3, 2024 |
| [Preference Alignment](./2_preference_alignment) | Explore DPO and ORPO techniques for aligning models with human preferences | ✅ Ready  | Dec 6, 2024 |
| [Parameter-efficient Fine-tuning](./3_parameter_efficient_finetuning) | Learn LoRA, prompt tuning, and efficient adaptation methods | ✅ Ready | Dec 9, 2024 |
| [Evaluation](./4_evaluation) | Use automatic benchmarks and create custom domain evaluations | ✅ Ready | Dec 13, 2024 |
| [Vision-language Models](./5_vision_language_models) | Adapt multimodal models for vision-language tasks | ✅ Ready | Dec 16, 2024 |
| [Synthetic Datasets](./6_synthetic_datasets) | Create and validate synthetic datasets for training | ✅ Ready | Dec 20, 2024 |
| [Inference](./7_inference) | Infer with models efficiently | ✅ Ready | Jan 8, 2025 |
| [Agents](./8_agents) | Build your own agentic AI | ✅ Ready | Jan 13, 2025 ||

## Por que Modelos de Linguagem Pequenos?

Embora os grandes modelos de linguagem tenham demonstrado capacidades impressionantes, eles frequentemente exigem recursos computacionais significativos e podem ser excessivos para aplicações focadas. Modelos de linguagem pequenos oferecem várias vantagens para aplicações específicas de domínio:

- **Eficiência**: Requerem significativamente menos recursos computacionais para treinamento e implantação.
- **Personalização**: Mais fáceis de ajustar e adaptar a domínios específicos.
- **Controle**: Maior compreensão e controle sobre o comportamento do modelo.
- **Custo**: Custos operacionais mais baixos para treinamento e inferência.
- **Privacidade**: Podem ser executados localmente sem enviar dados para APIs externas.
- **Tecnologia Verde**: Promovem o uso eficiente de recursos com menor pegada de carbono.
- **Facilidade para Pesquisa Acadêmica**: Oferecem um ponto de partida acessível para pesquisas acadêmicas com LLMs de ponta e menos restrições logísticas.
## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte:
- Compreensão básica de aprendizado de máquina e processamento de linguagem natural.
- Familiaridade com Python, PyTorch e a biblioteca `transformers`.
- Acesso a um modelo de linguagem pré-treinado e a um conjunto de dados rotulado.
## Instalação

### Windows

Todos os exemplos são executados no mesmo ambiente **python 3.11**, então você deve criar um ambiente e instalar as dependências assim:

```bash
python -m venv .venv
.venv/bin/activate
pip install -r requirements.txt
```

### Google Colab

**No Google Colab**, você precisará instalar as dependências de forma flexível com base no hardware que está utilizando. Assim:

```bash
!pip install transformers trl datasets huggingface_hub
```

```bash
pip install transformers trl datasets huggingface_hub
```

