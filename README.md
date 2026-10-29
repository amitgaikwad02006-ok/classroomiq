# ClassroomIQ GitHub Pages Demo

This is a static, browser-based demonstration of ClassroomIQ. It does not need Python, pip, or Streamlit.

## Run locally
Double-click `index.html` to open it in your browser.

## Deploy to GitHub Pages
1. Create a GitHub repository, e.g. `classroomiq-demo`.
2. Upload `index.html` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL appears in the Pages settings.

## Limitations
- This is a static demo. Data and history stay in the current browser via localStorage.
- The dashboard starts with simulated values. They are not real campus measurements.
- GitHub Pages is public static hosting. A login implemented only in browser JavaScript would not provide real access control, so this demo deliberately does not pretend to offer secure teacher-only login.
- No live sensors, camera AI, server database, machine-learning forecast, or equipment control are connected.
- For private teacher access and real data, use a backend with proper authentication or institution-approved hosting.
