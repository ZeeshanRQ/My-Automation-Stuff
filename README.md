# My Automation Stuff

A collection of my QA automation practice and work-sample projects – Cypress web E2E suites and WebdriverIO/Appium mobile tests – plus a few early React website projects.

## What's inside

| Folder | What it is | Tools |
| --- | --- | --- |
| `Automation Practice/cypress` | Early Cypress practice – login and add-clinic specs, custom commands | Cypress |
| `ECX/cypress` | EyeCare X web portal E2E tests – Super Admin, Clinic Admin and Doctor Portal flows (users, clinics, doctors, staff, patients, appointments) | Cypress, Faker |
| `ECX MB/cypress` | Copy of the EyeCare X Cypress suite used for mobile-browser runs | Cypress |
| `ECX Mobile/test/specs` | EyeCare X Android app tests – auth with email OTP, home, clinics, profile, pre-exam chat, vision tests | WebdriverIO, Appium |
| `Smart Printer Images/Images` | Logo, banners and client logos for the Smart Printers website | – |
| `smart-printers/src` | Smart Printers business website (source) | React, Vite, SCSS |
| `Final Digital Marketing Project/src` | Single-page digital marketing website (source) | React, Tailwind CSS |
| `print-marketing-site/src` | Print & promotional products storefront landing page (source) | React, SCSS |

## Projects that now have their own repositories

The web projects and the EyeCare X suite have been moved into standalone, runnable repositories (with build setup and documentation):

- **Smart Printers website** → [smart-printers-website](https://github.com/ZeeshanRQ/smart-printers-website)
- **Print marketing site** → [print-marketing-site](https://github.com/ZeeshanRQ/print-marketing-site)
- **EyeCare X test automation (Cypress + WebdriverIO)** → [eyecarex-test-automation](https://github.com/ZeeshanRQ/eyecarex-test-automation)
- **EyeCare X mobile app tests** → [eyecare-x-mobile](https://github.com/ZeeshanRQ/eyecare-x-mobile)

Please refer to those repositories for the latest code; the copies here are kept for history.

## Running the Cypress folders

Each `cypress/` folder expects a standard Cypress project around it:

```bash
npm init -y
npm install --save-dev cypress @faker-js/faker cypress-file-upload
npx cypress open
```

Credentials are read through `Cypress.env()` – provide them in a local `cypress.env.json` (not committed).
