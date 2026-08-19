# README.md.PedroFelix
# Atividade Avaliativa 1, Técnicas de Virtualização em Infraestrutura de TI

**Instruções:** cada questão vale 5,0 pontos. Marque a alternativa correta com um `x` dentro do checkbox (`- [x]`) e escreva sua justificativa no campo indicado.

---

**1.** Uma empresa tem 10 servidores físicos, cada um rodando uma única aplicação e usando, em média, 15% da capacidade de CPU. A empresa quer reduzir o número de servidores físicos, os custos de energia e climatização, sem perder o isolamento entre as aplicações. Qual técnica resolve esse problema?

- [ ] a) Comprar mais servidores físicos, um para cada nova aplicação
- [x] b) Consolidar as aplicações em múltiplas VMs, rodando em um número menor de hosts físicos, usando um hipervisor
- [ ] c) Desligar permanentemente as aplicações menos usadas
- [ ] d) Substituir os servidores físicos por notebooks comuns
- [ ] e) Virtualização não permite reduzir o número de servidores físicos

**Justificativa:** <A virtualização consolida múltiplas máquinas virtuais em menos servidores físicos, aproveitando a capacidade ociosa dos processadores e mantendo o isolamento, o que reduz custos de energia e refrigeração.>

**2.** Um data center de produção precisa do máximo desempenho possível para as VMs, com isolamento forte entre elas e sem depender de um sistema operacional hospedeiro rodando por baixo do hipervisor. Qual tipo de hipervisor é o mais adequado?

- [ ] a) Tipo 2 (hosted), pois é mais simples de instalar
- [x] b) Tipo 1 (bare-metal), pois roda diretamente sobre o hardware, sem SO hospedeiro intermediário
- [ ] c) Nenhum hipervisor é necessário, pois apenas containers resolvem isso
- [ ] d) Tipo 2, porque tem sempre melhor desempenho que o Tipo 1
- [ ] e) É indiferente: os dois tipos entregam o mesmo desempenho em produção

**Justificativa:** <O hipervisor Tipo 1 roda direto no hardware, sem a sobrecarga de um sistema operacional hospedeiro, garantindo menor latência, isolamento forte e desempenho máximo em produção.>
