# dawe2026cicd2
## Pràctica RA6 CI/CD intro
### Algunes comandes que podriem necessitar:

```
docker compose down
docker compose build --no-cache
docker compose up
```

Lukas Cea
L'aplicació és un gestor de tasques estructurat en tres seccions principals: un formulari per afegir noves tasques i dues llistes per visualitzar les tasques pendents i les completades. El CSS s'organitza mitjançant variables personalitzades (:root) per centralitzar els estils i utilitza un disseny responsive amb flexbox per adaptar-se a diferents dispositius. Per la seva part, el JavaScript gestiona la interactivitat permetent afegir, marcar o desmarcar tasques, i utilitza el localStorage per guardar les dades de manera que es mantinguin en refrescar la pàgina.