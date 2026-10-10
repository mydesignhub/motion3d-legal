# MyDesign Studio — legal pages

The public privacy policies of MyDesign Studio's Android apps:

- Motion 3D: https://mydesignhub.github.io/motion3d-legal/
- My Design: https://mydesignhub.github.io/motion3d-legal/my-design/

Each page is generated from its app's own `assets/legal/privacy_policy.txt` by
that app's `tool/build-privacy-page.py` — edit the text there, not here:

    python "Motion 3D 2/tool/build-privacy-page.py" motion3d-legal
    python "My Design/tool/build-privacy-page.py" motion3d-legal/my-design
