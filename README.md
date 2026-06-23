<!-- ═══════════════════════════════════════════════════════
     MUHAMMAD ANAS NADEEM · PROFILE README
     Commit both README.md and assets/race-strip.svg
     Place race-strip.svg at: assets/race-strip.svg
     ═══════════════════════════════════════════════════════ -->

<!-- ── HEADER ── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=200&color=0D0D0D&text=MUHAMMAD%20ANAS%20NADEEM&fontColor=FAFAF8&fontSize=36&fontAlignY=42&fontFamily=JetBrains%20Mono&desc=Computer%20Science%20%C2%B7%20AI%20Systems%20%C2%B7%20Physical%20AI%20%C2%B7%20Brunel%20University%20London&descAlignY=65&descSize=13&descColor=888884"/>

<!-- ── ANIMATED RACE STRIP ──
     This SVG file must be committed to your repo at: assets/race-strip.svg
     The car drives left-to-right with sector flash markers -->
<img width="100%" src="./assets/race-strip.svg" alt="race strip"/>

<br/>

<!-- ── TIMING BOARD ── -->
<table width="100%">
<tr>
<td align="center" width="33%" style="background-color:#0D0D0D;padding:16px 0;border:1px solid #1E1E1E;">
<sub><kbd>STATUS</kbd></sub><br/>
<b><span style="color:#E8002D;">SEEKING&nbsp;PLACEMENT</span></b>
</td>
<td align="center" width="34%" style="background-color:#0D0D0D;padding:16px 0;border:1px solid #1E1E1E;">
<sub><kbd>CURRENT BUILD</kbd></sub><br/>
<b style="color:#FAFAF8;">ARIS &middot; F1 STRATEGY AI</b>
</td>
<td align="center" width="33%" style="background-color:#0D0D0D;padding:16px 0;border:1px solid #1E1E1E;">
<sub><kbd>LOCATION</kbd></sub><br/>
<b style="color:#FAFAF8;">LONDON,&nbsp;UK</b>
</td>
</tr>
</table>

<br/>

---

## `// 01` &nbsp; COMPETITION RECORD

<table width="100%">
<tr style="background-color:#0D0D0D;">
<td width="48" align="center"><b style="color:#E8002D;font-size:22px;">P1</b></td>
<td>
<b>Oxford Physical AI Hackathon</b><br/>
<sub>Oxford AI Society &middot; Track 2 &middot; SO-101 + Amazing Hands &middot; Neuracore Stack</sub><br/><br/>
Only team to assemble the Amazing Hand hardware end-to-end. Shipped three live demos in 24 hours — real-time hand mirroring via imitation learning, sign language recognition, and a Meta Quest VR control interface.
</td>
<td width="80" align="center"><kbd>WINNER</kbd></td>
</tr>
</table>

<br/>

---

## `// 02` &nbsp; CURRENT BUILD &middot; ARIS

> Adaptive Race Intelligence System — a physics-grounded, ML-augmented F1 strategy engine that evaluates pit decisions per tick using Monte Carlo confidence intervals and narrates the optimal call with a quantified lap-time delta.

```
PIPELINE ──────────────────────────────────────────────────────────────────
  FastF1 Ingest → PostgreSQL → Bicycle Model + Tyre Degradation + Fuel Burn
                                          ↓
                               XGBoost ML Residual
                                 (race-by-race CV)
                                          ↓
                       Monte Carlo Action-Search Engine
                              ↙                    ↘
             Strategy Output                   LLM Narration
         delta · CI · pit window            radio-call format
                              ↘                    ↙
                           Streamlit Dashboard
────────────────────────────────────────────────────────────────────────────
```

| Phase | Scope | Status |
|---|---|:---:|
| 1 &middot; Foundations | FastF1 pipeline &middot; PostgreSQL &middot; Streamlit | ✅ |
| 2 &middot; Predictor | Bicycle model &middot; Tyre degradation &middot; XGBoost residual | 🔄 |
| 3 &middot; Counterfactuals | Perturbation engine &middot; Tiered tick architecture | ⏳ |
| 4 &middot; Narration | Local LLM &middot; Conformal calibration &middot; Strategy backtest | ⏳ |

