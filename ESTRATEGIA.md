# Estratégia de Testes - Campo de Senha (8-16 caracteres)

O Cenário: Você vai mapear os testes para um campo de "Criação de Senha".

Regra de Negócio: A senha deve ter no mínimo 8 caracteres e no máximo 16 caracteres.


Teste 1: 7 caracteres (Limite inferior - 1): Deve ser rejeitado.

Teste 2: 8 caracteres (Limite inferior exato): Deve ser aceito.

Teste 3: 16 caracteres (Limite superior exato): Deve ser aceito.

Teste 4: 17 caracteres (Limite superior + 1): Deve ser rejeitado.

## 1. Análise de Valor Limite (Foco Técnico)
- [ ] 7 caracteres: Rejeitar (Borda externa inferior)
- [ ] 8 caracteres: Aceitar (Borda interna inferior)
- [ ] 16 caracteres: Aceitar (Borda interna superior)
- [ ] 17 caracteres: Rejeitar (Borda externa superior)

## 2. Cenários Complementares (Funcional)
- [ ] Senha Vazia
- [ ] Caracteres Especiais (@#$%...)
- [ ] Combinação de Alfanuméricos

## 3. Heurística SFDPOT (Mentalidade Pleno)
- **Letra Escolhida:** D (Data)
- **Aplicação no Carrinho:** (Sua explicação aqui)

