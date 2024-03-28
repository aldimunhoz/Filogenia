# Fiologenia
Passo a passo para construção de arvore filogenética usando o mafft e o iqtree.

# Requisitos
1- Arquivo Multifasta  
2-Instalar ou acessar os sofwtares Mafft(on-line ou desktop), Aliview, IQ-TREE e iTol (on-line)  


# Arquivo Multifasta
1- Entra no site do Ncbi https://www.ncbi.nlm.nih.gov/nuccore/  
2- Digita o ornagnismo desejado e procura na opção nucleotídeo  
3- Abre a sequência no  formato fasta, copia e colo no bloco de notas, salva no extensão .fa ou .fasta  

# Alinhamento (TERMINAL)
1- Abrir o  terminal  
2- Criar diretório e mover arquivo multifasta  
3- Baixar o MAFFT usando o comando sudo apt install mafft  
4- Digitar mafft  
5- Irá abrir as configurações, indicar o arquivo de input, nomear o arquivo de output 
6- Definir parametros (formato de output => fasta, output order; estratégia => auto)

# Visualização e Trimming 
1- Visualizar o arquivo do output no AliView  
2- Fazer trimming das sequencias, se necessário  

# Filogenia 
1- Fazer upload do arquivo novo no ternimal ou servidor  
2- Baixar o IQ-TREE 
3- Usar o comando iqtree -s arquivo -m mfp -b1000 -t5 
