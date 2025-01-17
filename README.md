# doubt-that-the-sun-doth-move

This is something that's been knocking around in my head for a while, inspired by [Sun by Philip Schütte](https://www.wonderspaces.com/artists/philip-schutte). Basically you have an installation which is a screen with a horizon and sky projected onto it, and in front of it is a physical space where observers can pick up a ball and move it around. The screen shows the "sun" moving around/setting/rising to mimic the movements of the ball. Compelling!

#### Sun, by Philip Schütte
<img width="767" alt="Screenshot 2025-01-17 at 9 49 02 AM" src="https://github.com/user-attachments/assets/6b6792d2-2122-4106-af1f-be9301663be6" />

I've thought of a few different ways to implement this -- it could be an animated gradient that tracks the cursor in something like React, with the gradients shifting into sunset colors as the cursor approaches the "horizon" line, or it could be an actual light source in a threejs setup. 
