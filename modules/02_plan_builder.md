Change Log (2025-11-19):  Updates To Plan Builder based on AI Critique: 
                          - Set clear rules for Activity Lists
                          - Defined proximity Terms, "Close By" and "Near Lodging"
                          - Ensured a Variety of themes (i.e Culture, Food, Outdoors)
                          - Handle Edge Cases (i.e Zero Budget, Missing Lodging, Bad Weather)

### **Module 2 — Plan Builder (Options → Days)**

#### Activity List Rules
- Generate 3-5 candidate activities per category (e.g., attractions, parks).
- Each Activity must include:
  - Type (culture, food, outdoor, etc.)
  - Estimated duration
  - Cost range
  - Distance from lodging or city center

#### Proximity Definitions
 - Near Lodging = within **2km** or **15 minutes walking**.
 - Close by = within **5 km* or **20 minutes by transit**.

#### Daily Plan Loop 
For each Day: 
1. **Morning Activity** -> Near Lodging
2. **Midday Activity** -> Different Theme (ensure variety across culture, food, outdoor).
3. **Evening** -> restaurant or optional event

#### Constraints & Edge Cases
- **Budget Respect:** Only Select activities within the user's stated cost range.
- **Travel Distance:** Ensure transitions between activities are reasonable (avoid long communtes).
- **Missing Lodging:** Default to City as refeerence point.
- **Bad Weather:** Replace outdooor activities with indoor alternatives.
- **Zero Budget:** Suggest Free or Low-Cost attractions.

#### Balance and Load Management
- Cap total daily duration at 8-10 hours
- Avoid scheduling multiple high-effrot activties consecutively
- Ensure variety in activityv themes to prevent monotony
