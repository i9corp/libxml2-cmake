Preparando o ambiente
===========================================

Para compilações no Windows é necessário, configurar o a libxml2 para isso após fazer o download da bilioteca
<pre>
    git submodule update --init --recursive
</pre>

Entre no diretório third-party/libxml2/win32 e execute o seguinte comando

<pre>
cscript.exe win32/configure.js
</pre>

Após executar o comando o sistema ira criar os demais arquivos necessários para o seu projeto compilar.

Atenção, É necessário configurar o projeto antes de compilar


Pós compilação
===========================================

Após compilado as bibliotecas irão para a pasta lib