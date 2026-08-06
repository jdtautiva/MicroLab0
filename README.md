# MicroLab0 — Interactive Microeconomics Foundations Lab

> **Collection of 11 browser-based decision activities for introductory microeconomics and managerial economics courses.**
> Developed by **Julián Díaz Tautiva, PhD**

---

## Overview

MicroLab0 is a collection of browser-based pedagogical activities designed to introduce fundamental microeconomic concepts through short, interactive decision challenges. Rather than presenting economic theory only through definitions and formulas, the activities place students in the roles of consumers, producers, operations managers, market organizers, policy analysts, government ministers, and firm managers.

The collection consists of eleven standalone modules that can be used independently or as a progressive learning sequence:

1. Economic decisions, scarcity, restrictions, and opportunity cost
2. Optimization, equilibrium, and empirical analysis
3. Absolute and comparative advantage
4. Individual willingness to pay and market demand
5. Firm supply and industry supply
6. Price elasticity of supply in the short and long run
7. Competitive equilibrium, shortages, and surpluses
8. Price controls, rationing, and unintended consequences
9. Tax and subsidy incidence
10. International trade, tariffs, and distributional effects
11. Market structures, pricing power, and demand elasticity

Each activity is delivered as an individual HTML file—`act1.html` through `act11.html`. The modules require no installation or backend and can be opened locally or served through a learning-management system, institutional website, or standard web server.

---

## Learning Objectives

By completing the MicroLab0 activities, students are able to:

* Explain economics as the study of choices made under constraints, including decisions that do not directly involve money
* Distinguish optimization, equilibrium, and empiricism as complementary principles of economic reasoning
* Calculate opportunity costs and use comparative advantage to determine efficient specialization
* Construct market demand by aggregating individual willingness-to-pay decisions at a common price
* Differentiate individual firm supply from industry supply and aggregate comparable producers horizontally
* Distinguish movements along supply curves from shifts caused by input costs, technology, expectations, or changes in the number of firms
* Analyze how production restrictions and adjustment time affect the price elasticity of supply
* Identify competitive equilibrium and explain how prices coordinate buyers and sellers through shortages and surpluses
* Evaluate the intended and unintended consequences of price ceilings, rationing systems, and complementary policy measures
* Distinguish legal tax incidence from economic incidence and relate the distribution of a tax or subsidy to relative elasticities
* Evaluate the concentrated benefits and dispersed costs of tariffs, including the social cost per job protected
* Compare perfect competition, monopolistic competition, oligopoly, and monopoly using substitutes, differentiation, entry barriers, strategic interaction, and market power

---

## Key Features

**Eleven modular activities** — instructors may assign the complete sequence or select individual modules according to the topic being covered. Each activity contains its own scenario, instructions, conceptual synthesis, and completion stage.

**Role-based economic decisions** — students act as consumers, producers, market coordinators, operations managers, tax analysts, policy advisers, trade ministers, and managers of firms operating under different market structures.

**Progressive formative feedback** — incorrect decisions produce conceptual hints, comparison prompts, or additional opportunities rather than simply displaying the correct answer. Several activities track attempts or reveal information progressively.

**Interactive market construction** — students build demand and supply relationships from individual decisions, aggregate quantities at common prices, identify equilibrium, and observe how prices affect buyers and sellers.

**Exploratory controls** — sliders, numeric inputs, classification cards, policy alternatives, production actions, market-selection panels, and scenario comparisons allow students to test how changing assumptions affects outcomes.

**Scenario and market variation** — activities include generated consumer valuations, alternative market conditions, multiple industries, short- and long-run horizons, and different combinations of demand and supply elasticities.

**Native economic visualizations** — demand curves, supply curves, equilibrium diagrams, tax wedges, tariff effects, allocation outcomes, and market-power indicators are generated directly through SVG or HTML Canvas.

**Prediction before revelation** — several modules ask students to forecast an outcome before displaying the simulated result, enabling comparison between prior intuition and economic analysis.

**Policy trade-off analysis** — the public-policy activities examine outcomes across multiple dimensions, including price accessibility, product availability, waiting time, informal markets, production incentives, tax burdens, government revenue, employment, and stakeholder welfare.

**Challenges and achievement badges** — optional challenges include finding equilibrium within a limited number of attempts, reaching an industry supply target, creating a 50/50 tax-incidence allocation, satisfying policy constraints, and correctly classifying market structures.

**Reflection and classroom discussion** — activities conclude with conceptual summaries, open-ended questions, and prompts intended to initiate plenary discussion rather than replace instructor-led interpretation.

**Accessible and responsive interface** — the modules include visible keyboard-focus states, ARIA labels and live regions, responsive layouts, and reduced-motion accommodations in several activities.

---

## Technical Details

| Attribute                     | Detail                                                                                                                            |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Format                        | 11 standalone `.html` files: `act1.html`–`act11.html`                                                                             |
| Architecture                  | HTML5, embedded CSS, and vanilla JavaScript                                                                                       |
| External JavaScript libraries | None                                                                                                                              |
| Visualization                 | Native SVG; HTML Canvas in the tariff activity                                                                                    |
| Backend required              | None                                                                                                                              |
| Installation required         | None                                                                                                                              |
| Data persistence              | None; activity state is maintained only during the current browser session                                                        |
| Internet requirement          | Core activity logic can operate locally; the institutional logo is loaded from an external URL and includes a text-based fallback |
| Browser support               | Any modern browser, including Chrome, Firefox, Safari, and Edge                                                                   |
| Screen                        | Responsive; desktop or tablet recommended for detailed graphs and comparison tables                                               |
| Language                      | Spanish (`es-CL`)                                                                                                                 |
| Accessibility                 | Keyboard-focus indicators, semantic labels, ARIA live feedback, and reduced-motion support                                        |
| Institutional context         | Universidad Andrés Bello, Facultad de Economía y Negocios                                                                         |

---

## Suggested Citation

Díaz Tautiva, J.A. (2026). *MicroLab0 — Interactive Microeconomics Foundations Lab*. Interactive teaching activity suite for introductory and managerial economics.
