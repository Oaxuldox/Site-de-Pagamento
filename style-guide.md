 <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f4;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1 {
      text-align: center;
      color: #333;
    }
    label {
      display: block;
      margin: 15px 0 5px;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #28a745;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #218838;
    }
    .results {
      margin-top: 20px;
      padding: 20px;
      background: #e9ecef;
      border-radius: 10px;
    }
    .attribution {
      font-size: 11px;
      text-align: center;
      margin-top: 20px;
    }
    .attribution a {
      color: hsl(228, 45%, 44%);
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Mortgage Calculator</h1>
    <button id="clearButton">Clear All</button>

    <label for="amount">Mortgage Amount</label>
    <input type="number" id="amount" placeholder="Enter amount" />

    <label for="term">Mortgage Term (years)</label>
    <input type="number" id="term" placeholder="Enter term" />

    <label for="rate">Interest Rate (%)</label>
    <input type="number" id="rate" step="0.01" placeholder="Enter rate" />

    <label for="type">Mortgage Type</label>
    <select id="type">
      <option value="repayment">Repayment</option>
      <option value="interest-only">Interest Only</option>
    </select>

    <button id="calculateButton">Calculate Repayments</button>

    <div class="results" id="results">
      <p>Complete the form and click “calculate repayments” to see what your monthly repayments would be.</p>
    </div>
  </div>

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge">Frontend Mentor</a>. 
    Coded by <a href="#">Rafael Marjoub</a>.
  </div>
