# OUTPUT TEMPLATE: STAGE A (MENU CREATIVE)

When the user requests dish ideas or menu concepts, generate structured options (default: 5 options, or the specific count requested by the user).

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

---

### Closing Prompt:
Ask the user to select their preferred option number or specify adjustments.
