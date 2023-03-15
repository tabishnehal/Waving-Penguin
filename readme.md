# **Built Penguin using CSS transform**

![imagename](imagelink)

---

### **Steps followed to make Penguin wave!**

1. **Background -** Applied **linear-gradient** angled 45 degrees clockwise to background.
   - starting & ending with two colors.
2. **Ground -** Created ground div & applied **linear-gradient** angled 90deg clockwise to it.
   - starting & ending with two colors.
3. **Mountains -** Created two mountains - left & back-mounatain & applied **linear-gradient** and positioned them properly.
   - starting & ending with two colors.
   - applied **skew** function to left-mountain with 0deg shear to X-axis & 44deg shear to Y-axis.
   - rotated back-mountain by 45deg clockwise.
4. **Sun -** Created sun and positioned it to top-right corner such that 75px of it's top and right edges are off screen.
5. **Penguin -** Created penguin and positioned it to center horizontally, & it's descendants position absolute.
   - _**penguin head -**_ applied **linear-gradient** angled 45deg clockwise to penguin head, properly positioned & stacked it.
      - created face, chin, eyes, blush, beak, & applied proper styling to all.
   - _**penguin body -**_ applied **linear-gradient** angled 45deg clockwise to penguin body, & properly positioned it.
      - created arms, foot, & applied proper styling to them.
      - created shirt to apply cosmetic content "I 💜 CSS" to penguin body using before pseudo element.
6. **Wave -** Created a **@keyframes** rule named **wave** with four selectors starting at **10%** and incremented by **10%**.
   - **10% -** applied **rotate** with **110deg** clockwise to **transform** property.
   - **20% -** applied **rotate** with **130deg** clockwise to **transform** property.
   - **30% -** applied **rotate** with **110deg** clockwise to **transform** property.
   - **40% -** applied **rotate** with **130deg** clockwise to **transform** property.
7. **Finally**, applied created **@keyframes** rule named **wave** to left arm of the penguin with **1s** of **animation-duration**, **linear** timing, **infinite** iterative count.