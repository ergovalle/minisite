# Ergo Valle Editora — One Page v4 (imagens reais + mobile)

Atualização feita com as imagens reais enviadas: capa completa, lombada, logo da Ergo Valle e foto do autor.

Principais mudanças:
- capa do eBook substituída por recorte real da capa enviada;
- seção nova com prévia da futura edição física: capa completa + lombada;
- logo real da Ergo Valle no topo;
- foto real do autor na seção “Autor e fundador”;
- ajustes de CSS para celular sem prejudicar desktop.

Publicação:
```bash
cd ~/Downloads
unzip Ergo_Valle_Editora_OnePage_v4_imagens_reais.zip -d ergovalle-site-v4
cd ~/minisite
cp -r ~/Downloads/ergovalle-site-v4/ergovalle_onepage_v4_imagens_reais/* ~/minisite/

git add .
git commit -m "Atualiza Ergo Valle com imagens reais e versão mobile"
git push origin main
```
