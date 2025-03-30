# 🖨️ 3D-Druck Preisrechner (Docker)

Ein einfacher, webbasierter Preisrechner für deine 3D-Druck-Projekte, bereitgestellt über Docker mit Nginx.

---

## 🚀 Schneller Start

### Schritt 1: Repository klonen

```bash
git clone https://github.com/ra5on/3d-druck-rechner.git
cd 3d-druck-rechner
```

### Schritt 2: Docker Compose starten

```bash
docker compose up -d
```

Der Rechner ist anschließend über [http://localhost:4000](http://localhost:4000) erreichbar.

---

## 🗂️ Verzeichnisstruktur

```
3d-druck-rechner/
├── docker-compose.yml
└── www/
    └── index.html
```

- `docker-compose.yml` startet einen Nginx-Webserver im Docker-Container.
- `www/index.html` enthält den eigentlichen 3D-Druck Preisrechner als HTML-Datei.

---

## 🐳 Docker-Details

| Service | Port      | Beschreibung    |
|---------|-----------|-----------------|
| web     | `4000:80` | Nginx-Webserver |

---

## 🔧 Anpassungen

- Tausche die Datei `index.html` mit deiner eigenen Version aus, um Änderungen vorzunehmen oder den Rechner anzupassen.
- Den Port kannst du in der Datei `docker-compose.yml` nach deinen Wünschen anpassen.

---

## 📌 Voraussetzungen

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

## 💡 Hilfreiche Befehle

### Logs anzeigen:
```bash
docker compose logs -f
```

### Container stoppen:
```bash
docker compose down
```

---

## ⚖️ Lizenz

Dieses Projekt steht unter der [MIT-Lizenz](LICENSE).

---

## 🙋 Autor

**Patrick Joost**

---

Viel Spaß beim Drucken! 🎉
