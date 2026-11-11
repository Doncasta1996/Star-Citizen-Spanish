# 🚀 Star Citizen en español

Traducción de los textos de **Star Citizen al español de España**, compatible con **LIVE y PTU**.

<!-- sc-versions:start -->
## 📥 Descarga disponible

| Canal | Versión compatible |
|---|---|
| **LIVE** | **4.10.2-LIVE.12913470** |
| **PTU** | **4.10.3-PTU.13160301** |

**Última actualización de la traducción:** 11/11/2026.

### [⬇️ Descargar traducción para LIVE y PTU](https://github.com/Doncasta1996/Star-Citizen-Spanish/archive/refs/heads/main.zip)

El mismo paquete sirve para LIVE y PTU. Instálalo en la carpeta del canal donde juegues.
<!-- sc-versions:end -->

---

## ⚡ Instalación rápida

1. **Cierra Star Citizen.**
2. Descarga el ZIP y descomprímelo.
3. Abre la carpeta descomprimida y copia la carpeta **`data`** dentro de tu instalación:
   - **LIVE:** `StarCitizen\LIVE`
   - **PTU:** `StarCitizen\PTU`
4. Abre el archivo **`user.cfg`** de esa misma carpeta y añade esta línea:
```ini
g_language = spanish_(spain)
```

Si todavía no tienes `user.cfg`, créalo con ese nombre y contenido. Comprueba que Windows no lo guarde como `user.cfg.txt`.

### 📂 Ubicación del archivo de traducción

Para **LIVE**:
```scss
StarCitizen\LIVE\data\Localization\spanish_(spain)\global.ini
```

Para **PTU**:
```scss
StarCitizen\PTU\data\Localization\spanish_(spain)\global.ini
```

5. Inicia el juego.

---

## 🔄 Actualizar la traducción

1. Cierra el juego.
2. Descarga el paquete actualizado.
3. Copia la carpeta `data` en el canal correspondiente y acepta sustituir `global.ini`.

Si ya tienes configurado el idioma, puedes mantener tu `user.cfg`.

Si juegas tanto en LIVE como en PTU, actualiza el archivo en las dos carpetas.

---

## 🛠️ Si la traducción no aparece

Comprueba lo siguiente:

- Has instalado los archivos en el canal que estás ejecutando.
- `global.ini` está en la ruta indicada arriba.
- `user.cfg` está directamente dentro de `LIVE` o `PTU`.
- El nombre del archivo es `user.cfg`, sin la extensión adicional `.txt`.
- La línea del idioma coincide exactamente con:
```ini
g_language = spanish_(spain)
```

Reinicia el juego después de hacer los cambios.

---

## 🐛 Comunicar un error

Si encuentras una frase incorrecta, un texto cortado o una entrada en inglés, abre un aviso e incluye:

- **Canal y versión completa del juego.**
- **Texto que aparece y el problema observado.**
- **Dónde aparece**, por ejemplo, en un contrato, menú u objeto.
- **Una captura**, si es posible.

### [📝 Comunicar un error de traducción](https://github.com/Doncasta1996/Star-Citizen-Spanish/issues)

---

## 🤝 Créditos y colaboraciones

Traducción original de **Jose_Pacheco**.

Colaboraciones de **Autovot, JimmyVaras, Keiran, 𐒝órnacκ®, Sπeler y ZettaZ**.

[Proyecto colaborador SC_Spanish_SOK](https://github.com/Autovot/SC_Spanish_SOK)

Gracias a quienes comunican errores y ayudan a mejorar la traducción.
