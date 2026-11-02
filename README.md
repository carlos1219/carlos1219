<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=1000&color=2EA043&center=true&vCenter=true&width=700&lines=Hola%2C+soy+Carlos+Le%C3%B3n+Arjona;AppSec+%7C+DevSecOps;Shift-left+security+%26+supply+chain;M%C3%A1ster+en+Ciberseguridad" alt="Typing SVG" />

</div>

## 🔐 Sobre mí

Analista de seguridad de aplicaciones (AppSec) y desarrollador full stack en **Global Exchange**. Me muevo entre el código y la seguridad: diseño sistemas en los que la seguridad es una restricción de partida y no una revisión al final, con modelo de amenazas primero, mínimo privilegio, cadena de suministro verificable y pruebas contra sistemas reales.

- 🎓 Máster en Ciberseguridad
- 🛡️ Foco: AppSec, DevSecOps, seguridad en pipelines y contenedores

## 🚀 Proyecto destacado: [NAVE](https://github.com/carlos1219/nave)

Plataforma SAST/SCA para GitHub. Analiza cada push y pull request con **Semgrep** y **Trivy**, aplica una política de calidad y bloquea la PR con un check y un comentario cuando entra un fallo grave.

![NAVE bloqueando una pull request con hallazgos CRITICAL y HIGH](nave-pr-bloqueada.gif)

- **El escáner como superficie de ataque.** El código analizado no es de fiar: cada escaneo corre en contenedores efímeros sin red, con **gVisor** y Docker rootless, y solo un servicio aislado puede crearlos, mediante peticiones firmadas con HMAC.
- **Seguridad documentada y comprobada.** Modelo de amenazas STRIDE, 34 decisiones de arquitectura (ADR) y una revisión como atacante con 36 hallazgos, cada corrección con su test de regresión.
- **Cadena de suministro.** Imágenes fijadas por digest, dependencias con hash, acciones fijadas por SHA, SBOM CycloneDX, firma con cosign y OpenSSF Scorecard.
- **Calidad.** Unos 2.900 tests, arquitectura hexagonal verificada en CI y una CI que se escanea a sí misma.

## 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

Seguridad: Semgrep · Trivy · gVisor · Sigstore/cosign · OpenSSF Scorecard · CodeQL · Dependabot

## 🫀 Otro proyecto: BlutTruck

Sistema de monitorización cardíaca con IA (TFG): pulsera inteligente → app móvil (Dart) → backend **C# / .NET** → servidor de predicción en **Python** (SVM) → panel web en **Vue.js**, todo orquestado con **Docker**.

[`BlutTruckAPI`](https://github.com/carlos1219/BlutTruckAPI) · [`BlutTruck_Conjunto2`](https://github.com/carlos1219/BlutTruck_Conjunto2)

## 🤖 Cómo trabajo

Uso asistentes de IA (Claude Code) bajo un contrato de ingeniería escrito con reglas de seguridad no negociables. La arquitectura, las restricciones y los riesgos aceptados los decido yo, y nada se da por bueno sin tests, CI y pruebas contra el sistema real, incluido el código que propone el asistente.
