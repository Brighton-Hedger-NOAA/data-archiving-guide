---
layout: default
title: Stage 4 - Review the S2N Stub
parent: Full Archive Workflow
nav_order: 5
---

# Stage 4: Review the S2N Stub

From a thurough InPort Record, your Data Manger should create a **S2N** stub for your data. Review the following to ensure accurracy:

<div class="inport-tabs">
  <div class="inport-tab required active" onclick="showTab('people-projects')">People & Projects</div>
  <div class="inport-tab required" onclick="showTab('dates-locations')">Dates & Locations</div>
  <div class="inport-tab required" onclick="showTab('data-types')">Data Types</div>
  <div class="inport-tab required" onclick="showTab('package-summary')">Package Summary</div>
  <div class="inport-tab required" onclick="showTab('update-submit')">Upload & Submit</div>
</div>

<div id="people-projects" class="tab-content active">
    <div class="content-section">
        <h3>Review Responsible Persons:</h3>
        <div class="instruction-box">
            <em>For reference:  <a href="https://docs.google.com/document/d/1rdkL_FRQwnLvBpevDqzkdy_rqf-_XbpCqcYdlQGgrRU/edit?usp=sharing" target="_blank" rel="noopener noreferrer">Scientific Data Roles &amp; External Contacts</a></em>
            <ul>
                <li><strong>Principal Investigator:</strong> Data Steward, usually but not always project lead for the dataset.</li>
                <li><strong>Point of Contact:</strong> Data Manager for the dataset.</li>
                <li>Ideally include at least 2 relevant “responsible” persons <em>(i.e., the Data Steward, Data Manager, Data Archivist, or Project/team Lead)</em></li>
            </ul>
        </div>
    </div>
    <div class="content-section">
        <h3>Review Related Funding Agencies:</h3>
        <div class="instruction-box">
           <ul>
                <li>CRCP (for all NCRMP datasets)</li>
                <li>OAP for some OCC datasets</li>
                <li>USAID</li>
                <li>Could also be PIFSC, Monuments, Marine Debris Program, etc.</li>
            </ul>
        </div>
    </div>
    <div class="content-section">
        <h3>Review Related Projects/Programs:</h3>
        <div class="instruction-box">
            From InPort  <code>Keywords > Theme Keywords > NODC PROJECT NAMES THESAURUS</code>
            <ul>
                <li>National Coral Reef Monitoring Program (NCRMP required)</li>
                <li>CRCP (NCRMP required)</li>
                <li>CORAL REEF STUDIES (NCRMP required)</li>
            </ul>
        </div>
    </div>
</div>

<div id="dates-locations" class="tab-content">
    <div class="content-section">
        <h3>Review Dates:</h3>
        <div class="instruction-box">
            <div class="two-column-grid">
                <div class="field-group">
                    <strong>* Start Date or BCE Year:</strong>
                    <p>From InPort <code>"Extents" > Time Frames</code></p>  
                    <p>YYYY-MM-DD</p>
                </div>
                <div class="field-group">
                    <strong>* End Date or BCE Year:</strong>
                    <p>From InPort <code>"Extents" > Time Frames</code></p>  
                    <p>YYYY-MM-DD</p>
                </div>
            </div>
        </div>
    </div>
    <div class="content-section">
        <h3>Review Location:</h3>
        <div class="instruction-box">
             <p>Bounding coordinates must be exact for the dataset in S2N; obtain directly from the data or QC report.</p> 
             <p>Can also be found from InPort <code>"Extents" > Geographic Area</code>.</p>
        </div>
    </div>
    <div class="content-section">
        <h3>Review Observation Platforms:</h3>
        <div class="instruction-box">
                <p>Platform / Ship Name</p>
                <p>From InPort <code>"Platform Keywords" > NODC PLATFORM NAMES THESAURUS</code></p>
        </div>
    </div>
    <div class="content-section">
        <h3>Review Geographic Regions:</h3>
        <div class="instruction-box">
            <p>From InPort <code>"Spatial Keywords" > NODC SEA AREA NAMES THESAURUS</code></p>
            <ul class="nested-list">
                <li><strong>Hawaiian Archipelago:</strong>
                    <ul class="nested-list">
                        <li>North Pacific Ocean</li>
                        <li>Papahanaumokuakea Marine National Monument (if in the NWHI)</li>
                        <li>Coastal Waters of Hawaii</li>
                    </ul>
                </li>
                <li><strong>Mariana Archipelago:</strong>
                     <ul class="nested-list">
                        <li>NW Pacific</li>
                        <li>Marianas Trench Marine National Monument (if applicable)</li>
                    </ul>
                </li>
                <li><strong>American Samoa:</strong>
                    <ul class="nested-list">
                        <li>South Pacific Ocean</li>
                        <li>Rose Atoll Marine National Monument (if applicable)</li>
                    </ul>
                </li>
                <li><strong>PRIA:</strong>
                    <ul class="nested-list">
                        <li>Equatorial Pacific Ocean</li>
                        <li>Pacific Remote Islands Marine National Monument</li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>
