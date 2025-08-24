<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GCCV Other Than 3 Wheeler Premium Calculator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>GCCV Other Than 3 Wheeler Premium Calculator</h1>
    </header>
    <div class="tabs">
      <button class="tab-btn active" data-tab="input">Input Field</button>
      <button class="tab-btn" data-tab="selection">Selection Field</button>
      <button class="tab-btn" data-tab="addons">Add On Coverage</button>
      <button class="tab-btn" data-tab="discount">Discount</button>
    </div>
    <form id="premiumForm">
      <!-- Tab 1: Input Fields -->
      <div class="tab-content active" id="input">
        <div class="input-grid">
          <div>
            <label>Date of Registration (DOR)</label>
            <input type="date" id="dor" required>
          </div>
          <div>
            <label>Renewal Date (optional)</label>
            <input type="date" id="renewal">
          </div>
          <div>
            <label>Zone</label>
            <select id="zone" required>
              <option value="">Select Zone</option>
              <option value="A">Zone A (Chennai, Delhi/New Delhi, Kolkata, Mumbai)</option>
              <option value="B">Zone B (Other State Capitals)</option>
              <option value="C">Zone C (Rest of India)</option>
            </select>
          </div>
          <div>
            <label>Gross Vehicle Weight (GVW)</label>
            <input type="number" id="gvw" min="0" placeholder="0">
          </div>
          <div>
            <label>Seating Capacity as per RC</label>
            <input type="number" id="seating" min="0" placeholder="0">
          </div>
          <div>
            <label>Trailer</label>
            <div>
              <label><input type="radio" name="trailer" value="yes"> Yes</label>
              <label><input type="radio" name="trailer" value="no" checked> No</label>
            </div>
          </div>
          <div id="agriField" style="display:none;">
            <label>Agriculture Usage</label>
            <div>
              <label><input type="radio" name="agri" value="yes"> Yes</label>
              <label><input type="radio" name="agri" value="no" checked> No</label>
            </div>
          </div>
        </div>
        <div class="sum-insured-section">
          <h3>Sum Insured</h3>
          <div id="sumInsuredRows"></div>
          <button type="button" id="addSumInsuredRow" class="add-row-btn">+</button>
        </div>
        <div>
          <label><input type="checkbox" id="cng"> CNG</label>
          <div id="cngOptions" style="display:none;">
            <label><input type="checkbox" id="cngInbuilt"> Inbuilt</label>
            <label><input type="checkbox" id="cngExtra"> Extra Fitted</label>
            <input type="number" id="cngValue" placeholder="Value of CNG Kit" style="display:none; margin-top:5px;">
          </div>
        </div>
        <div>
          <label>Fleet Owner</label>
          <input type="checkbox" id="fleetOwner">
        </div>
        <div>
          <label>Claim in Previous Policy</label>
          <div>
            <label><input type="radio" name="claimPrev" value="yes"> Yes</label>
            <label><input type="radio" name="claimPrev" value="no" checked> No</label>
          </div>
        </div>
      </div>
      <!-- Tab 2: Selection Field -->
      <div class="tab-content" id="selection">
        <div>
          <label>NCB Discount</label>
          <select id="ncb" required>
            <option value="0">0%</option>
            <option value="20">20%</option>
            <option value="25">25%</option>
            <option value="45">45%</option>
            <option value="50">50%</option>
            <option value="nameTransferred">Name Transferred</option>
          </select>
        </div>
      </div>
      <!-- Tab 3: Add On Coverage -->
      <div class="tab-content" id="addons">
        <div>
          <label><input type="checkbox" id="imt23"> IMT-23</label>
        </div>
        <div>
          <label>Towing Charge Premium</label>
          <input type="number" id="towingSum" placeholder="0">
        </div>
        <div>
          <label>Geographic Area OD Premium</label>
          <select id="geoPremium">
            <option value="no">No</option>
            <option value="yes">Yes</option>
          </select>
        </div>
        <div>
          <label>Return to Invoice Premium</label>
          <select id="rti">
            <option value="no">No</option>
            <option value="yes">Yes</option>
          </select>
        </div>
        <div>
          <label>Consumable Premium</label>
          <select id="consumable">
            <option value="no">No</option>
            <option value="yes">Yes</option>
          </select>
        </div>
        <div>
          <label><input type="checkbox" id="nilDep"> Nil Depreciation Premium</label>
        </div>
        <div>
          <label>EMI Protection Premium</label>
          <select id="emiProtect">
            <option value="no">No</option>
            <option value="1">1 Month</option>
            <option value="2">2 Months</option>
          </select>
          <input type="number" id="emiSum" placeholder="EMI Sum Insured" style="margin-top:5px;">
        </div>
      </div>
      <!-- Tab 4: Discount -->
      <div class="tab-content" id="discount">
        <div>
          <label>TP Liability Add-ons</label>
          <div class="tp-addons">
            <label><input type="checkbox" id="paOwnerDriver"> Compulsory PA Owner Driver (₹320)</label>
            <label>LL Employee: <input type="number" id="llEmp" placeholder="Count" min="0"></label>
            <label>LL Paid Driver: <input type="number" id="llPaidDriver" placeholder="Count" min="0"></label>
            <label>Cleaner: <input type="number" id="llCleaner" placeholder="Count" min="0"></label>
            <label>Conductor: <input type="number" id="llConductor" placeholder="Count" min="0"></label>
            <label><input type="checkbox" id="paPaidDriver"> PA to Paid Driver (₹60)</label>
            <label>LL TO NFPP (others): <input type="number" id="llNfppOthers" placeholder="Count" min="0"></label>
            <label>LL TO NFPP (incl. employees): <input type="number" id="llNfppIncl" placeholder="Count" min="0"></label>
            <label><input type="checkbox" id="llGeoArea"> LL Geographical Area (₹100)</label>
            <label><input type="checkbox" id="cngTp"> CNG/LPG-TP Cover (₹60)</label>
            <label><input type="checkbox" id="trailerTp"> Trailer TP</label>
          </div>
        </div>
        <div class="tab-actions">
          <button type="button" id="backBtn4">Back</button>
          <button type="submit" id="calculateBtn">Calculate Premium</button>
        </div>
      </div>
      <!-- Tab Navigation Buttons -->
      <div class="tab-actions" id="tabActions">
        <button type="button" id="backBtn" style="display:none;">Back</button>
        <button type="button" id="nextBtn">Next</button>
      </div>
    </form>
    <div id="resultSheet"></div>
  </div>
  <script src="script.js"></script>
</body>
</html>
