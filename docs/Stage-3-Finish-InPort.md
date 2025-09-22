---
layout: default
title: Stage 3 - Finish InPort Record
parent: Full Archive Workflow
nav_order: 4
---

# Stage 3: Finish InPort Record
### After the data is ready to be archived you will finish filling out your InPort record. The tabs in  <span style="color: #003366; font-weight: bold; background-color: #e6f2ff; border: 1px solid #b3d7ff; padding: 2px 6px; border-radius: 4px;">blue</span> indicate sections that typically require updates. Click each tab to see the required actions.


<div class="inport-tabs">
  <div class="inport-tab active" onclick="showTab('summary')">Summary</div>
  <div class="inport-tab required" onclick="showTab('item-id')">Item Identification</div>
  <div class="inport-tab required" onclick="showTab('keywords')">Keywords</div>
  <div class="inport-tab required" onclick="showTab('location')">Physical Location</div>
  <div class="inport-tab required" onclick="showTab('dataset-info')">Data Set Info</div>
  <div class="inport-tab required" onclick="showTab('support-roles')">Support Roles</div>
  <div class="inport-tab required" onclick="showTab('extents')">Extents</div>
  <div class="inport-tab required" onclick="showTab('access-info')">Access Info</div>
  <div class="inport-tab required" onclick="showTab('distribution-info')
  ">Distribution Info</div>
  <div class="inport-tab required" onclick="showTab('urls')
  ">URLs</div>
  <div class="inport-tab" onclick="showTab('tech-env')">Tech Environment</div>
  <div class="inport-tab required" onclick="showTab('data-quality')">Data Quality</div>
  <div class="inport-tab" onclick="showTab('data-management')">Data Management</div>
  <div class="inport-tab required" onclick="showTab('lineage')">Lineage</div>
  <div class="inport-tab required" onclick="showTab('acquisition-info')">Acquisition Info</div>
  <div class="inport-tab required" onclick="showTab('child-items')">Child Items</div>
  <div class="inport-tab required" onclick="showTab('related-items')">Related Items</div>
  <div class="inport-tab" onclick="showTab('catalog-details')">Catalog Details</div>
</div>
<div id="summary" class="tab-content active"><p>Summary will populate from other tabs. No information is needed.</p></div>

