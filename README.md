# charmepisos.com.br

Landing page de orçamento da Charme & Pisos. Estática, publicada pelo GitHub Pages a partir da pasta `docs/`.
Substitui o site antigo que estava na HostGator.

## Como atualizar
1. Edite `C:\Users\DELL\Documents\CharmeCRM\site\landing.html` (as imagens ficam em `site\img`).
2. Rode `python publicar.py` nessa mesma pasta. Ele recria `docs/` aqui: copia o logo, reduz as imagens,
   põe ícone, imagem de compartilhamento e o arquivo CNAME.
3. Faça commit e push deste repositório. O GitHub Pages atualiza sozinho em 1–2 minutos.

Não edite `docs/` à mão: o próximo `publicar.py` apaga e recria a pasta.

## Domínio
`docs/CNAME` = charmepisos.com.br.
No DNS do domínio: 4 registros A (185.199.108–111.153) e CNAME `www` → `arrudaaldo.github.io`. MX/SPF do Titan (e-mail) não mexer.
O formulário e os botões não gravam nada: só abrem o WhatsApp (41) 99728-7915 com a mensagem pronta.
