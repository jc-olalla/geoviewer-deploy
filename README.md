# GeoViewer Deploy

This repository ties together the full GeoViewer stack: frontend, API, and database.

## 🔧 Setup

1. **Clone this repository**

```bash
git clone --recurse-submodules git@github.com:jc-olalla/geoviewer-deploy.git
```

2. **Edit database layers**
For example:

```bash
echo "https://mywmsservice/..." >> geoviewer-db/sample_layers.txt
```

3. **Build**

```bash
docker-compose up --build
```


