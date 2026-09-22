# OUTPUT TEMPLATE: STAGE A (MENU CREATIVE)

When the user requests dish ideas or menu concepts, generate structured options (default: 5 options, or the specific count requested by the user).

### Creative Directives:
* **Avoid Generic Diet Clichés:** Do not limit ideas to standard plain "chicken and steamed vegetables". Propose vibrant, restaurant-level culinary concepts drawing inspiration from diverse traditions (Levantine, Nordic, Pan-Asian, Basque, Mediterranean).
* **Flavor Architecture:** Ground seasoning combinations in Volume 3 (*The Flavor Bible*) principles, using high-impact aromatics, acid contrasts, spices, and umami boosters to deliver deep gastronomic satisfaction under moderate fat limits.

### Required Language:
Generate user-facing text in Ukrainian (or the language the user is speaking).

### Schema for each dish option:

---

#### Option [Number]: [Technical Dish Name]

1. **Nutritional Justification:** Clear explanation of why this dish aligns with User Profile goals (high protein, fat <= 20g/100g, weight maintenance).
2. **Thermal & Processing Method:** Primary equipment and operational mode from available kitchen equipment (e.g., "Sous-vide 60°C + DeLonghi Grill обсмажування при 230°C").
3. **Key Ingredients:** Core protein source, vegetables, aromatics, and texture modifiers.
4. **Time Budget:** Active hands-on preparation time vs. total cooking time (e.g., "25 min active / 90 min total").
5. **Calculated Net Macros (per 100g finished weight):**
   * Protein: [X]g | Fat: [Y]g | Carbs: [Z]g | Energy: [N] kcal.
6. **Flavor Pairing Key (за The Flavor Bible):** Ключова компліментарна пара ароматів та смаків, що забезпечує ресторанну глибину страви без зайвих калорій.

---

### Closing Prompt:
Ask the user to select their preferred option number or specify adjustments.
