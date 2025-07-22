# earthquake_multiples


---

##  Workflow Steps

###  Step 1: Download and Extract Data

- Download from [link](https://www.arcgis.com/home/item.html?id=4aa77ca426364ed9b2b621680f4ea28b)

### Step 2: Symbolize the Earthquakes

1. Use **Graduated Symbols** on the `Quakes6PlusSince1898` layer.
2. Field: `Mag` (Magnitude)
3. Number of Classes: 7
4. Manual class breaks:
   - 6.0 – 6.4  
   - 6.5 – 6.9  
   - 7.0 – 7.4  
   - 7.5 – 7.9  
   - 8.0 – 8.4  
   - 8.5 – 8.9  
   - 9.0+

5. Symbol: Semi-transparent circle (e.g., HEX #00A884, 75% opacity)

---

###  Step 3: Explore Layout & Apply Range Filters

1. Switch to the `Small Multiple Layout` tab.
2. Map frames have been pre-added for each magnitude class.
3. Use **Range Filters**:
   - Right-click map frame → Activate → Range tab
   - Set `Min` and `Max` values (e.g., `Min = 9.0` for the 9+ frame)
4. Deactivate frame view to return to layout.

---

### Step 4: Add Text Labels

1. Use `Insert` → `Rectangle Text` to label each map frame.
2. Example labels:
   - "Magnitude 6.0 – 6.4"
   - ...
   - "Magnitude 9.0+"
3. Customize fonts, colors, and alignment for clarity.

---

### Step 5: Export the Layout

1. Go to `Share` → `Export Layout`
2. Export as PDF or PNG to the `exports/` folder.
3. View and share your static map visualizations.

## Map Generated

![Small Multiple Layout](https://github.com/user-attachments/assets/8f9f5a62-0622-418e-9490-74206b2c1183)


---


