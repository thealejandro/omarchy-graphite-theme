<a href="https://thealejandro.dev"><picture><source media="(prefers-color-scheme: dark)" srcset="docs/marca/logotipo.svg"><img alt="thealejandro" src="docs/marca/logotipo-mono-oscuro.svg" height="32"></picture></a>

# Graphite

[English](README.md)

Un tema para [Omarchy](https://omarchy.org). Inspirado en macOS Graphite, oscuro.

Monocromo. Solo grises, sin acento de color: un escritorio tranquilo y sin distracciones.

![Graphite](preview.png)

## Instalar

```bash
omarchy theme install https://github.com/thealejandro/omarchy-graphite-theme
```

### Esquinas redondeadas y colores del prompt (recomendado)

Omarchy ignora los archivos `.lua` de los temas instalados desde un repo, así que
este tema guarda el radio de las esquinas en `shape.toml`. Un pequeño hook de
[omarchy-themes](https://github.com/thealejandro/omarchy-themes) lo aplica, y otro recolorea el prompt
[Tide](https://github.com/IlanCosman/tide) (fish) a juego:

```bash
git clone https://github.com/thealejandro/omarchy-themes
omarchy-themes/install.sh
```

Sin los hooks el tema funciona igual; las ventanas solo conservan tus esquinas de siempre.

## Qué incluye

| Archivo | Para qué sirve |
| --- | --- |
| `colors.toml` | La paleta. Omarchy genera con ella la terminal, btop, Neovim, VS Code, la barra y lo demás. Acento `#a1a1a6`, modo oscuro. |
| `icons.theme` | Iconos: `Yaru-sage-dark`. |
| `shape.toml` | Esquinas: 12 px, curvatura 4. |
| `hyprland.lua` | El mismo borde y esquinas, por si copias la carpeta a mano. |
| `backgrounds/` | Tres fondos de pantalla, hechos para este tema. |

Actualiza con `omarchy theme update`; quítalo con `omarchy theme remove graphite`.

Más temas: [thealejandro.dev/omarchy](https://thealejandro.dev/omarchy)

Hecho por [thealejandro](https://thealejandro.dev)

Sin relación con Apple ni Microsoft. [MIT](LICENSE)
