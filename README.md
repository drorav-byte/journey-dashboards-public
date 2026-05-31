# Journey Dashboards (Public)

Hosts interactive SFMC marketing-automation journey visualisations for embedding in the Base44 Lifecycle Journeys app.

## Live dashboards

### Lifecycle Journeys
| Journey | URL |
|---|---|
| Leads Onboarding - Experienced (v28) | https://drorav-byte.github.io/journey-dashboards-public/ |
| New Funded 2.0 (v5) | https://drorav-byte.github.io/journey-dashboards-public/new-funded-2.0.html |
| 0086_OnboardingWelcome_Journey (v2) | https://drorav-byte.github.io/journey-dashboards-public/onboarding-welcome.html |

### KPI Flows
| Journey | URL |
|---|---|
| Demo to FTD A/B (v4) | https://drorav-byte.github.io/journey-dashboards-public/demo-to-ftd.html |
| Deposit without Position (v2) | https://drorav-byte.github.io/journey-dashboards-public/deposit-without-position.html |

To publish a new dashboard:
1. Run `python apps/journey-mapper/build_<journey>_dashboard.py` locally
2. Copy the resulting HTML here with a slug filename
3. `git push` — live in ~30s
