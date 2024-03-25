---
description: Manual d'usuari per a les programacions
---

# Manual d'Usuari

Aquesta es la documentació que inclou el manual d'usuari per a la **Aplicació per a la Gestió de les Programacions del CIP FP de Batoi**

* [1. Accés a la Plataforma](./#1-accés-a-la-plataforma)
* [2. Dintre de l'aplicació](./#2-dintre-de-laplicació)
  * [2.1. Panell Esquerre](./#21-panell-esquerre)
  * [2.2. Panell Dret](./#22-panell-dret)
* [3. Cicles](./#3-cicles)
  * [3.1. Crear Cicles](./#31-crear-cicles)

## 1. Accés a la Plataforma

Per accedir a la plataforma hem d'escriure al nostre navegador favorit la següent url: [https://programacions.cipfpbatoi.es/](https://programacions.cipfpbatoi.es/). Una vegada hem accedit, s'ens mostrarà el panell d'autenticació:

![Pantalla de Login](md\_media/login\_.png)

Hem d'escriure les dades d'accés tal i com ens hagen indicat, en el meu cas, em registraré com el meu usuari amb la meua contrasenya i farem clic en _Entrar_.

![Login amb Dades](md\_media/login\_amb\_credencials.png)

## 2. Dintre de l'aplicació

Depenent del tamany inicial i del vostre usuari, veureu diferents coses. Per a treballar sobre el mateix esquema, deveu de maximitzar al màxim el navegador de forma que es veja la pantalla amb aquesta disposició:

![Pantalla Inicial](md\_media/pantalla\_inicial.png)

Principalment es tracta d'un CRUD (Create - Read - Update - Delete). Al panell **esquerre**, que és proporcionalment més xicotet que l'àrea principal, es mostren tots els ítems que podem modificar. A l'**àrea principal**, veurem el contingut relacionat amb l'ítem seleccionat, sobre el qual podrem treballar.

### 2.1. Panell Esquerre

![Panell Esquerre](md\_media/panel\_izquierdo.png)

Tal com podem observar en aquest panell, podem navegar per les diferents àrees en les que podem travallar. En el cas de l'usuari amb que està fent-se el manual, es poden revisar moltes àrees. Quan es clica el botó **Inici** es torna a l'àrea inicial d'edició. Les àrees més importants per a actualitzar la normativa i els continguts dels mòduls, son les següents:

1. **Cicles**: Aquesta secció ens permet treballar amb els cicles incloent informació important com família professional, Real Decret que el regula, etc.
2. **Mòduls**: Una vegada definitis els cicles, podem crear els mòduls i establir els resultats d'aprenentatge i els continguts per a cadascun d'ells.

>

### 2.2. Panell Dret

Les seccions **Cicles** i **Mòduls** tenen pràcticament els mateixos elements de navegació, a continuació s'adjunta una captura de pantalla que ens permetrà explicar les operacions comuns que podem fer en cadascun dels panells:

![Secció de Cicles](md\_media/seccio\_cicles\_marcada.png)

1. **Cercador**: Ens permet realitzar recerques a la secció a la que ens trobem per a facilitar-nos trobar el item amb que vulguem treballar.
2. **Usuari**: Ens permet tancar la sessió si fem clic a l'usuari. L'enganatge en canvi, ens permet alternar entre el tema fosc i el tema clar.
3. **Filtres i Crear**: El primer ens permet filtrar per qualsevol dels camps que es mostren (Aquesta característica està en desenvolupament). D'aquesta manera s>ols veurem els registres que coincideixen amb el filtre que hem definit. En funció dels nostres privilegis veurem un botó per a crear nous elements, per exemple cicles o mòduls.
4. **Ordenació**: Aquestes fletxes ens permiteixen ordenar els registres mostrats pel camp elegit, de manera alfabètica de forma ascendent o descendent.
5. **Més Opcions** Aquests tres punts ens permiteixen treballar en el registre en concret i realitzar operacions sobre ell.

## 3. Cicles

Quan seleccionem l'opció **Cicles** se'ns mostra la següent informació:

![Cicles Informàtica](md\_media/seccio\_cicles\_informatica.jpeg)

Aquest panell ens permet crear nous cicles i actualitzar tota la informació necessària respecte a ells. Ara, en la última versió, quan accedim sols sens mostren els cicles del **nostre departament**.

Quina informació del cicle podem veure?:

1. **Nom curt** Nom curt del cicle, inclou si es un cicle formatiu de grau superior, Inicials del cicle i legislació per a diferenciar si es tracta d'un cicle LOE o LOGSE, per exemple: En el cas del: _Cicle Formatiu de Desenrotllament d'aplicacions Multiplataforma_ el nom curt seria: **CFS DAM (LOE)**
2. **Nom Complet** Nom tal com ve en el Reial decret que el defineix.
3. **Real Decret de títol** Real decret en el que es defineix el títol.
4. **Ordre de Currículum** Si hi ha Ordre de la Generalitat Valenciana que concrete el currículum de la titulació definida pel real decret.
5. **Actualització del Real Decret de títol (Si Existeix)** Si hi ha cap actualització del títol, estaria a aquest apartat.
6. **Departament** Departament al que pertany el títol.

Quines opcions tenim disponibles per a treballar amb els cicles?(Aquestes opcions les podem veure dalt a la dreta, just baix del nostre identificador)

![Opcions a la pantalla principal dels cicles](md\_media/seccio\_cicles\_opcions.png)

* Opció **Filtros**: Actualment ens permeteix filtrar pels camps _Nom Curt_ i _Nom Complet_ del cicle per a que ens siga més fàcil buscar l'opció en la que volem treballar.
* Opció **Crear Cicles**: Quan prenem aquest botó ens mostra el panell per a crear cicles que es descriurà posteriorment.
* Opció **...**: Al polsar el aquest botó sens mostren dos noves opcions:
  * **Ver**: En permet visualitzar tota la informació del cicle **incloent els mòduls professionals donats d'alta** a l'aplicació i hiperenllaçats, de forma que si polsem dins d'aquest ens durà al panell de visualització del mòdul professional. En aquest panell, dalt a la dreta, tenim dues noves opcions que ens permeten **Volver al listado** en el que es mostren tots els mòduls o **Modificar** la informació relativa a la identificació del cicle formatiu.
  * Opció **Modificar**: Ens permet modificar la informació de identificació del cicle. Dal a la dreta, tenim opcions per a **Guardar i seguir editando** amb el desariem els canvis i seguiriem editant i per a **Guardar Cambios** amb el que desariem els canvis i tancariem el panell d'edició tornant al llistat de cicles.

### 3.1. Crear Cicles

Per a crear cicles hem de premer el botó **Crear Cicles** i sens mostrarà un panell on hem d'emplenar els següents camps:

![Creació d'un cicle nou](md\_media/cicle\_nou.png)
