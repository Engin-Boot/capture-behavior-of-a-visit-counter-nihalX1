# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: Hospital is working.
  When: Visitor enters door where sensor is present.
  Then: Plot the trends of vistor on graph

Scenario: Alert when seating capacity is full

  Given: Hospital is functional.
  When: Seating is full.
  Then: Send alert to system.
