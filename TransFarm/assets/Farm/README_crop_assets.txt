Trans-Farm crop asset setup
============================

Use ONE farm-plot base image as a persistent background layer:
    assets/Farm/farm_plot_base_v2.png

Each crop has independent transparent overlay assets:
    <crop>_stage_1.png
    <crop>_stage_2.png
    <crop>_stage_3.png
    <crop>_seeds.png
    <crop>_harvest.png

Do not bake crop art into the plot image. The plot base stays fixed and the
game swaps only the crop overlay when growth changes. All stage images use the
same 512x512 transparent canvas and are bottom-aligned to a consistent soil
line so the same plot-center coordinates can be reused for every crop.

Current crop slugs:
    hay
    carrot
    strawberry
    corn
    pumpkin
    vegetable_lamb
    cloudberry
    dragon_pepper
    bimberry
    succuberry
