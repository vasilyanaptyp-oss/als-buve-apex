# alsbuve.lv (apex) → https://www.alsbuve.lv

The site itself lives in `als-buve` on www.alsbuve.lv. GitHub issued the certificate of that repo for www only (27.10.2026),
so https://alsbuve.lv showed a *.github.io certificate. This repo claims the apex on its own, gets its own certificate and
sends every path to the same path on www (index.html and 404.html, JavaScript plus a meta refresh fallback).