<div id="item-id" class="tab-content"><p>
<ul>
  <li>
    <strong>Title:</strong> NCRMP: WHAT (metrics) + WHERE (region) + WHEN (from/to)
    <ul>
      <li><em>If Title includes “...since YEAR” change it to “...from YEAR to YEAR”</em></li>
      <img width="750" height=auto alt="Example:" src="{{ '/assets/screenshot-2025-08-01-120531.png' | relative_url }}" />
    </ul>
  </li>
  <li>
    <strong>Short Name:</strong> Add a short name if one isn’t already given 
    <ul>
      <li><em>If NCRMP, start with NCRMP: dataset</em></li>
      <img width="500" height=auto alt="Example:" src="{{ '/assets/screenshot-2025-08-01-122436.png' | relative_url }}" />
    </ul>
  </li>
  <li>
    <strong>Status:</strong> 
    <ul>
      <li>If NCRMP = ongoing</li>
      <li>If one-off project = completed</li>
    </ul>
  </li>
  <li>
    <strong>Creation Date:</strong> Month and year when the first dataset files included in the InPort record were submitted to NCEI
    <ul>
      <li><em>File date of data in <code>T:\DataManagement\NCEI Archive Packages\</code></em></li>
    </ul>
  </li>
  <li>
    <strong>Revision Date:</strong> Month and year you are revising the record with the new set of data
  </li>
  <li>
    <strong>Publication Date:</strong> Update YEAR to reflect when the dataset will be published or republished with new data
  </li>
    <div style="padding-left: 3em;">
        <em><img width="250" height=auto alt="Example:" src="{{ '/assets/Screenshot-2025-08-01-122859.png' | relative_url }}" /></em>
    </div>   
  <li>
    <strong>Abstract:</strong> About the dataset — who, what, where, when, and a brief how
    <ul>
      <li>Who: PIFSC and ESD and CRCP (or NCRMP)</li>
      <li>Update to reflect latest mission/surveys</li>
      <li>Be sure to describe/emphasize the dataset to be archived (not the analysis, publication, or project).</li>
      <li>
        <em>Example:</em><br/>
        <blockquote>
        The data described here include <strong>XXXX</strong> data collected as part of NOAA's ongoing National Coral Reef Monitoring Program (NCRMP). These data were gathered around <strong>REGION AND/OR ISLAND(S)</strong> from <strong>DATE</strong> to <strong>DATE</strong> as a part of the NOAA Pacific Islands Fisheries Science Center (PIFSC), Ecosystem Sciences Division (formerly the Coral Reef Ecosystem Division) led NCRMP mission to <strong>REGION AND/OR ISLAND(S)</strong> in <strong>YYYY</strong>. The variables of <strong>XXXX</strong> were recorded by SCUBA divers during surveys at NCRMP climate stations. A select number of climate sites were chosen per island in hard-bottom habitat at 15-m depths in a stratified random fashion. To record <strong>XXXX</strong>, the divers... [brief overview of method]
        </blockquote>
      </li>
    </ul>
  </li>
  <li>
    <strong>Purpose:</strong> Why this dataset matters — what purpose does it serve?
    <ul>
      <li>
        <em>Example:</em><br/>
        <blockquote>
        Water temperature time series data aid in the monitoring of seawater temperature variability and are used to help scientists assess and understand how coral reefs monitored as part of the NOAA National Coral Reef Monitoring Program (NCRMP) are responding to thermal stress.
        </blockquote>
      </li>
    </ul>
  </li>
  <li>
    <strong>Notes:</strong>
    <ul>
      <li>Address any issues/questions/updates, then delete notes before submission</li>
      <li>You can also add a note for anything you’re not sure about, and we’ll figure out what to do with it.</li>  
      <li><strong>It should be deleted before the record is published and exported for NCEI </strong></li>
    </ul>
  </li>
  <li>
    <strong>Citation:</strong> Add any directly relevant publication citations (e.g., SOP, reports, summary briefs)
    <ul>
      <li>Drafts are okay — just indicate so</li>
    </ul>
  </li>
  <li>
    <strong>Supplemental Info:</strong> Big-picture context — if part of NCRMP, RAMP, or a one-off project, describe it here
    <ul>
      <li>
        <strong><u>Supplemental Info for Ecological Data:</u></strong><br/>
        <blockquote>
       <p>The NOAA National Coral Reef Monitoring Program (NCRMP) details a long term approach to provide an ecosystem perspective via monitoring climate, fish, benthic, and socioeconomic variables in a consistent and integrated manner. The NCRMP coordinates various NOAA Coral Reef Conservation Program (CRCP) biological, physical, and human dimensions activities into a cohesive NOAA-wide effort. Through the implementation of the NCRMP, NOAA is able to clearly and concisely communicate results of national-scale monitoring to national, state, and territorial policy makers, resource managers, and the public on a periodic basis.</p>
        <p> NCRMP is a framework for conducting sustained observations of biological, climate, and socioeconomic indicators at 10 priority coral reefs across the U.S. and its territories. This integrated approach consolidates monitoring of coral reefs under a uniform method in the Pacific, Atlantic, Caribbean, and the Gulf of Mexico for the first time. NCRMP is funded by the CRCP and supported by NOAA Fisheries, NOAA National Centers for Coastal Ocean Science (NCCOS), and many other partners. The PIFSC Ecosystem Sciences Division (ESD) at NOAA Fisheries is leading biological monitoring in the U.S. Pacific Islands Region. </p>
        <p> The biological component of NCRMP in the Pacific provides a triennial ecological characterization at a broad spatial scale of general reef condition for reef fishes, corals and benthic habitat (i.e., fish species composition/density/size, benthic cover, and coral density/size/condition). Innovative analysis techniques are then used to develop products that give fellow scientists, managers, decision makers and the public a better understanding of a region’s resources and how they are changing over time. </p> 
        </blockquote>
      </li>
      <li>
        <strong><u>Supplemental Info for Climate Data:</u></strong><br/>
        <blockquote>
        <p> The NOAA National Coral Reef Monitoring Program (NCRMP) details a long term approach to provide an ecosystem perspective via monitoring climate, fish, benthic, and socioeconomic variables in a consistent and integrated manner. The NCRMP coordinates various NOAA Coral Reef Conservation Program (CRCP) biological, physical, and human dimensions activities into a cohesive NOAA-wide effort. Through the implementation of the NCRMP, NOAA is able to clearly and concisely communicate results of national-scale monitoring to national, state, and territorial policy makers, resource managers, and the public on a periodic basis.</p>
        <p> NCRMP is a framework for conducting sustained observations of biological, climate, and socioeconomic indicators at 10 priority coral reefs across the U.S. and its territories. This integrated approach consolidates monitoring of coral reefs under a uniform method in the Pacific, Atlantic, Caribbean, and the Gulf of Mexico for the first time. NCRMP is funded by the Coral Reef Conservation Program (CRCP) and supported by NOAA Fisheries, NOAA National Centers for Coastal Ocean Science (NCCOS), NOAA’s Atlantic Oceanographic & Meteorological Laboratory (AOML), NOAA Coral Reef Watch, and many other partners. The Ecosystem Sciences Division (ESD) at NOAA Fisheries is leading in-situ climate monitoring in the U.S. Pacific Islands Region.</p>
        <p> The climate component of NCRMP in the Pacific provides a comprehensive view of climate change impacts on coral reef ecosystems and helps identify areas of resilience and vulnerability. The key indicators used to identify and monitor climate-driven trends include 1) thermal stress caused by changes in sea temperature, 2) ocean acidification resulting from changes in carbonate chemistry, and 3) ecological impacts by collecting data on coral growth rates, erosion, and community structure to understand the impacts of thermal stress and ocean acidification on the ecosystem. Each year, ESD scientists work closely with CRCP and partners during Reef Assessment and Monitoring Program (RAMP) missions to collect data using moored oceanographic and ecological instruments stationed at fixed sites in the Pacific Ocean, and water samples collected by divers. The in-situ data and satellite-based observations are also used in modeling efforts. Innovative analysis techniques are used to develop products that give fellow scientists, managers, decision makers and the public a better understanding of a region’s resources and how they are changing over time.</p>
        </blockquote>
      </li>
    </ul>
  </li>
  <li>
    <strong>DOI:</strong> Assigned only to NCRMP datasets (NCEI Collection) by CRCP
    <ul>
      <li>Usually applies only to NCRMP data</li>
      <li>
        To find the DOI:
        <ul>
          <li>Navigate to an existing dataset accession in the InPort record</li>
          <li>Go to Distribution Info → Accession URL → Documentation tab → NCEI Collection under Associated Resources</li>
          <li>Copy the Dataset Identifier (not the full link)</li>
          <li>
        Example: <code>10.7289/V59s6vcf5</code> (use the identifier only)
      </li>
        </ul>
      </li>      
      <li>This is NOT the DOI for the related publication</li>
    </ul>
  </li>
  <li>
    <strong>DOI Registration Authority:</strong> NOAA
  </li>