&rarr;&nbsp; [Execution Plan](https://github.com/AnassNadeem/ARIS/blob/main/ARIS-EXECUTION-PLAN.md) &nbsp;&middot;&nbsp; [Build Log](https://github.com/AnassNadeem/ARIS/blob/main/BUILD-LOG.md) &nbsp;&middot;&nbsp; [Repository](https://github.com/AnassNadeem/ARIS)

---

## `// 03` &nbsp; TECH STACK

**Languages**

![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=E8002D)
![Java](https://img.shields.io/badge/Java-0D0D0D?style=flat-square&logo=openjdk&logoColor=E8002D)
![C](https://img.shields.io/badge/C-0D0D0D?style=flat-square&logo=c&logoColor=E8002D)
![SQL](https://img.shields.io/badge/SQL-0D0D0D?style=flat-square&logo=postgresql&logoColor=E8002D)
![JavaScript](https://img.shields.io/badge/JavaScript-0D0D0D?style=flat-square&logo=javascript&logoColor=E8002D)

**AI &middot; ML &middot; Simulation**

![PyTorch](https://img.shields.io/badge/PyTorch-0D0D0D?style=flat-square&logo=pytorch&logoColor=FAFAF8)
![scikit&#8209;learn](https://img.shields.io/badge/scikit--learn-0D0D0D?style=flat-square&logo=scikit-learn&logoColor=FAFAF8)
![XGBoost](https://img.shields.io/badge/XGBoost-0D0D0D?style=flat-square&logo=xgboost&logoColor=FAFAF8)
![NumPy](https://img.shields.io/badge/NumPy-0D0D0D?style=flat-square&logo=numpy&logoColor=FAFAF8)
![Pandas](https://img.shields.io/badge/Pandas-0D0D0D?style=flat-square&logo=pandas&logoColor=FAFAF8)
![FastF1](https://img.shields.io/badge/FastF1-0D0D0D?style=flat-square&logo=formula1&logoColor=FAFAF8)

**Infrastructure &middot; DevOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D0D0D?style=flat-square&logo=postgresql&logoColor=888884)
![Docker](https://img.shields.io/badge/Docker-0D0D0D?style=flat-square&logo=docker&logoColor=888884)
![Streamlit](https://img.shields.io/badge/Streamlit-0D0D0D?style=flat-square&logo=streamlit&logoColor=888884)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D0D0D?style=flat-square&logo=github-actions&logoColor=888884)
![Linux](https://img.shields.io/badge/Linux-0D0D0D?style=flat-square&logo=linux&logoColor=888884)
![Git](https://img.shields.io/badge/Git-0D0D0D?style=flat-square&logo=git&logoColor=888884)

**Physical AI &middot; Hardware**

![ROS](https://img.shields.io/badge/ROS-0D0D0D?style=flat-square&logo=ros&logoColor=FAFAF8)
![Arduino](https://img.shields.io/badge/Arduino-0D0D0D?style=flat-square&logo=arduino&logoColor=FAFAF8)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-0D0D0D?style=flat-square&logo=raspberry-pi&logoColor=FAFAF8)
![CUDA](https://img.shields.io/badge/CUDA-0D0D0D?style=flat-square&logo=nvidia&logoColor=FAFAF8)

---

## `// 04` &nbsp; EXPERIENCE

```
Jan 2026 – Mar 2026   Student Leader · Electech Lab
                      Taught robotics, logic gates, and coding to primary-school
                      students at St Andrews C of E using Tinkercad + Code Monkey.

Jul 2024 – Aug 2024   PHP Intern · Tally Marks Consulting
                      Optimised database operations and wrote complex SQL queries
                      for enterprise data management systems.
```

---

## `// 05` &nbsp; STATUS

```python
status = {
    "degree"    : "BSc Computer Science · Brunel University London",
    "building"  : "ARIS — F1 race strategy AI  (physics + ML + LLM narration)",
    "studying"  : ["ML theory", "vehicle dynamics", "conformal prediction"],
    "exploring" : ["VLA models", "imitation learning", "physical AI systems"],
    "open_to"   : ["placements", "internships", "AI/ML · robotics · software engineering"]
}
```

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D0D0D?style=for-the-badge&logo=linkedin&logoColor=E8002D)](https://linkedin.com/in/MuhammadAnasNadeem)
&nbsp;
[![Email](https://img.shields.io/badge/Email-0D0D0D?style=for-the-badge&logo=gmail&logoColor=E8002D)](mailto:anass.nadeem42@gmail.com)
&nbsp;
[![ARIS](https://img.shields.io/badge/ARIS-0D0D0D?style=for-the-badge&logo=github&logoColor=E8002D)](https://github.com/AnassNadeem/ARIS)
&nbsp;
[![Profile Views](https://komarev.com/ghpvc/?username=AnassNadeem&style=for-the-badge&color=0D0D0D&label=VIEWS)](https://github.com/AnassNadeem)

</div>

<!-- ── RED CLOSING STRIPE ── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=4&color=E8002D"/>
