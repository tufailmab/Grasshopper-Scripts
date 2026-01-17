  <h1>Hyst-to-Backbone Grasshopper Tool</h1>

  <p>
    <strong>Hyst-to-Backbone.gh</strong> is a Grasshopper visual programming tool developed to
    assist in processing hysteresis force–displacement data. The tool facilitates visualization,
    baking, separation, and post-processing of hysteresis data, while the <strong>backbone curve
    extraction is performed manually by the user</strong>.
  </p>

  <h2>Workflow Overview</h2>
  <ol>
    <li>Paste <strong>displacement data</strong> into the displacement input panel.</li>
    <li>Paste <strong>force data</strong> into the force input panel.</li>
    <li>The tool generates a <strong>force–displacement polyline</strong> representing the hysteresis response.</li>
    <li>The polyline points are <strong>baked into Rhino</strong>.</li>
    <li>The user <strong>manually cleans the baked points</strong> by removing hysteresis loops.</li>
    <li>Only the points corresponding to the <strong>backbone curve</strong> are retained by the user.</li>
    <li>The cleaned backbone points are then reintroduced into the workflow.</li>
    <li>The backbone data is separated into:
      <ul>
        <li><strong>Positive branch</strong></li>
        <li><strong>Negative branch</strong></li>
      </ul>
    </li>
    <li>Energy absorption values of the manually selected backbone curves are extracted.</li>
    <li>The final numerical results are copied for <strong>Excel-based post-processing</strong>.</li>
  </ol>

  <h2>Features</h2>
  <ul>
    <li><strong>Hysteresis Visualization:</strong> Generates force–displacement polylines from raw data.</li>
    <li><strong>Point Baking:</strong> Bakes hysteresis points into Rhino for user-controlled processing.</li>
    <li><strong>Manual Backbone Selection:</strong> User retains only backbone curve points.</li>
    <li><strong>Branch Separation:</strong> Separates positive and negative backbone branches.</li>
    <li><strong>Energy Calculation:</strong> Computes energy absorption from user-selected backbone data.</li>
    <li><strong>Excel-Compatible Output:</strong> Clean numerical output for spreadsheet analysis.</li>
  </ul>

  <h2>Usage Instructions</h2>
  <ol>
    <li>Open <code>Hyst-to-Backbone.gh</code> in Grasshopper.</li>
    <li>Paste displacement values into the displacement panel.</li>
    <li>Paste force values into the force panel.</li>
    <li>Ensure both datasets have matching lengths.</li>
    <li>Generate and bake the hysteresis curve points.</li>
    <li>Manually delete non-backbone points in Rhino.</li>
    <li>Keep only the backbone curve points.</li>
    <li>Feed the cleaned points back into the Grasshopper definition.</li>
    <li>Separate positive and negative branches.</li>
    <li>Copy the energy and backbone data into Excel.</li>
  </ol>

  <h2>Requirements</h2>
  <ul>
    <li>Rhinoceros 3D</li>
    <li>Grasshopper</li>
  </ul>
  <p>No additional plugins are required.</p>

  <h2>License</h2>
  <p>
    This project is licensed under the <strong>MIT License</strong>. You are free to use, modify, and distribute this tool under the terms of the MIT License.
    If you use this tool in academic or professional work, proper attribution is appreciated.
  </p>

  <h2>Developer Information</h2>
  <ul>
    <li><strong>Developer:</strong> Tufail Mabood</li>
    <li><strong>Contact:</strong> <a href="https://wa.me/+923440907874">WhatsApp</a></li>
    <li><strong>Note:</strong> This tool is open-source. Feel free to modify and improve it.</li>
  </ul>

</body>
</html>
