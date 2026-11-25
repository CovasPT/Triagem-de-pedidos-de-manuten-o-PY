Triagem de pedidos de manutencao - Projeto de Inteligencia Artificial
=====================================================================

Grupo: (numero)
Elementos: (nome, numero) x 3

1. Versoes
   - Python: (preencher com a versao usada, ex.: 3.12)
   - Bibliotecas: ver requirements.txt (atualizar com as versoes efetivamente usadas:
     python -m pip freeze | findstr /I "pandas numpy matplotlib scikit-learn")

2. Organizacao esperada
   notebook.ipynb
   dados/
     treino.csv
     validacao.csv
     teste.csv
     rotulos_teste.csv
   README.txt
   requirements.txt

   Nota: os rotulos do teste foram fornecidos num ficheiro separado (rotulos_teste.csv).
   O notebook so os junta ao teste (por id_pedido) na seccao final, depois de a decisao
   estar fixada.

3. Como executar
   1) python -m pip install -r requirements.txt
   2) Abrir notebook.ipynb no Jupyter / VS Code com esse ambiente como kernel.
   3) Kernel > Restart & Run All. Todos os caminhos sao relativos a pasta do notebook.
