# Animated Exoplanet Discovery Plot

![Example animation](mass_vs_period_by_year.gif)

This repository generates an animated **mass vs orbital period diagram** of confirmed exoplanets using the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars/).

The animation progresses through **discovery year**, gradually adding planets as they were discovered, illustrating the rapid growth of the exoplanet population and how different detection techniques populate different regions of parameter space.

The output is an animated GIF suitable for presentations, talks, and outreach.

---

## Data Source

The data comes from the **NASA Exoplanet Archive** `PSCompPars` table.

https://exoplanetarchive.ipac.caltech.edu/

---

## Configuration Options

The script allows several user-controlled parameters.

### Axis Units

| Parameter | Options | Description |
|------|------|------|
| `X_SCALE` | `"days"` / `"years"` | Orbital period units |
| `Y_SCALE` | `"Mearth"` / `"Mjup"` | Planet mass units |

---

### Plot Style

| Parameter | Options | Description |
|------|------|------|
| `THEME` | `"light"` / `"dark"` | Plot colour scheme |
| `TRANSPARENT_BG` | `True` / `False` | Transparent background for slides |
| `GRIDLINES` | `True` / `False` | Toggle gridlines |
| `LOG_SCALE` | `True` / `False` | Logarithmic axes |

---

### Animation Settings

| Parameter | Description |
|------|------|
| `FPS` | Frames per second in the GIF |
| `POINT_SIZE` | Size of plotted planets |
| `ALPHA` | Marker transparency |

---

## Output

The script produces an animated GIF:
