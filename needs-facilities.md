# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: Sensor is working and counter updated when patient enters.
  When: Computation of visitor trend.
  Then: Plot the trends of visitor on graph.

Scenario: Alert when seating capacity is full

  Given: Sensor and counter are working.
  When: If there are no vacant chairs when counting the same.
  Then: Send alert to system.
