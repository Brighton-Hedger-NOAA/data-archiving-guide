---
layout: default
title: Stage 2 - Fill Out InPort Record
parent: Full Archive Workflow
nav_order: 2
---

# Stage 2: Fill Out InPort Record
### After setting up an InPort record from scratch or by cloning and existing one, you will fill in placeholder text until yourve collected your data. The tabs in  <span style="color: #003366; font-weight: bold; background-color: #e6f2ff; border: 1px solid #b3d7ff; padding: 2px 6px; border-radius: 4px;">blue</span> indicate sections will need placeholder info. Click each tab to see the required actions.

<div class="inport-tabs">
  <div class="inport-tab active" onclick="showTab('summary')">Summary</div>
  <div class="inport-tab required" onclick="showTab('item-id')">Item Identification</div>
  <div class="inport-tab" onclick="showTab('keywords')">Keywords</div>
  <div class="inport-tab" onclick="showTab('location')">Physical Location</div>
  <div class="inport-tab" onclick="showTab('dataset-info')">Data Set Info</div>
  <div class="inport-tab" onclick="showTab('support-roles')">Support Roles</div>
  <div class="inport-tab required" onclick="showTab('extents')">Extents</div>
  <div class="inport-tab" onclick="showTab('access-info')">Access Info</div>
  <div class="inport-tab required" onclick="showTab('distribution-info')">Distribution Info</div>
  <div class="inport-tab" onclick="showTab('urls')">URLs</div>
  <div class="inport-tab" onclick="showTab('tech-env')">Tech Environment</div>
  <div class="inport-tab" onclick="showTab('data-quality')">Data Quality</div>
  <div class="inport-tab" onclick="showTab('data-management')">Data Management</div>
  <div class="inport-tab" onclick="showTab('lineage')">Lineage</div>
  <div class="inport-tab" onclick="showTab('acquisition')">Acquisition Info</div>
  <div class="inport-tab" onclick="showTab('child-items')">Child Items</div>
  <div class="inport-tab" onclick="showTab('related-items')">Related Items</div>
  <div class="inport-tab" onclick="showTab('catalog-details')">Catalog Details</div>
</div>

<div id="summary" class="tab-content active"><p>Summary will populate from other tabs. No information is needed.</p></div>

<div id="item-id" class="tab-content">
  <p><strong>Update Publication Date:</strong> Update to the year you are currently updating the record.  
  <br>
  <strong>Add placeholder Abstract</strong> </p>
</div>

<div id="keywords" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="location" class="tab-content"><p>No placeholder needed.</p></div>

<div id="dataset-info" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="support-roles" class="tab-content">
  <p>No placeholder needed..</p>
</div>

<div id="extents" class="tab-content">
  <p><strong>Add placeholder Timeframe and Lat/Lon</strong></p>
</div>

<div id="access-info" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="distribution-info" class="tab-content">
  <p><strong> Add placeholder Distribution Info </strong>></p>
</div>

<div id="urls" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="tech-env" class="tab-content"><p>No placeholder needed.</p></div>

<div id="data-quality" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="data-management" class="tab-content"><p>No placeholder needed.</p></div>

<div id="lineage" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="acquisition" class="tab-content"><p>No placeholder needed.</p></div>

<div id="child-items" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="related-items" class="tab-content">
  <p>No placeholder needed.</p>
</div>

<div id="catalog-details" class="tab-content"><p>No placeholder needed.</p></div>


<script>
  function showTab(tabId) {
    document.querySelectorAll('.tab-content').forEach(tab => {
      tab.classList.remove('active');
    });
    document.querySelectorAll('.inport-tab').forEach(tab => {
      tab.classList.remove('active');
    });
    document.getElementById(tabId).classList.add('active');
    event.target.classList.add('active');
  }
</script>









---
<center><a href="{{ '/docs/Stage-2.5-Prep-and-QC-Your-Data.html' | relative_url }}" class="btn btn-custom fs-6 mb-4 mb-md-0">
  Next Stage: Prep and QC Your Data
</a></center>
