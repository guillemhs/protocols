# M1.771 - Privadesa
----

Si queréis acceder a la versión en castellano de este README, haced click [aquí](IB-README.md).

# Notebooks d'exercicis resolts de protocols criptogràfics

Aquest repositori conté un conjunt de *notebooks* de jupyter amb activitats sobre protocols criptogràfics que preserven la privadesa. Els *notebooks* contenen tant els enunciats de les activitats, com una proposta de solució, que podeu fer servir per comparar-la amb les vostres respostes.

El repositori conté les activitats en un únic fitxer de Jupyter *notebooks*. Les activitats estan dissenyades per a resoldre-les dins del propi *notebook*, implementant fragments de codi en **Python**.

## Preparació de l'entorn

Per tal d'executar els *notebooks* amb les activitats, necessitareu:
* una instal·lació de `python3` amb algunes llibreries addicionals i 
* el programari `jupyter`. 

### Instal·lació de python3

Descarregueu i instal·leu `python3` per al vostre sistema operatiu.

Si treballeu en una distribució linux basada en debian, podeu fer:

```
$ sudo apt-get install python3
```

### Instal·lació de dependències

Instal·leu les llibreries addicionals necessàries per a les activitats, que es troben especificades al fitxer `requirements.txt` executant des de dins de la carpeta del repositori:

```
$ pip install -r requirements.txt
```

### Instal·lació de jupyter

Les activitats es presenten com a un conjunt de *notebooks* de jupyter. Instal·leu el programari jupyter seguint les indicacions de la [web oficial](https://jupyter.org/install)

## Execució dels notebooks

Una vegada tingueu el programari instal·lat, inicieu jupyter i obriu els *notebooks* amb les activitats:

```
jupyter notebook
```
