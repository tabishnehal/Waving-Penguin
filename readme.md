# **Built Penguin:penguin::wave: using CSS transforms**

[wavingPenguin.webm](https://user-images.githubusercontent.com/51947285/225391160-76599ab6-58a8-4074-8c13-2d462dd9e6d3.webm)

## [:link: Deployment link](https://tabishnehal.github.io/Waving-Penguin/)
---

### **Steps followed to make Penguin wave :wave: !**

1. **Background -** Applied **linear-gradient** angled 45 degrees clockwise to background.
   - starting & ending with two colors.
2. **Ground -** Created ground div & applied **linear-gradient** angled 90deg clockwise to it.
   - starting & ending with two colors.
3. **Mountains :mountain: -** Created two mountains - left & back-mounatain & applied **linear-gradient** and positioned them properly.
   - starting & ending with two colors.
   - applied **skew** function to left-mountain with 0deg shear to X-axis & 44deg shear to Y-axis.
   - rotated back-mountain by 45deg clockwise.
4. **Sun :sun_with_face: -** Created sun and positioned it to top-right corner such that 75px of it's top and right edges are off screen.
5. **Penguin :penguin: -** Created penguin and positioned it to center horizontally, & it's descendants position absolute.
   - _**penguin head -**_ applied **linear-gradient** angled 45deg clockwise to penguin head, properly positioned & stacked it.
      - created face, chin, eyes, blush, beak, & applied proper styling to all.
   - _**penguin body -**_ applied **linear-gradient** angled 45deg clockwise to penguin body, & properly positioned it.
      - created arms, foot, & applied proper styling to them.
      - created shirt to apply cosmetic content "I 💜 CSS" to penguin body using before pseudo element.
6. **Wave :wave: -** Created a **@keyframes** rule named **wave** with four selectors starting at **10%** and incremented by **10%**.
   - **10% -** applied **rotate** with **110deg** clockwise to **transform** property.
   - **20% -** applied **rotate** with **130deg** clockwise to **transform** property.
   - **30% -** applied **rotate** with **110deg** clockwise to **transform** property.
   - **40% -** applied **rotate** with **130deg** clockwise to **transform** property.
7. **Finally**, applied created **@keyframes** rule named **wave** to left arm of the penguin with **1s** of **animation-duration**, **linear** timing, **infinite** iterative count.


### CSS concepts learned :fire: and applied :hammer_and_wrench:
 - CSS Variables.
 - CSS Animation.
 - CSS Transform.
 - CSS Transition.
 - CSS @keyframes rule.
 - CSS gradient.

If you also want to learn above CSS concepts like I learnt then head over to :link: [w3schools](https://www.w3schools.com/css/css3_2dtransforms.asp), :link: [freeCodeCamp](https://www.freecodecamp.org/).

Don't forget to star :star: if you found it useful.
