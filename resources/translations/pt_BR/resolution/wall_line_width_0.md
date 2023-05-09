Largura de extrusão da parede externa
====
A largura da linha da parede externa pode ser ajustada separadamente das paredes internas. Essa configuração indica a largura da linha da parede externa.

<!--screenshot {
"image_path": "wall_line_width_0.png",
"models": [{"script": "hive.scad"}],
"camera_position": [-31, -31, 147],
"settings": {
    "wall_line_count": 2,
    "wall_line_width_0": 0.8
},
"colours": 64
}-->
![O contorno da parede externa é muito mais largo do que o restante](../images/wall_line_width_0.png)

A redução da parede externa para uma largura de linha ligeiramente abaixo do tamanho do bocal é conhecida por ser benéfica para a resistência. O bocal extrudará um pouco menos de material, mas sua abertura se sobreporá à parede interna adjacente. Isso faz com que o material seja empurrado para o lado pela parede colocada anteriormente em seu local adequado. Mas isso também fará com que o plástico se funda melhor com as paredes adjacentes. Isso permite que a parede externa se funda melhor com as paredes internas, de modo que elas possam combinar sua resistência. Isso melhora muito a resistência das paredes.

A redução da largura da linha da parede externa também permite que o bocal imprima detalhes mais finos, pois a linha mais fina se ajustará melhor aos detalhes pequenos.

Aumentar a largura da linha da parede externa pode reduzir o tempo de impressão. É possível obter uma parede com espessura semelhante com menos paredes internas. A resistência ainda será um pouco reduzida porque a parede externa não se fundirá tão bem com as paredes internas.

<!--if cura_version>=5.0-->
Em peças finas, a largura da linha será ajustada automaticamente para se adequar à largura local da peça. Não há necessidade de garantir que a largura da peça seja um múltiplo da largura da linha. O [Ângulo-limite de transição da parede](../shell/wall_transition_angle.md) determina onde a largura da linha é ajustada automaticamente em cantos agudos. A [Largura mínima da linha da parede](../shell/min_wall_line_width.md) determina o quanto elas podem ser ajustadas em cada direção.
<!--endif-->

<!--if cura_version<5.0:
Ajuste de linhas
----
Ao imprimir peças finas, o ajuste das configurações de largura da linha da parede é uma ferramenta importante para obter peças precisas e resistentes. O Cura só desenhará contornos completos, portanto, se um contorno não se encaixar, haverá uma lacuna nas paredes, o que compromete muito a resistência e a precisão da peça.

O Cura tentará preencher essas lacunas entre as paredes se a opção [Preencher lacunas entre paredes](../shell/fill_perimeter_gaps.md) estiver ativada, mas essa técnica não é ideal para formas arbitrárias e geralmente leva muito tempo de impressão. Quando duas paredes se sobrepõem, o recurso [Compensar sobreposições de parede](../shell/travel_compensate_overlapping_walls_enabled.md) reduzirá a largura da linha da parede para garantir que a peça seja dimensionalmente precisa, mas isso incorre em alterações de fluxo que também reduzem a qualidade e a resistência da impressão.

Para um ajuste ideal, você deseja que a peça seja um múltiplo exato da largura da linha da parede, de modo que as paredes se encaixem precisamente dentro da peça. Se você souber qual é a largura da peça, isso pode ser feito facilmente ajustando a largura das paredes. Primeiro você vê quantos contornos deseja ajustar de modo que as linhas ainda tenham uma largura razoável. Em seguida, você pode ver o quanto precisa ajustar a largura da linha da parede para que as linhas se encaixem corretamente. Lembre-se de que você pode ajustar a [Largura da linha da parede externa](wall_line_width_0.md) e a [Largura da linha da parede interna](wall_line_width_x.md) separadamente. Conte cuidadosamente quantas vezes cada tipo de parede será desenhado para prever o efeito da alteração da largura da linha da parede.

O ajuste de linhas de parede é uma habilidade importante para a impressão 3D que distingue os operadores de impressoras 3D especializados dos demais. É necessário praticar um pouco.
-->