</div>


<div id="data-types" class="tab-content">
    <p>Data types must be applied for each type of metric in the dataset <em>(cover, temperature, pH, taxa id, count, length, weight, etc.)</em> but not for all metrics of the same type. If it is an NCRMP data stream, make sure to add the correct data type from the <a href="https://docs.google.com/spreadsheets/d/1PlG0XM_oFenFuoL63dOn3jFoBtwRLRiw6gvVJoPHK_Q/edit#gid=808566215" target="_blank" rel="noopener noreferrer">NCRMP NODC Controlled Vocab List</a>.</p>
    <div class="content-section">
        <div class="instruction-box">
            <p><strong>Parameter/Variable:</strong><br>
            From InPort <code>Keywords > Theme Keywords > NODC DATA TYPES THESAURUS</code></p>
            <hr>
            <dl class="data-type-dl">
                <dt>Units</dt>
                <dd>From InPort <code>Child Items > Entity > Attribute Summary > Description</code></dd>
                <dt>Observation Category</dt>
                <dd>From InPort <code>Keywords > Theme Keywords > NODC OBSERVATION TYPES THESAURUS</code></dd>
                <dt>Sampling Instrument</dt>
                <dd>From InPort <code>Keywords > Instrument Keywords > NODC INSTRUMENT TYPES THESAURUS</code></dd>
                <dt>Sampling and Analyzing Method</dt>
                <dd>From InPort <code>Lineage > Lineage Statement</code> (and/or relevant <code>Process Steps</code> and <code>Lineage Sources</code>)</dd>
                <dt>Data Quality Method</dt>
                <dd>From InPort <code>Lineage</code> and/or <code>Data Quality</code> </dd>
            </dl>
        </div>
    </div>
</div>


<div id="package-summary" class="tab-content">
    <div class="summary-rows-container">
        <div class="summary-row">
            <div class="summary-label">
                <span class="required-star">*</span> Dataset Title:
            </div>
            <div class="summary-content">
                From InPort <code>Item Identification &gt; Title</code> (dates should be from/to YYYY-MM-DD for dataset).
                <div class="note">
                    <strong>Note:</strong> Make sure the title is descriptive of the dataset or follows the format of the last archived dataset.
                </div>
            </div>
        </div>
        <div class="summary-row">
            <div class="summary-label">
                <span class="required-star">*</span> Abstract / Description:
            </div>
            <div class="summary-content">
                From InPort <code>Item Identification > Abstract</code>.
                <div class="note">
                    <strong>Note:</strong> The S2N abstract should be less verbose than the one in InPort and specific to the exact dataset being archived.
                    <ul>
                        <li><strong>Example:</strong> ‘2024 Vital Rates coral annotations from imagery collected in the Hawaiian Archipelago’ is better than ‘Vital rates coral annotations from 2024 across Pacific Islands regions.’</li>
                    </ul>
                </div>
            </div>
        </div>
         <div class="summary-row">
            <div class="summary-label">
                <span class="required-star">*</span> Suggested Author List:
            </div>
            <div class="summary-content">
                NOAA, Pacific Islands Fisheries Science Center, Ecosystem Sciences Division
            </div>
        </div>
        <div class="summary-row">
            <div class="summary-label">
                Purpose:
            </div>
            <div class="summary-content">
                From <code>Item Identification > Purpose + Supplemental</code>. Provides purpose for the dataset as well as the big-picture context for the surveys.
            </div>
        </div>
        <div class="summary-row">
            <div class="summary-label">
                References:
            </div>
            <div class="summary-content">
                Link for InPort record + any citations directly relevant to the dataset.
                <div class="note">
                    <strong>Note:</strong> Ensure that the correct InPort record URL is provided in the references.
                </div>
            </div>
        </div>
    </div>
</div>

<div id="update-submit" class="tab-content">
    <div class="action-box"><p>Once you have completed all previous sections, please notify your Data Manager or a trained S2N Archivist that your package is ready for them to submit.</p>
        <p>Your notification should include:</p>
        <ul>
            <li>The location of the final data files on the network drives.</li>
        </ul>
    </div>
    <div class="warning-box">
        <ul>
            <li><strong>Do NOT add files directly to this page.</strong> They will not save correctly when you exit S2N.</li>
            <li><strong>Do NOT click the "UPLOAD and SUBMIT" button.</strong> The data archivist will perform the final submission.</li>
        </ul>
    </div>
</div>


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

## Helpful Tools

  *  [Send2NCEI Tool](https://www.ncei.noaa.gov/archive/send2ncei/)

---
<center><a href="{{ '/docs/Stage-5-Review-and-Submission.html' | relative_url }}" class="btn btn-custom fs-6 mb-4 mb-md-0">
  Last Stage: Data Package Submission
</a></center>