</ul>
</p></div>

<div id="keywords" class="tab-content">
  <p> <ul>
    <li>InPort uses both <strong>CONTROLLED</strong> and <strong>UNCONTROLLED</strong> keywords.
      <ul>
        <li>Controlled keywords (GCMD thesauri) are required for CoRIS and help users find datasets on platforms like DATA.GOV and OneStop.</li>
        <li>Uncontrolled keywords (Theme) provide additional descriptive information.</li>
        <li>Keywords can be cloned from similar records to save time.</li>
      </ul>
    </li>
    <li><strong>Controlled Keywords:</strong>
      <ul>
        <li>Include:
          <ul>
            <li>Ecosystem Sciences Division as GCMD Data Center</li>
            <li>Coral Reef, Benthic, and other relevant GCMD Science Keywords</li>
            <li>Applicable GCMD Location, Instrument, and Platform Keywords</li>
          </ul>
        </li>
        <li>Add an ISO 19115 Topic Category (e.g., Biota, Oceans, Environment)</li>
       <div style="padding-left: 2em;">
             <em><img width="500" height=auto alt="Example:" src="{{ '/assets/Screenshot-2025-08-01-131806.png' | relative_url }}" /></em>
        </div> 
      </ul>
    </li>
    <li><strong>Uncontrolled Keywords (Theme):</strong>
      <ul>
        <li><a href="https://gcmd.earthdata.nasa.gov/KeywordViewer/scheme/all/ea7d9260-7e8f-4c53-89c4-f1b4bccc5a63">CoRIS Discovery Thesaurus</a> (required, only 1):
          <ul>
            <li>Numeric Data Sets > Benthic</li>
            <li>Numeric Data Sets > Biology</li>
            <li>Numeric Data Sets > Calcification Rate</li>
            <li>Numeric Data Sets > Chemistry</li>
            <li>Numeric Data Sets > Fish Census</li>
            <li>Numeric Data Sets > Oceanography</li>
            <li>Visual Images > Habitats</li>
          </ul>
        </li>
        <li><a href="https://data.nodc.noaa.gov/cgi-bin/iso?id=gov.noaa.nodc:ISO_19115_1">CoRIS Theme Thesaurus</a> (at least 1): match the ISO Topic Category.</li>
      </ul>
    </li>
    <li><strong>CRCP Project ID (if CRCP funded):</strong>
      <ul>
        <li><strong>NCRMP (2013+):</strong> 743 – National Coral Reef Monitoring Program</li>
        <li><strong>FY12:</strong> 587 – Pacific Reef Assessment and Monitoring Program</li>
        <li><strong>FY11 & earlier:</strong> 1221 – Pacific RAMP Biennial Monitoring</li>
      </ul>
    </li>
    <li><strong>NODC Thesauri:</strong>
      <ul>
        <li><strong>Observation Types:</strong> One observation type + one data type per metric.
          <ul>
            <li>e.g., survey, in situ, satellite data, visual assessment</li>
          </ul>
        </li>
        <li><strong>Data Types:</strong> e.g., percent cover, biomass, conductivity</li>
        <li>Use the NCRMP <a href="https://www.ncei.noaa.gov/data/oceans/ncei/ocads/metadata/NCRMP_NODC_Controlled_Vocabulary.xlsx">Controlled Vocabulary</a> as reference.</li>
      </ul>
    </li>
    <li><strong>Project, Institution, and Exclusion Keywords:</strong>
      <ul>
        <li><strong>NODC Project Thesaurus:</strong>
          <ul>
            <li>Coral Reef Conservation Program</li>
            <li>National Coral Reef Monitoring Program</li>
            <li>Pacific RAMP</li>
          </ul>
        </li>
        <li><strong>NODC Submitting Institution:</strong> e.g., US DOC, NOAA, NMFS, PIFSC, CRED</li>
        <li><strong>PARR Exclusion (optional):</strong> e.g., Non-Federal Funding, Legacy Data Set</li>
      </ul>
    </li>
    <li><strong>Instrument:</strong>
      <ul>
        <li>TYPE = INSTRUMENT</li>
        <li>Use NODC INSTRUMENT TYPES THESAURUS if possible</li>
        <li>Examples: ADCP, CTD, fluorometer, GPS, STR, CTD etc.</li>
      </ul>
    </li>
    <li><strong>Platform:</strong>
      <ul>
        <li>Use <a href="https://www.ncei.noaa.gov/access/inport/item/1251659">NODC PLATFORM NAMES THESAURUS</a></li>
        <li>Examples: Hi‘ialakai, Oscar Elton Sette, Small Vessels</li>
        <li>TYPE = PLATFORM</li>
      </ul>
    </li>
    <li><strong>Spatial/Place:</strong>
      <ul>
        <li><a href="https://www.coris.noaa.gov/data/supportrngdocs.html#keywords">CoRIS Place Thesaurus</a>: 1+ pair per region</li>
        <li>One for COUNTRY/TERRITORY and one for OCEAN BASIN</li>
        <li>Examples:
          <ul>
            <li>COUNTRY/TERRITORY = Northern Mariana Islands</li>
            <li>OCEAN BASIN = Western Pacific Ocean</li>
          </ul>
        </li>
        <li>Also add keywords from:
          <ul>
            <li><a href="https://gcmd.earthdata.nasa.gov/KeywordViewer/scheme/all/a4523ae1-d49a-45cf-98e0-eed261e0ac8b">Pacific Country Thesaurus</a></li>
            <li><a href="https://gcmd.earthdata.nasa.gov/KeywordViewer/scheme/all/fb050d4f-ec8e-43ed-89f0-393f209c53c3">Pacific Ocean Thesaurus</a></li>
            <li>NODC SEA AREA NAMES THESAURUS</li>
          </ul>
        </li>
      </ul>
    </li>
  </ul></p></div>

