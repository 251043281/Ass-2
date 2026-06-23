---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

# Machine 1: Resistance Analysis

:::::::::::::: {.columns}
::: {.column width="50%"}
### Impact of P & T
Analysis of Machine 1 shows how Pressure ($P$) and Temperature ($T$) influence product quality:

- **Pressure**: Evaluates if mechanical load affects resistance.
- **Temperature**: Evaluates thermal impacts on material properties.
- **Interaction**: Checks if the effect of Pressure changes at different Temperatures.

*Note: Lower resistance is preferred (USL = 10).*
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_resistance.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::::::::::::

---

# Machine 1: Resistance Analysis

:::::::::::::: {.columns}
::: {.column width="50%"}
### Impact of P & T
Analysis of Machine 1 shows how Pressure ($P$) and Temperature ($T$) influence product quality:

- **Pressure**: Evaluates if mechanical load affects resistance.
- **Temperature**: Evaluates thermal impacts on material properties.
- **Interaction**: Checks if the effect of Pressure changes at different Temperatures.

*Note: Lower resistance is preferred (USL = 10).*
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_resistance.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::::::::::::

---

# Effects of Pressure and Temperature on Part Resistance for Machine 1

:::::::::::::: {.columns}
::: {.column width="50%"}
## Study Overview
**Objective:** To assess the statistical significance of varying environmental and mechanical parameters on product quality.

- **Focus:** Machine 1 Performance
- **Target:** Part Resistance $\Omega$
- **Goal:** Optimization and variance reduction
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/engineering.png)

::: notes
Welcome. Today we are presenting the analysis of Machine 1, focusing on how pressure and temperature variables impact the final part resistance. Our primary objective is to identify key drivers of resistance to ensure product consistency.
:::
::::::::::::::

---

# Methodology & Parameters

:::::::::::::: {.columns}
::: {.column width="50%"}
### Analysis Framework
- **Response Variable:** Part Resistance
- **Design:** Two-Way ANOVA
- **Significance Level:** $\alpha = 0.05$

### Factors Tested
- **Pressure ($P$):** Mechanical load
- **Temperature ($T$):** Thermal environment
- **Interaction ($P\times T$):** Synergistic effects
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/test-tube.png)

::: notes
We utilized a Two-Way ANOVA method to isolate the effects of two primary factors. Resistance is our critical quality metric. We are testing at a 95% confidence interval to ensure statistical robustness.
:::
::::::::::::::

---

# Statistical Results

:::::::::::::: {.columns}
::: {.column width="50%"}
### ANOVA Summary Table

| Factor | p-value | Significance |
| :--- | :--- | :--- |
| Pressure ($P$) | 0.0000 | **Significant** |
| Temperature ($T$) | 0.0000 | **Significant** |
| Interaction ($P\times T$) | 0.0183 | **Significant** |

**All factors exceed the confidence threshold.**
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_resistance.html' width='100%' height='450px' style='border:none;'></iframe>
:::

::: notes
The data shows that both Pressure and Temperature have highly significant independent effects (p < 0.0001). Crucially, the interaction between them is also significant at 0.0183, suggesting the effect of pressure depends on the current temperature.
:::
::::::::::::::

---

# Discussion of Effects

:::::::::::::: {.columns}
::: {.column width="50%"}
### Key Insights
- **Main Effects:** Both $P$ and $T$ are primary drivers of Part Resistance variation.
- **Interaction Complexity:** The significant $P\times T$ interaction implies that adjusting pressure will yield different results depending on the thermal state of the machine.
- **Optimization:** Process control must account for both variables simultaneously.
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/workflow.png)

::: notes
It is not enough to look at pressure or temperature in isolation. Because the interaction is significant, the engineering team must develop a multi-variable control strategy to hit the target resistance values efficiently.
:::
::::::::::::::

---

# Conclusion

:::::::::::::: {.columns}
::: {.column width="50%"}
### Final Verdict
- ✅ **Pressure** significantly affects resistance.
- ✅ **Temperature** significantly affects resistance.
- ✅ **Interaction Effect** is present and validated.

**Recommendation:** 
Implement a coupled control loop for Pressure and Temperature for Machine 1 to maintain Resistance below the USL of 10.
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/checked.png)

::: notes
In conclusion, we have statistically validated that Pressure, Temperature, and their interaction are critical to Machine 1's output. Future process improvements should prioritize the stabilization of these two factors in tandem.
:::
::::::::::::::
