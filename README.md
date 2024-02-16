# Hermodr - Mensageria

Abstrair envio de emails com react-email e Resend.

A ideia é abstrair o uso do react-email com resend para uma usabilidade mais “simples” o cara faz o cadastro com o github e cria os templates de emails usando uma interface visual dos componentes do react-email podendo customizar como quiser inclusive usando tailwind e para os envios ele irá cadastrar qual a chave da API do resend dele e para enviar o email ele vai enviar via http mesmo.

Dentro do cadastro ele pode ter 1 ou vários templates e 1 ou vários domínios e forneceremos uma chave de API de acesso por domínio (talvez, se quiser sim… ou 1 chave de acesso pro usuário msm) ele envia uma requisição HTTP pra uma rota com a chave no Bearer pra sabermos quem é e no corpo pra quem quer mandar o email, qual a msg e qual template já customizado ele quer usar…

Resumindo, login usando github (pq nosso alvo são os para devs), cadastro de templates de emails usando os componentes do react-email (pode ser um no-code/low-code, onde o cara clicka nos componentes que quer usar mas também fornecendo o código dos componentes permitindo a inserção e ou edição dos já selecionados) usando o envio de email do resend já que o cara vai cadastrar a chave da API deles do resend.
