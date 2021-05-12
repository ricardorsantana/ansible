<h2> Anotações </h2>

Exemplos de Playbook para uso no Fortigate.



<h2> Lista de Arquivos:</h2>
<b> - inventario -> </b> Arquivo de inventário utilizado para "atacar" o fortinet.

<b> - teste.yml -> </b> Exemplo de Playbook que utilizei para "atacar" o fortinet via SSH, usando o modulo/comando raw.

Nota: como o fortigate tem um SSH emulado, a melhor forma de executar um comando (quando não se tem modulos já prontos) na console é utilizando o RAW.
             

<h3> Para rodar o teste direto no terminal utilize o comando:</h3>
ansible-playbook -i inventario teste.yml -vvv
