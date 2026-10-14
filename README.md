# Cama suspensa em tubo galvanizado, com nós impressos em 3D

Cama de casal flutuante (sem pés visíveis, base recuada 15 cm) em tubo galvanizado de 1¼" e 1", com nós estruturais impressos em 3D em PETG. Projeto completo: desenho, simulação estrutural, lista de corte, ferragens, arquivos STL das peças impressas e manual de montagem passo a passo.

## Ficha técnica

| | |
|---|---|
| Estrutura | 3 longarinas e 4 travessas em tubo de 1¼" sobre base recuada de 6 postes |
| Cabeceira | painel de tubo de 1", fixado na parede, sem carga da cama |
| Nós impressos | 62 impressões em PETG — 11,4 kg (9,2 kg na versão leve) |
| Colchão | casal, 138 × 188 cm |
| Vão livre | 28 cm entre a base e o estrado |
| Carga testada | duas pessoas de 100 kg, incluindo queda de 10 cm no canto do pé (pior caso: 107 MPa, 46% do escoamento) |

## Conteúdo do repositório

- **[docs/projeto-completo.html](docs/projeto-completo.html)** — o projeto completo: evolução do desenho, simulação de elementos finitos (estática e dinâmica), lista de corte dos tubos, ferragens, detalhes dos soquetes e sequência de montagem.
- **[docs/manual-montagem-cama-flutuante.pdf](docs/manual-montagem-cama-flutuante.pdf)** — manual de montagem em PDF, com as 14 etapas ilustradas, peças/ferragens de cada etapa e os encaixes conferidos.
- **[docs/montagem-passo-a-passo.html](docs/montagem-passo-a-passo.html)** — a mesma montagem como animação 3D interativa (câmera livre, peças explodidas, tabela de verificações).
- **[stl/](stl)** — arquivos STL das 62 impressões (nós da base, colares, selas e cabeceira), já orientados para o fatiador. Ver `stl/LEIA-ME-stl.txt` para a lista completa, quantidades e ajustes de impressão (PETG, 235–245 °C, mesa 75–80 °C).
- **[assets/](assets)** — modelos 3D em glTF binário (`.glb`) da cama montada e explodida, para visualização em Blender, Visualizador 3D do Windows ou qualquer visualizador glTF.
- **[docs/LEIA-ME_pecas_impressas.txt](docs/LEIA-ME_pecas_impressas.txt)** — lista de impressão e furação das peças, em texto simples.

## Material e impressão

PETG é o material recomendado (boa adesão entre camadas, resiste ao calor comum de quarto, imprime sem caixa fechada). Parâmetros: bico 235–245 °C, mesa 75–80 °C, ventoinha 20–30%, camadas 0,2 mm, 8 perímetros e 40% de preenchimento (versão leve: 6 perímetros e 25%). Detalhes completos no `stl/LEIA-ME-stl.txt`.

## Pendências

- Teste físico do nó impresso (soquete real em PETG, carga de 10 kg a 50 cm) antes da impressão de todas as peças.
- Teste de carga final: 400 kg distribuídos por 24 h, com verificação de deflexão e nivelamento.
