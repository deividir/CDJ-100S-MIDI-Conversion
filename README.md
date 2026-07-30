# Pioneer CDJ-100S USB MIDI Conversion

Transforme um clássico da Pioneer em um moderno controlador **USB MIDI**, preservando toda a ergonomia, construção e aparência original do equipamento.

Este projeto substitui toda a eletrônica principal do **Pioneer CDJ-100S** por uma **STM32 BlackPill**, permitindo sua utilização com softwares modernos de DJ.

> ⚠️ Este repositório contém apenas a documentação do projeto. O firmware é proprietário e **não está disponível**.

---


# Principais Recursos

✔ Conversão completa para USB MIDI

✔ STM32 BlackPill (STM32F411CEU6)

✔ Jog Wheel de alta precisão

✔ Pitch Fader Analógico

✔ Todos os botões originais funcionais

✔ LEDs originais reaproveitados

✔ Display LCD 16x2 (Opcional)

✔ DAC PCM5102 para saída de áudio (Opcional)

✔ Compatível com qualquer software que possua suporte ao protocolo MIDI

✔ Mantém a aparência original do CDJ

---

# Como Funciona

O projeto remove a eletrônica principal do CDJ-100S e instala uma **STM32 BlackPill**, que passa a controlar todos os componentes do equipamento.

A STM32 realiza a leitura de:

- Pitch Fader
- Jog Wheel
- Botões
- LEDs
- Display LCD (Opcional)

Todos esses comandos são convertidos em mensagens **USB MIDI**, permitindo o controle de softwares de DJ modernos.

Quando utilizado o **DAC PCM5102**, o áudio digital enviado pelo computador é convertido para áudio analógico e disponibilizado diretamente nas saídas RCA do equipamento.

---

# Compatibilidade

| Software | MIDI | Áudio |
|----------|:----:|:-----:|
| VirtualDJ | ✅ | ✅ |
| Mixxx | ✅ | ✅ |
| Rekordbox | ⚠️ | Funciona mas é necessário Hardware homologado |
| Serato DJ | ⚠️ | Funciona mas é necessário Hardware homologado |

---

# Hardware Utilizado

- STM32 BlackPill STM32F411CEU6
- LCD 16x2 I²C (Opcional)
- DAC PCM5102 (Opcional)
- ST-Link V2
- Pioneer CDJ-100S

---

# Estrutura do Projeto

```
CDJ-100S

↓

STM32 BlackPill

↓

USB MIDI

↓

Computador

↓

Software DJ

↓

PCM5102 (Opcional)

↓

Saídas RCA
```

---

# Aqui você encontrará:

✔ Apresentação do projeto

✔ Fotos do controlador finalizado

✔ Demonstrações em vídeo

✔ Manual de Montagem Demonstração

✔ Histórico de atualizações

> Este repositório possui caráter demonstrativo e não contém os arquivos necessários para a construção completa do projeto.

---

# O que NÃO está disponível

❌ Firmware

❌ Código-fonte

❌ Arquivos de programação

❌ Mapas MIDI

O firmware utilizado neste projeto é de desenvolvimento próprio e não é disponibilizado neste repositório.

Caso deseje utilizar este projeto, você poderá:

- Desenvolver seu próprio firmware.
- Adquirir uma STM32 BlackPill já programada.

---

# Manual Técnico

O manual completo possui mais de **25 páginas**, contendo:

- Desmontagem completa
- Ligações elétricas
- Localização dos componentes
- Mapa de conexões
- Instalação do LCD
- Instalação do DAC PCM5102
- Identificação das trilhas
- Testes
- Resolução de problemas
- Diagramas detalhados

---

# Aviso

Este projeto é destinado exclusivamente para fins educacionais e de estudo.

Toda modificação é realizada por conta e risco do usuário.

A Pioneer DJ, AlphaTheta, Serato, Rekordbox, VirtualDJ e demais marcas citadas pertencem aos seus respectivos proprietários.

---

# Firmware

O firmware utilizado neste projeto é proprietário e não é distribuído em formato digital.

Para quem deseja uma solução pronta para instalação, disponibilizo uma **STM32 BlackPill original já programada e testada**, fornecida separadamente.

Dessa forma, não é necessário possuir um gravador ST-Link nem realizar o processo de gravação do microcontrolador.

Caso prefira, você também pode desenvolver seu próprio firmware utilizando a documentação de hardware disponível no manual técnico.

---

# Adquirir uma STM32 Programada

Caso prefira não desenvolver seu próprio firmware, disponibilizo placas **STM32 BlackPill já programadas e testadas**, prontas para instalação.

📘 [Curso Completo] - R$ 44,90

💾 [1 STM32 Gravada e Testada] - R$ 120,00

📦 [Curso + 1 STM32 Gravada e testada] - R$ 149,00

📦📦 [Kit para 2 CDJs (2 STM32 + curso)] – R$ 249,90 ou R$ 259,90.

---


# Licença

Este repositório disponibiliza apenas a documentação do hardware.

O firmware é proprietário (**Proprietary Software**) e não está licenciado para redistribuição.

---

# Contato

Instagram: https://www.instagram.com/djdeividi

E-mail: djdeividi@hotmail.com

---

