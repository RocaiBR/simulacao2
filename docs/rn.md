## 3. Regras de Negócio (RN)

### RN01 — Maioridade
Para criar uma conta, o usuário deve ter mais de 18 anos.

### RN02 — Bloqueio por inatividade
Usuários inativos por mais de 90 dias devem ser marcados como inativos.

### RN03 — Limite de tentativas de login
Após 5 tentativas inválidas, a conta deve ser temporariamente bloqueada.

### RNF04 — Disponibilidade
O sistema deve ficar disponível 99,5% do tempo, excluindo manutenções programadas.

### RNF05 — Escalabilidade
O sistema deve suportar até 5.000 usuários simultâneos sem perda de desempenho.

### RNF06 — Backup automático
O sistema deve realizar backup automático do banco de dados a cada 24 horas.

### RNF07 — Criptografia
Os dados pessoais dos usuários devem ser armazenados de forma criptografada no banco de dados.

### RNF08 — Acessibilidade
O sistema deve seguir as diretrizes WCAG 2.1 para garantir acessibilidade a usuários com deficiência.
