Consulta NETRIN
A consulta até o momento usa dados direto do ambiente de produção, então TOME CUIDADO.
Etapas:
1) Acesse Credenciados nomeadas (External Credentials) acesse  DWNetrinAuth e mude o Authorization colocando a chave valida do cliente : Bearer XPTO-XPTO-XPTO-XPTO
2) Depois de realizar o commit. Acesse o conjunto de permissão (Permission Sets) >> DW Credencias Netrin e de atribuição dos usuarios que desejam realizar a consulta.
3) No conjunto de permissão acesse o objeto account e de permissão nos campos que tenham o nome Netrin.
4) No momento o campo UF para ser preenchido é UF NETRIN ou o campo Documento (CPF/CNPJ), se deseja usar outro campo para preenchimento, acesse o fluxo DW Flow Selecao Consultas Negrin e mude no action DWNetrinSintegra e no fluxo DW Flow Consulta Netrin
mude a formula DWBillingStateLength e no DWNetrinSintegra, e por fim acesse o fluxo DW Flow Selecao Consultas Negrin V2 e mude a action DWNetrinSintegra
5) Verifique se deseja usar os botões que já estão prontos só incluir no layout da conta chamado Consulta Netrin, ou se deseja usar o gatilho da criação ativando ou desativando a trigger DW FL Trigger Consulta Netrin.
