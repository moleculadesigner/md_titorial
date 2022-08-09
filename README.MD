# Семинар по запуску симуляции комплекса белка с лигандом в Gromacs
В рамках семинара изучим:
1. Как параметризовать белок полем CHARMM
1. Как параметризовать лиганд полем CHARMM (CGenFF)
1. Как подготовить входные файлы для MD
1. Как поставить вычисления в очередь на HPC-кластере
1. Что можно узнать из тракетории

Команды и рекомендации описаны в [ноутбуке](BCD%20MD%20Tutorial.ipynb).
Перед запуском ноутбука нужно поставить и активировать окуружение конды:
``` shell
conda env create -f env/md-tutorial.yml
conda activate md-tutorial
jupyter notebook
```

Для связи:
- iakovlevda@biocad.ru
- tg: [@diazepunk](https://t.me/diazepunk)