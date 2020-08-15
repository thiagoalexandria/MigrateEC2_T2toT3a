Para que possamos migrar a instância entre as familias T2 e T3a é necessário que antes realizemos a atualização do dirver ENA e habilitemos o Ena Support para a mesma, dessa forma esse playbook faz toda a parte de atualização e migração de instância de forma atumática.

```
ansible-playbook -i hosts main.yml
```
