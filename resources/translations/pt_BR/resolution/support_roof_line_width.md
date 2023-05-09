Largura da linha do teto do suporte
====
As larguras das linhas do teto de suporte podem ser configuradas separadamente das larguras do restante das linhas de suporte.

<!--screenshot {
"image_path": "support_roof_line_width.png",
"models": [
    {
        "script": "trash_bin_lid.scad",
        "transformation": ["scale(0.5)"]
    }
],
"camera_position": [-47, 79, 110],
"settings": {
    "support_enable": true,
    "support_roof_enable": true,
    "support_roof_line_width": 0.8
},
"layer": 192,
"colours": 64
}-->
![As linhas do teto de suporte são mais largas do que o restante das linhas de suporte](../images/support_roof_line_width.png)

Imprimir o teto de suporte com linhas um pouco mais finas geralmente é vantajoso para a qualidade da superfície suspensa que ele suporta, puramente por ter uma superfície superior mais lisa acima da interface de suporte. No entanto, isso não aumenta necessariamente a adesão entre a interface de suporte e o modelo, de modo que o suporte não será necessariamente mais difícil de remover.

No entanto, imprimir as linhas do telhado muito finas causará extrusão irregular, o que reduz o efeito de suporte do telhado, causando uma pior qualidade de saliência. Isso também pode introduzir uma grande mudança na taxa de fluxo através do bocal, causando excesso de extrusão quando começar a imprimir o teto de suporte e falta de extrusão quando imprimir o que vier depois do teto de suporte.