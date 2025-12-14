---
layout: default
title: Personal Planner (Power Apps)
---

# Personal Planner (Power Apps)

A personal planner built with **Power Apps** to make **employee planning** simple and efficient.  
Planning of **tasks, orders, and vacation** per employee – fully stored in **Dataverse**.

🔗 **LinkedIn post:**  
[Link](https://www.linkedin.com/posts/fabian-brandt-2b1a36100_poweratelier-powerplatform-lowcode-activity-7405567835789344770-tHUX)

---

## Problem / Goal

The goal was to make **daily planning** in Power Apps more practical and user-friendly:
- fast rescheduling in day-to-day operations
- moving assignments between employees
- fine-grained adjustments on a per-day basis

---

## Key Features

### Drag & Drop Planning
- Planning via **drag & drop** using reusable templates
- Items can be moved between employees or adjusted on a daily level

### Optional: Click-to-Move
For quick changes:
1. Select a planning item
2. Click the target day in the calendar
3. The item is moved to the selected date

### Fully Configurable Layout
- Row height
- Column width
- Pagination
- Date range
- Defaults (e.g. start from “today”)

---

## Data & Architecture

### Dataverse as the Foundation
All planning data is fully stored in **Dataverse**, providing a stable and scalable foundation  
(e.g. for future **Power BI** reporting).

### PCF for Drag & Drop
A **PCF component** is used for drag & drop (by Scott Durow).  
➡️ [Link](https://github.com/scottdurow/power-drag-drop)

The planner logic, data model, and UI behavior are **custom-built**.

---

## Results / Learnings

- Implemented in **4 days**
- Strong focus on clarity, control, and real user requirements
- Comparison: attempts using vibe.powerapps.com / generated pages did not result in a usable solution even after several hours

---

## Roadmap / Ideas
- Power BI dashboard based on Dataverse data
- UX refinements (keyboard support, shortcuts, faster bulk actions)
- Validations (conflicts, capacities, dependencies)

---

## Screenshots / Demo Video

<div class="media-card">
  <iframe
    src="https://www.youtube.com/embed/wguuDynQRZI"
    title="Power Apps Personal Planner"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>

  <div class="media-caption">
    Demo – Personal Planner in Power Apps
  </div>
</div>
