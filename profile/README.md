<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/urbiva-banner-light.png">
  <img alt="Urbiva. Intelligence for cities that work for everyone. Midnight Violet banner with the Urbiva logo, a city grid and an accessible route line in Volt Lime." src="assets/urbiva-banner.png" width="100%">
</picture>

<h3 align="center">Intelligence for cities that work for everyone.</h3>
<p align="center">AI-powered urban accessibility and infrastructure intelligence.<br><b>Every city. Every possibility.</b></p>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/divider-light.png">
  <img alt="" src="assets/divider.png" width="100%">
</picture>

## Why Urbiva

The shortest route is not always a passable one. Stairs, high curbs, broken surfaces and blocked paths turn a short walk into a long or impossible one for wheelchair users, parents with strollers and older people. Cities rarely know where these barriers are, and planners rarely see which repair would help the most people.

Urbiva connects three things: what people observe on the street, a verified accessibility graph, and a simple way to measure the effect of removing a barrier.

## Four modules

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: light)" srcset="assets/module-go-light.png">
        <img alt="Urbiva Go: accessible route navigation for residents" src="assets/module-go.png" width="100%">
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: light)" srcset="assets/module-vision-light.png">
        <img alt="Urbiva Vision: AI-assisted barrier reporting with human confirmation" src="assets/module-vision.png" width="100%">
      </picture>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: light)" srcset="assets/module-urban-light.png">
        <img alt="Urbiva Urban: infrastructure intelligence dashboard for planners" src="assets/module-urban.png" width="100%">
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: light)" srcset="assets/module-impact-light.png">
        <img alt="Urbiva Impact: simulation of what removing a barrier changes" src="assets/module-impact.png" width="100%">
      </picture>
    </td>
  </tr>
</table>

| Module | For | What it does |
| --- | --- | --- |
| **Urbiva Go** | Residents | Compares a suitable route with the shortest route for a mobility profile and says honestly what is not verified |
| **Urbiva Vision** | Residents | Turns a photo into a barrier report; AI gives an estimate, a person confirms it |
| **Urbiva Urban** | Planners | Shows segment states, barrier records and a review queue |
| **Urbiva Impact** | Planners | Recalculates 15-minute reachability on a copy of the graph after removing a barrier |

## How it fits together

<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/urbiva-architecture-light.png">
  <img alt="Architecture: urban observation flows into Urbiva Vision, then verified barrier data, then the accessibility graph, which powers Urbiva Go and Urbiva Urban and feeds Urbiva Impact. A lightweight local vision model, UVA-Net S10, is marked as planned research." src="assets/urbiva-architecture.png" width="100%">
</picture>

## Where we are

| Area | Status |
| --- | --- |
| Hackathon MVP with all four modules and a guided demo | Implemented |
| Demo network "Pilot zona A" | Sample data, not a real city |
| Design system v1.0 | Design freeze |
| UVA-Net S10, a lightweight local vision model | Planned research, no model or results yet |
| Public deployment and real pilot data | Planned |

## Principles

- **Human confirmation.** AI output is an estimate until a person confirms it.
- **Honest data.** Unknown and unverified segments are shown as such, never hidden.
- **Privacy by default.** Photos are stripped of metadata and are not stored.
- **Measured impact.** Every number comes from the graph, with its assumptions shown.

<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/divider-light.png">
  <img alt="" src="assets/divider.png" width="100%">
</picture>

<p align="center"><sub>Urbiva. Building accessible, human-centered cities with artificial intelligence.</sub></p>
