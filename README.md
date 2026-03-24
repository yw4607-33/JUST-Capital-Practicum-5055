JUST Capital Practicum: Synthetic Persona Generation with AI

Project Overview

This project investigates whether Large Language Models can generate synthetic survey respondents that accurately replicate real-world survey distributions. We focus on corporate social responsibility attitudes using JUST Capital's 2025 survey data.

🎯 Project Phases
Phase 1: Literature Review ✅

Reviewed research on LLM-generated personas, synthetic sampling, and bias
Key papers: Morris et al. (Verasight Reports), Shin et al. (DIS 2024), Atari et al. (2025)

Phase 2: Persona Design Specifications ✅

Demographics: Age, Gender, Race, Metro Status, Industry, Political Party, Education, Income, Region, Employment
Attitudes (Factor Analysis):

Performance: How well are companies performing on social/economic responsibilities?
Belief: To what extent should businesses play an active role in societal issues?
Importance: How important are corporate social responsibilities?


Joint Distributions: Selected Top 15 joint distributions based on association strength (correlation scores)

Phase 3: Persona Generation 🔄 In Progress

Generate synthetic personas using Claude API
Validate against Just Capital's marginal distributions
Ensure logical consistency and sociological plausibility

Phase 4: Survey Response Generation 📅 Upcoming

Feed personas into the response generation model
Generate synthetic survey responses
Validate against real survey data

Phase 5: Analysis & Validation 📅 Upcoming

Assess replicability
Test for homogeneity bias
Compare Claude vs. ChatGPT (parallel team)
