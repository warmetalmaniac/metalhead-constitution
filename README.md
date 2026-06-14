from pathlib import Path

html_content = """
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Constituição do Metalhead Caótico</title>
<style>
body {
    background-color: #0b0b0b;
    color: #e6e6e6;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    padding: 20px;
}
h1 {
    color: #ff0000;
    text-align: center;
}
h2 {
    color: #ff4444;
}
section {
    margin-bottom: 25px;
    border-left: 3px solid #ff0000;
    padding-left: 10px;
}
</style>
</head>
<body>

<h1>📜 Constituição Oficial do Metalhead Caótico™</h1>

<section>
<h2>Artigo 1 — Código do Headbang</h2>
<p>Qualquer tentativa externa de impedir o headbang durante um riff pesado é considerada sabotagem sonora.</p>
</section>

<section>
<h2>Artigo 2 — Volume Sagrado</h2>
<p>O volume mínimo aceitável para metal é quase sendo investigado por perturbação da realidade local.</p>
</section>

<section>
<h2>Artigo 3 — Santíssima Escala Gutural</h2>
<p>1. Grave<br>2. Mais grave ainda<br>3. Entidade não humana</p>
</section>

<section>
<h2>Artigo 6 — Lei Anti-Poser</h2>
<p>Quem não reconhecer ao menos um artista com mais de 10.000 ouvintes mensais deve entrar em ritual de purificação ouvindo Antidemon até atingir compreensão mínima do caos musical.</p>
</section>

<section>
<h2>Artigo 7 — Parágrafo 3</h2>
<p>Durante sessões de jogos como Minecraft, Terraria e similares, é permitido ouvir músicas indies sem perda de pontos de metal.</p>
</section>

<section>
<h2>Artigo Final</h2>
<p>O riff manda. O headbang obedece. O poser sofre.</p>
</section>

</body>
</html>
"""

file_path = Path("/mnt/data/constituição_metalhead_caotico.html")
file_path.write_text(html_content, encoding="utf-8")

file_path.name
