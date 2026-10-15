# SSCONPAV · Rodovias — App de campo (APK)

App do apontador/encarregado: lança o **Relatório Fotográfico** (trechos com foto Antes/Depois, KM, sentido, largura) e a **Ordem de Serviço** do dia, com GPS, bússola e carimbo em cada foto. Funciona sem internet e sincroniza com o escritório.

- `index.html` — o app inteiro. Publicado em GitHub Pages: `https://SEU-USUARIO.github.io/ssconpav-rodovia-apk/`
- `versao.json` — versão publicada; o app compara com a sua `APP_VERSION` e se atualiza sozinho.
- `ssconpav-mobile/` — casca Android (Capacitor). O robô `build-apk.yml` gera o `SSCONPAV-Rodovias.apk`.

Tabela `rodovia_registros` e bucket `rodovia-fotos` no Supabase (SQL em `supabase_rodovia.sql`, no repositório do sistema).
**Não edite o `index.html` à mão**: ele é gerado por `_fabrica-rodovia/build.py`.

Login de demonstração (sem nuvem): usuário `ssconpav`, senha `Ssconpav`.
