<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img src="./assets/banner-light.svg" width="100%" alt="ISEM – Institut für Smarte Entwicklung und Maschinenelemente, Technische Universität Hamburg">
</picture>

<br>

<a href="https://www.tuhh.de/isem/willkommen"><img src="https://img.shields.io/badge/Webseite-tuhh.de%2Fisem-0b2545?style=flat-square" alt="Webseite des Instituts"></a>
<a href="https://www.tuhh.de/isem/en/welcome-1"><img src="https://img.shields.io/badge/Website-English-0b2545?style=flat-square" alt="Englischsprachige Webseite des Instituts"></a>
<a href="https://isem-karriere.de"><img src="https://img.shields.io/badge/Karriere%20%26%20Abschlussarbeiten-isem--karriere.de-00879a?style=flat-square" alt="Karriere und Abschlussarbeiten am ISEM"></a>

<br><br>

Willkommen beim **Institut für Smarte Entwicklung und Maschinenelemente (ISEM)** der Technischen Universität Hamburg.<br>
Hier veröffentlichen wir Open-Source-Projekte aus Forschung, Lehre und studentischen Abschlussarbeiten –<br>
von Maschinenelementen über Methoden der Produktentwicklung bis zur Software.

</div>

---

## Software-Projekte

### Billard-Demonstrator „Billard@ISEM“

Ein Billard-Roboter aus einzelnen, vernetzten Modulen: Die Kamera erkennt die Kugeln, das Spielmodul steuert den Ablauf, der Beamer projiziert direkt auf den Tisch.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/billard-game-module"><b>billard-game-module</b></a><br>
      Spielmodul: Ablaufsteuerung (Scheduling) und Kommunikation zwischen den Modulen, inklusive Weboberfläche für die Spielmodi.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/billard-game-module?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/billard-camera-module"><b>billard-camera-module</b></a><br>
      Computer-Vision-System für 8-Ball-Pool mit Raspberry Pi 5, HQ Camera und eigens trainierten YOLO-Modellen zur Detektion und Klassifikation.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/billard-camera-module?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/billard-beamer-module"><b>billard-beamer-module</b></a><br>
      Beamer über dem Tisch: projiziert Bilder perspektivisch entzerrt auf die Spielfläche und gibt optional Ton aus.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/billard-beamer-module?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/billard_base_module"><b>billard_base_module</b></a><br>
      Gemeinsame Basisklasse der Module: API-Grundgerüst, Laden von Konfiguration und Secrets sowie Download-Seite für gespeicherte Dateien.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/billard_base_module?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
  </tr>
</table>

### Vorlagen für Abschlussarbeiten & Promotion

<table>
  <tr>
    <td width="100%" valign="top">
      <a href="https://github.com/ISEM-TUHH/dissertationsvorlage"><b>dissertationsvorlage</b></a><br>
      Satzvorlage der Reihe „Forschungsberichte des ISEM“: Dissertation nach TUHH-Formalia setzen, als Buch drucken lassen und online bereitstellen – aus einer Quelle entstehen Druck-, Online- und Archivfassung.<br><br>
      <img src="https://img.shields.io/badge/Typst-239DAD?style=flat-square&logo=typst&logoColor=white" alt="Typst">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/dissertationsvorlage?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
  </tr>
</table>

### Methoden & Werkzeuge

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/spalten"><b>spalten</b></a><br>
      SPALTEN-Problemlösung (Albers et al.) als Claude-Code-Skill: sieben Module von der Situationsanalyse bis zum Lernen, mit Informationscheck zwischen den Modulen und Gates, an denen ein Mensch entscheidet.<br><br>
      <img src="https://img.shields.io/badge/Claude%20Code-Skill-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude-Code-Skill">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/spalten?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ISEM-TUHH/SheetGen"><b>SheetGen</b></a><br>
      Pipeline zur Erzeugung synthetischer 2D-Blechteilgeometrien als skalierbare Trainingsdaten für ML-gestütztes Stanzen und Umformen.<br><br>
      <img src="https://img.shields.io/badge/Machine%20Learning-Datensatz-6e7781?style=flat-square" alt="Machine Learning, Datensatz">
      <img src="https://img.shields.io/github/stars/ISEM-TUHH/SheetGen?style=flat-square&label=Stars" alt="GitHub-Stars">
    </td>
  </tr>
</table>

<details>
<summary><b>Archiv</b></summary>
<br>
<table>
  <tr>
    <td width="100%" valign="top">
      <a href="https://github.com/ISEM-TUHH/Miro-API"><b>Miro-API</b></a><br>
      Experimentierumgebung für die Miro API (archiviert, wird nicht mehr gepflegt).<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Status-archiviert-6e7781?style=flat-square" alt="Status: archiviert">
    </td>
  </tr>
</table>
</details>

---

## Mitmachen & Abschlussarbeiten

Viele der Projekte hier sind in studentischen Arbeiten entstanden – das Kameramodul des Billard-Demonstrators zum Beispiel im Rahmen einer Bachelorarbeit. Offene Themen für Bachelor- und Masterarbeiten sowie Stellen am Institut gibt es auf **[isem-karriere.de](https://isem-karriere.de)**.

Fehler gefunden oder eine Idee? Issues und Pull Requests in den jeweiligen Repositories sind willkommen.

---

<div align="center">
<sub>Institut für Smarte Entwicklung und Maschinenelemente · Technische Universität Hamburg<br>
<a href="https://www.tuhh.de/isem/willkommen">Webseite</a> · <a href="https://isem-karriere.de">Karriere</a> · Dieses Profil wird im Repository <a href="https://github.com/ISEM-TUHH/.github">.github</a> gepflegt.</sub>
</div>
