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
Welcome. Today we are presenting the analysis of Machine 1, focusing on how pressure and temperature variables impact the final part resistance.
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
We utilized a Two-Way ANOVA method to isolate the effects of two primary factors.
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

**All factors exceed the threshold.**
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_resistance.html' width='100%' height='450px' style='border:none;'></iframe>
:::
::::::::::::::

---

# Discussion of Effects

:::::::::::::: {.columns}
::: {.column width="50%"}
### Key Insights
- **Main Effects:** Both $P$ and $T$ are primary drivers of Part Resistance variation.
- **Interaction Complexity:** The significant $P\times T$ interaction implies synergistic effects.
- **Optimization:** Process control must account for both variables.
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/workflow.png)
:::
::::::::::::::

---

# Conclusion

:::::::::::::: {.columns}
::: {.column width="50%"}
### Final Verdict
- ✅ **Pressure** significant.
- ✅ **Temperature** significant.
- ✅ **Interaction Effect** validated.

**Recommendation:** 
Implement a coupled control loop for Pressure and Temperature for Machine 1.
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/checked.png)
:::
::::::::::::::