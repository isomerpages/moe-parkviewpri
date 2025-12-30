---
title: Park View Yearbook
permalink: /park-view-yearbook/
variant: markdown
description: ""
---
<div class="yearbook-grid">
  <div class="yearbook-item">
    <a target="_blank" href="https://go.gov.sg/pvps-yearbook-2025">
      <img src="/images/2025_YB_Cover.jpg">
    </a>
    <p>2025</p>
  </div>
  
  <div class="yearbook-item">
    <a target="_blank" href="https://go.gov.sg/pvps-yearbook-2024">
      <img src="/images/Park_View_Primary_School_Yearook_2024_Page_001.jpg">
    </a>
    <p>2024</p>
  </div>
  
  <div class="yearbook-item">
    <a target="_blank" href="https://go.gov.sg/pvps-2023-yearbook">
      <img src="/images/2023_yearbook_01.jpg">
    </a>
    <p>2023</p>
  </div>
  
  <div class="yearbook-item">
    <a target="_blank" href="https://go.gov.sg/pvps-2022-yearbook">
      <img src="/images/pages%20from%20park%20view%20primary%20school%20photo%2005.jpg">
    </a>
    <p>2022</p>
  </div>
</div>

<style>
.yearbook-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  padding: 16px;
  justify-items: center;
}

.yearbook-item img {
  width: 180px;
  height: 240px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  transition: transform 0.2s, box-shadow 0.2s;
}

.yearbook-item a:hover img {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
}

.yearbook-item p {
  text-align: center;
  margin-top: 8px;
  font-size: 14px;
  font-weight: 500;
}

/* Responsive: 2 columns on tablets, 1 column on phones */
@media (max-width: 900px) {
  .yearbook-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .yearbook-grid {
    grid-template-columns: 1fr;
  }
}
</style>
