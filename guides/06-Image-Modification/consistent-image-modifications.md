# Consistent Image Modifications with Freepik + AI

A workflow for making **minimal modifications** to images while maintaining **high visual consistency**.

---

## When to Use This Workflow

Use this method when you need to:

| Use Case | Example |
|----------|---------|
| **Change object colors** | White flames → Orange flames |
| **Add/modify character details** | Add a helmet plume, change armor style |
| **Show state transformations** | Empty tank → Filled tank |
| **Adjust scene elements** | Add smoke, change lighting, add reflections |
| **Maintain style across variations** | Same character in different poses |

---

## Step-by-Step Process

### Step 1: Generate JSON from Original Image

1. Upload your **original image** to Freepik
2. Ask Freepik to **generate a detailed JSON description** of the image
3. Save this JSON — it captures all visual attributes (colors, positions, objects, style)

### Step 2: Modify the JSON with AI

1. Share the generated JSON with your AI assistant
2. Describe what changes you want (e.g., "make the flames orange with yellow highlights")
3. AI will update the relevant JSON properties while preserving everything else

### Step 3: Send Modified JSON to Freepik

1. Paste the **modified JSON** into Freepik as your prompt
2. The structured format ensures precise instructions

### Step 4: Add Reference Image

1. **Attach the original image** as a reference image
2. This anchors the generation to your existing style
3. Hit **Generate**

---

## Pro Tips (Optional but Recommended)

| Tip | Why It Helps |
|-----|--------------|
| **Add color reference images** | Ensures exact color matching (e.g., a swatch of the orange you want) |
| **Add object reference images** | Helps with specific object appearances (e.g., a flame style you like) |
| **Keep JSON structure intact** | Only modify the specific properties that need changing |
| **Use hex codes for colors** | More precise than color names (e.g., `#ff7a00` instead of "orange") |

---

## Example: Changing Flame Style

**Original JSON (excerpt):**
```json
"visual_attributes": {
  "color": "White outline, black interior",
  "texture": "Curved flame line art"
}
```

**Modified JSON (excerpt):**
```json
"visual_attributes": {
  "color": "Orange (#ff7a00) with yellow (#ffb84d) highlights",
  "texture": "Smooth stylized shapes"
},
"micro_details": [
  "Flame tips are pointed, layered shapes",
  "Yellow inner flame shapes layered over orange outer flames",
  "Vertical tongues rising upward",
  "Thin smoke outlines in dark gray above largest flames"
]
```

---

## Summary

```
Original Image → Freepik JSON → AI Modifies JSON → Freepik + Reference → Consistent Result
```

This workflow ensures your modifications stay true to the original style while precisely changing only what you specify.
