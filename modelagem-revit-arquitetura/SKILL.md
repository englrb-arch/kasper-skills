---
name: modelagem-revit-arquitetura
description: Roteiro de modelagem de projetos de arquitetura no Revit, na ordem correta, com checagens a cada etapa. Use quando for iniciar, continuar ou revisar um modelo.
---

# Modelagem de projeto de arquitetura no Revit

Rascunho feito a partir do papel do Kasper. Trechos marcados com [CONFIRMAR] dependem do padrao da empresa e precisam ser preenchidos pelo Lucas.

## Regras gerais
- Siga a ordem das etapas abaixo. Nao pule para a etapa seguinte sem concluir a checagem da atual.
- Antes de comecar, confirme: template do projeto, unidade, sistema de coordenadas, nivel de desenvolvimento (LOD) [CONFIRMAR].
- Nomeie tudo (niveis, tipos de parede, vistas, folhas) conforme o padrao [CONFIRMAR]. Nunca deixe nomes padrao.
- Use tipos e familias do template. So crie familia nova se nao existir equivalente, e avise o Lucas.
- Ao terminar cada etapa, registre o que foi feito e o que ficou pendente.

## Etapas

1. Niveis e eixos
   - Niveis com cotas reais (terreo, pavimentos, cobertura, fundacao) e nomes padronizados.
   - Eixos nomeados e travados (pin) depois de conferidos.
   - Checagem: todos os niveis tem vistas de planta; eixos alinhados com o projeto de referencia.

2. Paredes
   - Tipos por funcao (externa, interna, divisoria, shaft) com camadas e espessuras corretas [CONFIRMAR espessuras].
   - Restricoes de base e topo ligadas aos niveis.
   - Checagem: sem paredes sobrepostas, sem vaos acidentais nos encontros, juncoes limpas.

3. Pisos
   - Um piso por ambiente ou area continua, com tipo e acabamento corretos.
   - Checagem: bordas coincidem com as paredes e o piso nao invade vaos de escada.

4. Janelas e portas
   - Familias do template, por cota de peitoril/soleira correta; marcas unicas e sequenciais.
   - Checagem: nenhuma porta ou janela sem parede hospedeira; sentido de abertura revisado.

5. Lajes e forro
   - Lajes estruturais separadas dos pisos de acabamento; forros com altura e tipo por ambiente.
   - Checagem: furos para escadas e shafts; pe-direito livre conforme projeto.

6. Escadas
   - Escada por componente, com niveis base e topo corretos.
   - Checagem: espelho e piso conforme norma (NBR 9050 e codigo local) [CONFIRMAR]; guarda-corpo e corrimao presentes.

7. Telhado
   - Inclinacao, beirais e tipo de cobertura definidos.
   - Checagem: encontro com paredes sem frestas; platibandas e rufos quando houver.

8. Complementos
   - Mobiliario fixo, loucas, equipamentos, guarda-corpos, rampas e demais itens do escopo.
   - Checagem: itens no nivel e na fase corretos.

9. Vistas e folhas
   - Plantas, cortes, elevacoes e 3D conforme o escopo [CONFIRMAR lista de vistas].
   - Template de vista, escala e filtros padrao; folhas com carimbo, numeracao e revisao corretos.
   - Checagem final: nenhuma vista fora de folha, sem elementos sem nome, tabelas atualizadas.

## Entrega
Ao final, devolva ao Lucas um resumo curto: o que foi modelado, premissas assumidas, pendencias e duvidas de projeto.
