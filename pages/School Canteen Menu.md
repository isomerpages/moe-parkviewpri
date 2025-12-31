---
title: School Canteen Menu
permalink: /about-us/school-canteen-menu/
description: ""
variant: markdown
---
<div class="canteen-grid">

<div class="canteen-item">
  <img src="/images/About%20Us/Canteen%202026/Stall_1.jpg">
  <p>Stall 1 – Cool Station</p>
</div>

  <div class="canteen-item">
    <img src="/images/About%20Us/Canteen%202026/Stall_2.jpg">
    <p>Stall 2 – Hot Drinks &amp; Snacks</p>
  </div>

  <div class="canteen-item">
    <img src="/images/About%20Us/Canteen%202026/Stall_4.jpg">
    <p>Stall 4 – Chinese Cooked Noodles Stall</p>
  </div>

  <div class="canteen-item">
    <img src="/images/About%20Us/Canteen%202026/Stall_5.jpg">
    <p>Stall 5 – Chinese Food Rice Stall</p>
  </div>

  <div class="canteen-item">
    <img src="/images/About%20Us/Canteen%202026/Stall_7.jpg">
    <p>Stall 7 – Malay Cooked Noodles &amp; Rice</p>
  </div>

</div>


<div id="lightbox">
  <img alt="Expanded canteen image" id="lightbox-img">
</div>


<style>
.canteen-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  padding: 16px;
  justify-items: center;
}

.canteen-item img {
  width: 180px;
  height: 240px;
  object-fit: cover;
  border-radius: 8px;
  cursor: pointer;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  transition: transform 0.2s, box-shadow 0.2s;
}

.canteen-item img:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
}

.canteen-item p {
  text-align: center;
  margin-top: 8px;
  font-size: 14px;
  font-weight: 500;
}

/* LIGHTBOX */
#lightbox {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.85);
  display: none;
  align-items: center;
  justify-content: center;
  z-index: 999;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 8px;
}

/* RESPONSIVE */
@media (max-width: 900px) {
  .canteen-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .canteen-grid {
    grid-template-columns: 1fr;
  }
}
</style>