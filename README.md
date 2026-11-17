# 1. Inicializar e fazer o primeiro commit
git init
git branch -M main
git add .
git commit -m "Fábrica de Corpus Bairro em Dia: pipeline, teste e diálogos-semente"

# 2. Conectar ao GitHub e enviar (troque SEU_USUARIO)
git remote add origin https://github.com/SEU_USUARIO/bairro-em-dia-corpus.git
git push -u origin main
