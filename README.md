# otodm-runner

Instagram "yorumlara X yaz" -> DM otomasyonu. GitHub Actions'ta 7/24 calisir (public repo: Actions dakikasi ucretsiz).
Ana proje ozel repoda; bu repo yalniz `scripts/instagram.py` kopyasini ve `otodm.yml` is akisini tasir. Kod sirri yok:
anahtarlar repo secret'larinda (IG_TOKEN, IG_USER_ID, IG_KULLANICI, OTODM_JSON).

- Kurallari guncelle: `gh secret set OTODM_JSON -R Tunacodin/otodm-runner < yerel/instagram/otodm.json` (ana repo kokunden)
- instagram.py degisirse: ana repodan buraya kopyala, commit, push.
