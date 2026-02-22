# CTFR

### ¿Extrañas la técnica AXFR? Esta herramienta permite obtener los subdominios de un sitio web HTTPS en pocos segundos.

#### ¿Cómo funciona? CTFR no utiliza ataques de diccionario ni fuerza bruta, simplemente abusa de los registros de Certificate Transparency. Para más información sobre los registros CT, consulta www.certificate-transparency.org y crt.sh.Primeros pasosPor favor, sigue las instrucciones a continuación para instalar y ejecutar CTFR.Requisitos previosAsegúrate de tener instaladas las siguientes herramientas:Python 3.0 o posterior.

## Instalación

```bash $ git clone https://github.com/SamaelAS/Sdominio```

```bash $ cd Sdomin```

```bash $ pip3 install -r requirements.txt```

## Ejecución

```bash $ python3 ctfr.py```
--help Uso Parámetros y ejemplos de uso.Parámetros-d --domain [dominio_objetivo] (obligatorio)
-o --output [archivo_salida] (opcional)```

## Ejemplos$  

```bash $ python3ctfr.py -d starbucks.com```

```bash python3 ctfr.py -d facebook.com -o /home/shei/subdomains_fb.txt```
