BOARDCHECK AI SCANNER — ANDROID PROTOTYPE

WHAT WORKS
- Mobile-first interface with live rear-camera preview and capture (browser permissions/security permitting).
- Photo upload fallback.
- Multiple phone brands and common fault categories.
- Generic rule-based next-check suggestions.
- Optional manual measurement fields and JSON/CSV case export.

WHAT NEEDS TRAINING / INTEGRATION
- Automatic component/IC identification and location marking.
- Visual damage/defect detection.
- Image-based fault diagnosis.
No trained vision model or cloud AI service is included. The app does not claim to detect a fault from the image.

ANDROID SETUP
1. Extract this ZIP using Files / My Files.
2. Open index.html in Chrome.
3. Camera access may be blocked when opening a local file. If so, choose Use photo instead, or host the folder using an HTTPS static site.
4. Tap Open camera, allow access, centre the board, tap Capture.
5. Choose brand/fault, enter only measurements actually taken, then tap Analyze scan.
6. Export JSON or CSV. Images are not embedded in exports; keep image files with their case IDs.

SAFETY AND DATA
- Treat suggestions as generic triage, not a confirmed diagnosis.
- Use model-specific schematics and verified electrical measurements.
- Disconnect power before resistance/diode tests.
- Collect clear, permissioned board photos labelled with brand/model, board region, known component labels, confirmed fault, measurements, and repair outcome to train/evaluate a future model.
