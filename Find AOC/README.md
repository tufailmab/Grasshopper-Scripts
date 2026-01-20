<h1>Find AOC – Grasshopper Tool</h1>

<p>
  <strong>Find AOC.gh</strong> is a Grasshopper visual programming tool developed to
  compute the <strong>Area Under the Curve (AOC)</strong> for pushover analysis results.
  The tool reads <strong>force–displacement data directly from an Excel file</strong>
  and calculates the enclosed area of the curve, which represents energy-related
  response parameters commonly used in structural performance assessment (I developed this tool primarily for processing Abaqus FEA results, and while the AOC can also be computed using Python or Excel’s integration tools, I prefer and enjoy working with visual programming).
</p>

<h2>Workflow Overview</h2>
<ol>
  <li>Prepare an <strong>Excel file</strong> containing pushover data.</li>
  <li>Ensure the file includes:
    <ul>
      <li><strong>Displacement values</strong> (mm)</li>
      <li><strong>Force values</strong> (kN)</li>
    </ul>
  </li>
  <li>Specify the <strong>Excel file path</strong> in the Grasshopper file input panel.</li>
  <li>Define the <strong>sheet name</strong> containing the pushover data.</li>
  <li>Enter the <strong>cell address range</strong> for:
    <ul>
      <li>Displacement data</li>
      <li>Force data</li>
    </ul>
  </li>
  <li>The tool reads the data directly from Excel.</li>
  <li>A <strong>force–displacement curve</strong> is generated internally.</li>
  <li>The <strong>area under the curve (AOC)</strong> is automatically calculated.</li>
  <li>The final numerical result is displayed for user interpretation and reporting.</li>
</ol>

<h2>Features</h2>
<ul>
  <li><strong>Excel-Based Input:</strong> Reads force and displacement data directly from Excel.</li>
  <li><strong>Pushover Curve Processing:</strong> Handles monotonic force–displacement relationships.</li>
  <li><strong>Area Under Curve Calculation:</strong> Automatically computes AOC values.</li>
  <li><strong>Engineering Units:</strong> Supports force in kN and displacement in mm.</li>
  <li><strong>Minimal User Interaction:</strong> No manual curve cleaning or baking required.</li>
  <li><strong>Post-Processing Ready:</strong> Results can be directly used in reports or spreadsheets.</li>
</ul>

<h2>Usage Instructions</h2>
<ol>
  <li>Open <code>Find AOC.gh</code> in Grasshopper.</li>
  <li>Prepare your Excel file with force and displacement data.</li>
  <li>Enter the full <strong>file path</strong> of the Excel file.</li>
  <li>Specify the <strong>sheet name</strong> containing the data.</li>
  <li>Provide the correct <strong>cell addresses</strong> for:
    <ul>
      <li>Displacement column</li>
      <li>Force column</li>
    </ul>
  </li>
  <li>Ensure both datasets have the same number of data points.</li>
  <li>Run the Grasshopper definition.</li>
  <li>Read the computed <strong>Area Under the Curve (AOC)</strong> from the output panel.</li>
</ol>

<h2>Requirements</h2>
<ul>
  <li>Rhinoceros 3D</li>
  <li>Grasshopper</li>
  <li>Microsoft Excel (or compatible spreadsheet software)</li>
</ul>
<p>No additional Grasshopper plugins are required.</p>

<h2>License</h2>
<p>
  This project is licensed under the <strong>MIT License</strong>. You are free to use,
  modify, and distribute this tool under the terms of the MIT License.
  If you use this tool in academic or professional work, proper attribution is appreciated.
</p>

<h2>Developer Information</h2>
<ul>
  <li><strong>Developer:</strong> Tufail Mabood</li>
  <li><strong>Contact:</strong> <a href="https://wa.me/+923440907874">WhatsApp</a></li>
  <li><strong>Note:</strong> This tool is open-source. Feel free to modify and improve it.</li>
</ul>
