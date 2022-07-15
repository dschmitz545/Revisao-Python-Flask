# Curso da Twitch Codeshow python e flask
[PlayList Curso na Twitch](https://www.twitch.tv/collections/gRe7fj7iGBZJMQ)

### Pontos interresantes a serem lembrados

- WSGI = servidor já embutido no python
- Gunicorn = servidor de aplicação para python
- Não é uma boa pratia, fazer pip freeze ou pip list para preencher o requirements.txt
- Factorys = funções ou classes que podem ser invocadas no futuro, melhor jeito de trabalhar com flask
- Convenções = chamar de create_app a factory principal, chamar de init_app a factory de cada uma das extenções separadamente
- Nunca usar import app em outros arquivos, no máximo o import create_app, a não ser em casos especificos de teste.