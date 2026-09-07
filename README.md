# Task 3 · Temperature Converter Website

**Track:** Web Development & Designing — Level 1
**Objective:** Build an interactive web tool that converts temperature values between Celsius, Fahrenheit, and Kelvin, with real-time input validation.

## About this project

A single-page temperature converter. Enter a value, choose the unit you're converting *from*, and it instantly shows the equivalent value in all three units (Celsius, Fahrenheit, Kelvin). Invalid input and physically impossible values (below absolute zero) are both caught and explained.

## Tech stack

- HTML5
- CSS3
- JavaScript (Vanilla — no libraries, no `eval()`)

## Feature checklist

- [x] Numeric input field with validation — non-numeric or empty input shows an inline error
- [x] Dropdown to select the input unit (Celsius / Fahrenheit / Kelvin)
- [x] Auto-conversion showing all three output units simultaneously
- [x] Convert button triggers the calculation (also works via Enter key)
- [x] Result display area with correct unit labels (°C, °F, K)
- [x] Edge case handling: any value that converts to below −273.15 °C shows a friendly "below absolute zero" warning instead of a result
- [x] Clean, centred, card-based UI with clear labels

## Conversion formulas used

- Celsius → Fahrenheit: `F = C × 9/5 + 32`
- Fahrenheit → Celsius: `C = (F − 32) × 5/9`
- Celsius ↔ Kelvin: `K = C + 273.15`

## Files

| File | Description |
|---|---|
| `index.html` | Full converter tool (HTML + CSS + JS) |
| `screenshot-desktop.png` | Desktop view |
| `screenshot-mobile.png` | Mobile view |

## How to view

Open `index.html` directly in any browser — no build step, no server, no dependencies.