<div id="location" class="tab-content">
  <p style="padding-left: 3em;">
    <img width="450" height="auto" alt="A descriptive summary of the image" src="{{ '/assets/Screenshot202509-22074120.png' | relative_url }}" />
  </p>
</div>

<div id="dataset-info" class="tab-content">
  <p>
    <ul>
      <li>
        <strong>Entity Attribute Overview</strong>
        <ul>
          <li>A summary of the info/metrics included in the dataset that are defined in the CHILD / Entity record. You do not need to list each column/header, just an overview of what the user can expect to find in the dataset.</li>
        </ul>
        <ul>
          <li><strong>Example:</strong> <em>Raw survey data includes metadata for each survey (where, when, who, area); site characteristics (depth, reef type, habitat); unique image name and individual point observations identified at three functional group levels of benthic cover: Tier 1 (e.g., hard coral, soft coral, macroalgae, turf algae, etc.), Tier 2 (e.g., Hard Coral = massive, branching, foliose, encrusting, etc.; Macroalgae = upright macroalgae, encrusting macroalgae, bluegreen macroalgae, and Halimeda, etc.), and Tier 3 (e.g., Hard Coral = Astreopora sp, Favia sp, Pocillopora, etc.; Macroalgae = Caulerpa sp, Dictyosphaeria sp, Padina sp, etc.).
          <br>A data dictionary is included to define columns in the datasets (https://www.fisheries.noaa.gov/inport/item/76707, https://www.fisheries.noaa.gov/inport/item/77555, https://www.fisheries.noaa.gov/inport/item/76863, https://www.fisheries.noaa.gov/inport/item/76862).
          <br>An image classification scheme is also included to describe the classification used with the CoralNet annotation tool (https://www.fisheries.noaa.gov/inport/item/74875).</em> </li>
        </ul>
      </li>
      <li>
        <strong>Data Set Credit</strong>
        <ul>
          <li>Usually: NOAA Fisheries, ESD and funded by the NOAA CRCP.</li>
          <li>If there are many funders or partners, for example:
            <ul>
              <li>NOAA Fisheries, Ecosystem Sciences Division and partners, with support from the Census of Marine Life (2008-2010), NOAA's Ocean Acidification Program (2010-2012), and from the Coral Reef Conservation Program (2012-2019).</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </p>
</div>

<div id="support-roles" class="tab-content">
  <p>
    <ul>
      <li><strong>Originator:</strong> the agency data owner; PIFSC</li>
      <li><strong>Data Set Credit:</strong> the data funder; CRCP</li>
      <li><strong>Data Steward:</strong> person most knowledgeable about the data and its collection/processing</li>
      <li><strong>Point of Contact:</strong> PI/project lead of the data steward, if appropriate</li>
      <li><strong>Distributor:</strong> internal distributor (with FROM and TO date) and NCEI (with only FROM date)</li>
      <li><strong>Metadata contact:</strong> the InPort liaison to PIFSC; your Data Manager</li>
    </ul>
  </p>
</div>

<div id="extents" class="tab-content">
  <p>Define the geographic and temporal boundaries of the dataset.</p>
  <ul>
    <li><strong>Add Timeframe:</strong> Use the minimum and maximum dates directly from the dataset file to define the time range for the region.</li>
    <li><strong>Add Geographic Regions:</strong> Verify that the maximum latitude and longitude from your dataset fall within the bounding box defined in the InPort record.</li>
  </ul>
</div>

<div id="access-info" class="tab-content">
  <p>
    <ul>
      <li>Check the box for Standard NOAA Data License</li>
      <li>Content filled in from template by data management</li>
      <li>In the example citation, copy the InPort citation in the header</li>
      <li><strong>PLEASE UPDATE ANY MENTIONS OF <em>“CREP”</em> TO <em>“ESD”</em> IF APPLICABLE TO YOUR RECORD</strong></li>
    </ul>
  </p>
</div>

<div id="distribution-info" class="tab-content">
  <p>
    <em>Add a new distribution for every file to be included in your data package (except for the data dictionary).</em>
    <br><br>
    <strong>The following distributions should be included (if relevant):</strong>
    <ul>
      <li>Archived datasets</li>
      <li>SOPs/Protocols (NCRMP Docs Only <a href="https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0157633" target="_blank" rel="noopener noreferrer">accession 0157633</a>)</li>
      <li>Reports / Briefs (NCRMP Docs Only <a href="https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0157633" target="_blank" rel="noopener noreferrer">accession 0157633</a>)</li>
      <li>ERDDAP link to specific dataset (use “CRCP” in keyword search to filter datasets)</li>
      <li>OBIS link to specific dataset:
        <ul>
          <li>Click on DATASETS and use these DATASET NAME search strings to find data:
            <ul>
              <li>“CRED” - these were submitted ~10 years ago and need to be updated</li>
              <li>“Pacific Islands Fisheries” - recently updated (fish BLT and StRS nSPC)</li>
              <li>“Pacific Reef Assessment” - recently updated (fish SPC)</li>
            </ul>
          </li>
          <li>Click the green SAVE button.</li>
          <li>Under the LAYERS tab, click the green hamburger button / menu > VIEW DATA.</li>
          <li>At the bottom of the page, click the TITLE to go to the dataset page and copy the link.</li>
        </ul>
      </li>
    </ul>
    <br>
    <strong>For each DISTRIBUTION entry:</strong>
    <ul>
      <li><strong>Start Date:</strong>
        <ul>
          <li>If data are already archived, you can get the date from the NCEI Accession > Description tab > Publication Date.</li>
          <li>Otherwise, data management will fill in the date when they receive the auto-generated email with the subject “NCEI online publication confirmation of NCEI Accession #”.</li>
          <li>Use NULL if the dataset is not yet accessioned AND not yet published online.</li>
        </ul>
      </li>
      <li><strong>End Date:</strong> Always blank.</li>
      <li><strong>Download URL:</strong>
        <ul>
          <li>Add a link to the NCEI accession.</li>
          <li>All distributions for one year will have the same accession URL.</li>
          <li>If the data package has not yet been archived, use this placeholder: <code>http://accession.nodc.noaa.gov/accession#</code></li>
        </ul>
      </li>
      <li><strong>Distributor:</strong> NCEI, Silver Spring, MD</li>
      <li><strong>File Name:</strong> Be thoughtful with file names (what, where, when) and be consistent.</li>
      <li><strong>Description:</strong> Give a thorough description of what’s included in the file/data package.</li>
      <li><strong>File Date:</strong> When was the file exported from the database? Update if the data are revised.</li>
      <li><strong>Distribution Format:</strong>
        <ul>
          <li>Use archive-friendly formats (e.g., CSV, JPEG, shapefile). See the full list <a href="https://www.fisheries.noaa.gov/inport/help/distribution-format" target="_blank" rel="noopener noreferrer">here</a>.</li>
          <li>The 'File type' should be the actual format (e.g., csv).</li>
          <li>If the file is a zipped folder, specify this under ‘Compression Type’.</li>
          <li>More info:
            <ul>
                <li><a href="https://www.fisheries.noaa.gov/inport/help/distribution-format-changes" target="_blank" rel="noopener noreferrer">Format Changes</a></li>
                <li><a href="https://www.fisheries.noaa.gov/inport/help/distribution-format" target="_blank" rel="noopener noreferrer">Format Help</a></li>
            </ul>
          </li>
        </ul>
      </li>
      <li><strong>File Size:</strong> Useful to include if the file is large (e.g., benthic images, temperature time series).</li>
    </ul>
  </p>
</div>

<div id="urls" class="tab-content">
  <p>
    Relevant information that DOES NOT need to be archived with the data (e.g., a project website). URLs should at least include the following, if relevant:
    <ul>
      <li>Update former PIFSC websites with the new fisheries website link: <a href="https://www.fisheries.noaa.gov/region/pacific-islands#science" target="_blank" rel="noopener noreferrer">https://www.fisheries.noaa.gov/region/pacific-islands#science</a></li>
      <li>NOAA National Coral Reef Monitoring Program: <a href="https://www.coris.noaa.gov/monitoring/" target="_blank" rel="noopener noreferrer">https://www.coris.noaa.gov/monitoring/</a></li>
      <li><strong>Browse graphic:</strong> Add a URL for an image online that can represent the data.</li>
      <li>If a PIFSC image link is broken, replace this part of the URL <code>www.pifsc.noaa.gov</code> with this <code>origin-apps-pifsc.fisheries.noaa.gov</code>.</li>
    </ul>
  </p>
</div>

<div id="tech-env" class="tab-content">
  <p>Name of Oracle View, Access database/query, R script, ArcGIS tools/version</p></div>

<div id="data-quality" class="tab-content">
  <p>
    Up to 15 fields can be described if needed, applicable, or useful to an end-user. These fields are required:
    <ul>
      <li>Accuracy</li>
      <li>Completeness Report</li>
      <li>Conceptual Consistency</li>
      <li>Quality Control Procedures</li>
    </ul>
  </p>
</div>

<div id="data-management" class="tab-content">
  <p> No information typically needs to be entered or changed in this section for this workflow.</p></div>

<div id="lineage" class="tab-content">
  <p>
    <strong>aka Methods / Process</strong>
    <ul>
      <li><strong>Lineage Statement:</strong> A brief, high-level summary of the methodology. Details should be reserved for one to many process steps, depending on the dataset and if a published SOP exists.</li>
      <li><strong>Sources:</strong> Include the citation and URL of related SOPs/Procedures.</li>
      <li><strong>Process Steps:</strong> If a comprehensive SOP is accessible online, a brief method description is acceptable.</li>
      <li>You can have one to many sources and one to many process steps, but you can only link one source to a process step (linking is optional).</li>
    </ul>
  </p>
</div>

<div id="acquisition-info" class="tab-content">
    <p><ul>
      <li>
        <strong>Instruments:</strong> Work with your Data Manager to add instruments if applicable, otherwise set to “Not applicable”.
      </li>
      <li>
        <strong>Platforms:</strong> Add platforms if applicable to the dataset (see KEYWORDS). See the example below for diel surveys, otherwise set to “Not applicable”.
        <div style="padding-left: 2em; padding-top: 0.5em;">
          <em><img width="850" height="auto" alt="Example of diel suite platform entry in InPort" src="{{ '/assets/Screenshot2025-09-22085529.png' | relative_url }}" /></em>
        </div>
      </li> </ul>
    </p>
</div>

<div id="child-items" class="tab-content">
  <p>This section is the <strong>Data Dictionary</strong>, also referred to as the "InPort record entity." You reviewed and updated this in the previous stage, so this section should be accurate.
  <ul>
      <li>
        <strong>Add a New Child Record</strong>
        <ul>
          <li><strong>CLONE/COPY an existing CHILD record</strong>
            <ul>
              <li>Identify the InPort ID for the CHILD/ENTITY record that you wish to COPY. <em>Be sure to get the ID from the ENTITY record and not the DATASET record.</em></li>
              <li>Go to the DATASET record that you want to add a new CHILD record to.</li>
              <li>Click the ITEM menu and choose ADD CHILD ITEM.</li>
              <li>Catalog Item Type = ENTITY</li>
              <li>Add a specific name for the entities for the dataset.</li>
              <li>Clone from CAT ID = the InPort ID from step 1 that you want to copy.</li>
              <li>Once created, edit content in the ENTITY record accordingly (see Update Child section).</li>
            </ul>
          </li>
          <li><strong>Create a new child record from scratch</strong>
            <ul>
              <li>Follow the steps as above, except DO NOT add an InPort ID in the CLONE FROM box.</li>
              <li>Use the Rubric to complete the record, or...</li>
              <li>Scroll to the bottom of the page and EDIT Entity Information and QUICK EDIT Data Attributes to add the NAME, TYPE, and DESCRIPTION for each column in the data file to be submitted to the archive (see Update Child section for details).</li>
            </ul>
          </li>
        </ul>
      </li>
      <li>
        <strong>Update Child Record</strong>
        <ul>
          <li><strong>Entity Info</strong>
            <ul>
              <li><strong>Entity Type:</strong> What is the record describing? (e.g., Data table, spreadsheet, data file, GIS file are most commonly used).</li>
              <li><strong>Active Version:</strong> Can be "no" if it’s legacy data or a retired method.</li>
              <li><strong>Description:</strong> Briefly, what do the entities describe?</li>
              <li><strong>Change Summary:</strong> Why the need for the entity record or updates? (e.g., method change, new metrics added, fields deprecated/no longer used).</li>
            </ul>
          </li>
          <li><strong>Attributes</strong>
            <ul>
              <li><strong>Attribute Summary:</strong> Review descriptions for each column name. Do they make sense?</li>
              <li>Use EDIT ATTRIBUTES to change a field Name and add/edit sequence numbers.</li>
              <li>Use QUICK EDIT to edit the Type and Description for each field. Be thorough, as the archive will flag data that doesn’t match descriptions.</li>
              <li><em>If you make changes to an NCRMP Entity record for one region, the change should most likely be made to the Entity record for the other 3 regions too. Work with your Data Manager to do this.</em></li>
              <li><strong>TYPE:</strong> TEXT, NUMERIC, DATE.</li>
              <li>Note: If you are submitting several folders of images via NCEI, you will need to define them in the child item. In this case, the type will be ‘images’.</li>
            </ul>
          </li>
        </ul>
      </li>
      <li>
        <strong>Create the Data Dictionary file</strong>
        <br><em>This file is needed for the NCEI archive package.</em>
        <ul>
          <li><strong>Export the data dictionary from the ENTITY Attribute Summary:</strong>
            <ul>
              <li>Select the headers (from the small bar graph icon to "Description") and all the rows within the summary.</li>
              <li>Copy and paste into Excel using the “Match Destination Formatting” option.</li>
              <li>Delete the first two columns.</li>
            </ul>
          </li>
          <li>Save as a CSV file.</li>
          <li><strong>File name:</strong> <code>ESD_&lt;METRIC&gt;_DataDictionary_&lt;REGION&gt;_&lt;yyyymmdd&gt;.csv</code></li>
          <li><strong>Location:</strong> <code>T:\DataManagement\NCEI Archive Packages\&lt;DATASET&gt;\Documentation\</code></li>
        </ul>
      </li>
    </ul></p>
</div>

<div id="related-items" class="tab-content">
  <p>Link to other relevant records within InPort.</p>
  <ul>
    <li>Are there any related InPort records that are not yet listed?</li>
    <li>If so, add them as a <strong>Cross-Reference</strong>.</li>
  </ul>
</div>

<div id="catalog-details" class="tab-content">
  <p>No information typically needs to be entered or changed in this section for this workflow.
    <ul><li> This is optional, but if you find you struggle to find your dataset in an InPort search, add tags here by editing the Catalog Details section.</li></ul></p></div>


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
<center><a href="{{ '/docs/Stage-4-S2N.html' | relative_url }}" class="btn btn-custom fs-6 mb-4 mb-md-0">
  Next Stage: Review S2N Stub
</a></center>
