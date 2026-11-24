# Bara Mitra prototype

A responsive, Kannada-first front-end prototype for the Bara Mitra drought relief and claim copilot concept.

## Open the prototype

Open `index.html` in a modern browser. It is a static site and does not need a build step or account.

## What you can try

- Switch between Kannada and English.
- Describe a field issue by typing or, where the browser supports it, using speech recognition.
- Choose a crop, add village or taluk details, and attach a field photo for a local preview.
- Review sample field notes, support options to ask about, a document checklist, and water-wise crop ideas.
- Save a plain-text field guide to the device.

## Prototype boundaries

The analysis and support content is sample guidance. This prototype does not diagnose crop damage, verify current scheme availability or eligibility, capture GPS, submit a claim, or upload report data. Confirm decisions and current requirements with the local agriculture office.

The voice input feature uses the browser's built-in speech recognition when available; browser support and Kannada recognition vary. The microphone is only requested after the user presses **Speak instead**.

The hero landscape photo is by [Abdul Muiz Khan on Unsplash](https://unsplash.com/photos/a-green-field-with-trees-and-a-blue-sky-X9Ql-wHV3TQ), used under the [Unsplash License](https://unsplash.com/license).

The photo-guidance panel is a front-end demonstration with sample steps; it is not connected to an AI model and does not upload the selected photo. Nearby farmer-group and fertilizer-shop links open Google Maps searches using the area entered by the user. Google receives that area only when the user opens a map link.
