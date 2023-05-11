# A_Star
<!DOCTYPE html>
<html>
<body>
  <h1>Delivery Agent Problem</h1>
  <h2>Problem Definition</h2>
  <p><strong>Pick the order up and find the minimum cost path to the destination, then deliver the order to the customer.</strong></p>
  <h2>Environment Type</h2>
  <p><strong>Static</strong></p>
  <h2>Agent Type</h2>
  <p><strong>Pro-active</strong></p>
  <h2>PEAS</h2>
  <ul>
    <li><strong>P:</strong> Cost (minimize cost), Safely deliver the order, Check order integrity, Safety of the agent, Number of orders delivered per hour.</li>
    <li><strong>E:</strong> Roads</li>
    <li><strong>A:</strong> Arms, Wheels</li>
    <li><strong>S:</strong> GPS, Infrared, Camera</li>
  </ul>
  <h2>Solution / Plan</h2>
  <p>The best path for the agent is as follows:</p>
  <ol>
    <li>Start at the initial state, waiting for the order.</li>
    <li>Pick up the order.</li>
    <li>Go to location B.</li>
    <li>Continue to location E.</li>
    <li>Turn right to reach the destination.</li>
    <li>Drop the order to the customer (goal state).</li>
  </ol>
</body>
</html>
