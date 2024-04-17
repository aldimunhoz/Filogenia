# Fiologenia
Passo a passo para construção de arvore filogenética usando o mafft e o iqtree.

# Requisitos
1- Arquivo Multifasta  
2-Instalar ou acessar os sofwtares Mafft(web ou desktop), Aliview, IQ-TREE e iTol (web)  


# Arquivo Multifasta
1- Entra no site do Ncbi https://www.ncbi.nlm.nih.gov/nuccore/  
2- Digita o ornagnismo desejado e procura na opção nucleotídeo  
3- Abre a sequência no  formato fasta, copia e cola no bloco de notas, salva no extensão .fa ou .fasta  

# Alinhamento (TERMINAL)
1- Abrir o  terminal  
2- Criar diretório e mover arquivo multifasta  
3- Baixar o MAFFT usando o comando sudo apt install mafft  
4- Digitar mafft  
5- Irá abrir as configurações, indicar o arquivo de input, nomear o arquivo de output  
6- Definir parametros (formato de output => fasta, output order; estratégia => auto)

# Visualização e Trimming Alinhamento
1- Visualizar o arquivo do output no AliView  
2- Fazer trimming das sequencias, se necessário  

# Filogenia 
1- Fazer upload do arquivo novo no terminal ou servidor  
2- Baixar o IQ-TREE2  
3- Usar o comando iqtree2 -s arquivo -m MFP -B 1000 -T 5 

# Visualização Árvore
1- Entra no site https://itol.embl.de/  
2- Fazer o upload do arquivo de output do iqtree2 no formato .treefile  
3- Configurar a árvore no painel de controle, aba avançado, opção Midpoint root


