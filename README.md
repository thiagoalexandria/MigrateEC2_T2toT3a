A familia T3a é uma fámilia mais nova e com um custo bem inferior a antiga T2. Para que possamos migrar a família sem maiores problemas é necessário a atualização do drive de rede ENA e que habilitemos na máquina o ENA Support para a mesma. Esse playbook faz toda a parte de atualização e migração de instância de forma atumática.

```
ansible-playbook -i hosts main.yml
```
