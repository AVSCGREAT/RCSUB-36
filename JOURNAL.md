---
title: "RC Submarine"
author: "@AVSC"  "@Kastriya"
description: "Low-cost, open-source RC submarine for robotics & STEM exploration"
created_at: "2025-07-21"
total time spent: "~32hrs"
---

(A compact underwater rover built for learning, hacking, and diving deep — literally.)

---

### Day 1: research & sketching

**Time Spent:** \~4 hrs  
kicked off with some deep dives (pun intended) into underwater robotics.

* looked at torpedo-style subs and modular robot designs — lots of cool stuff out there but most are $$$.
* focused on how RC ballast systems and waterproof electronics usually work.
* sketched a hybrid layout: main pressure hull + sealed electronics capsule + separate rear drive module.
* idea: make it printable, modular, and super easy to tinker with later.

---

### Day 2: hull design & material plan

**Time Spent:** \~5 hrs  
got to CAD basics and started shaping the sub.

* went for a clean cylindrical hull with rounded nose and tail sections — easier to seal, easy to print.
* started planning how to break up the body for printing: front dome, mid-body, rear shaft mount.
* figured PLA might actually work if sealed right. considered PETG too.
* began scripting parametric parts using OpenSCAD — makes future changes easy.

---

### Day 3: electronics layout & BOM

**Time Spent:** \~4 hrs  
dug into what goes inside this thing.

* selected a 2200KV brushless motor + ESC from old drone stash.
* added 2.4GHz RX/TX module and mini servo for rudder/fins.
* LiPo battery safety was a priority — went for 3S compact packs.
* added slots for LED modules and a basic FPV cam later down the line.

---

### Day 4: 3D modeling sprint

**Time Spent:** \~6 hrs  
pushed hard on modeling everything together.

* designed the prop shaft housing with waterproofing in mind — O-ring channel, sleeve, bushings.
* made the front dome mount with screw slots and tension fit to a printed flange.
* added control fin slots and servo mounts at the rear.
* cleaned up geometry and began splitting STLs for the slicer.

---

### Day 5: budgeting & grant draft

**Time Spent:** \~6 hrs  
switched gears and prepped the Hack Club grant stuff.

* built a full BOM in USD — managed to squeeze under $200 total.
* wrote the project readme + grant pitch, focused on modularity and education use.
* highlighted key design goals: open-source, easy to rebuild, and adaptable for schools or STEM demos.

---

### Day 6: docs & export

**Time Spent:** \~7 hrs  
wrapped up with polish and packaging.

* finalized GitHub README with wiring diagrams and design notes.
* double-checked STL orientation and cleaned up filenames.
* added labels and markers inside CAD files to help with print alignment.
* prepped everything for a first test print once parts arrive.

---

### status update

CAD and STLs are ready. Project folder’s set with documentation and clean exports. Just waiting on a few core electronics:

* Brushless motor + 30A ESC  
* 3S LiPo battery  
* RX/TX module  
* O-rings + waterproof servo  

print test starts as soon as stuff lands. fingers crossed this thing floats — and dives.

---
