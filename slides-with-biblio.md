# Effects of Pressure and Temperature on Part Resistance for Machine 1

:::::::::::::: {.columns}
::: {.column width="50%"}
## Study Overview
**Objective:** To assess the statistical significance of environmental and mechanical parameters on product quality.

- **Focus:** Machine 1 Performance
- **Target:** Part Resistance $\Omega$
- **Goal:** Optimization and variance reduction
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/engineering.png)

::: notes
Welcome. Today we present the analysis of Machine 1, focusing on how pressure and temperature variables impact the final part resistance. Our objective is to identify key drivers of resistance to ensure product consistency.
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
We utilized a Two-Way ANOVA method to isolate the effects of two primary factors. Resistance is our critical quality metric, tested at a 95% confidence interval.
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

**All factors exceed the 95% threshold.**
:::

::: {.column width="50%"}
<iframe data-src='media/plots/m1_resistance.html' width='100%' height='450px' style='border:none;'></iframe>
:::

::: notes
The data shows that both Pressure and Temperature have highly significant independent effects. Crucially, the interaction between them is also significant at 0.0183, suggesting the effect of pressure depends on the current temperature.
:::
::::::::::::::

---

# Discussion of Effects

:::::::::::::: {.columns}
::: {.column width="50%"}
### Key Insights
- **Main Effects:** Both $P$ and $T$ are primary drivers of variation.
- **Interaction Complexity:** The significant $P\times T$ interaction implies synergistic effects between load and heat.
- **Optimization:** Process control must account for both variables simultaneously to maintain resistance quality.
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
- ✅ **Pressure** significant effect.
- ✅ **Temperature** significant effect.
- ✅ **Interaction Effect** validated.

**Recommendation:** 
Implement a coupled control loop for Pressure and Temperature for Machine 1 to minimize Part Resistance.
:::

::: {.column width="50%"}
![](https://img.icons8.com/fluency/200/checked.png)

::: notes
In conclusion, we have statistically validated that Pressure, Temperature, and their interaction are critical to Machine 1's output. Future process improvements should prioritize the stabilization of these two factors in tandem.
:::
::::::::::::::
---
# Bibliography
<div id="refs"></div>
