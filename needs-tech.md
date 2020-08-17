# Visit-counter technical needs

Scenario: Recover across restarts of the server.
that runs the visit-counter

  Given: Counter was initially working.
  When: When programmer restarts Server.
  Then: Obtain last saved value of counter and assign to existing.

Scenario: Reconcile counts if the sensor is offline for a while

  Given: Server was online for a while before going offline.
  When: Server goes offline.
  Then: Obtain last saved value of counter and assign to existing.
