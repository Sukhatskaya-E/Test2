# Виртуальная среда "test2_env"

## Сборка: 
```
name: test2_env
channels:
  - bioconda
  - conda-forge
  - defaults
dependencies:
  - bwa-mem2
  - multiqc
  - samtools
  - picard
```

Перед созданием убедиться, что установлен менеджер пакетов Conda (в составе Anaconda или Miniconda).  
  
Сохранить файл test2_env.yml в рабочей директории.

## Создание:
  
 `conda env create -f test2_env.yml`  

## Активация:
   
 `conda activate test2_env`