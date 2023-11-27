graph TD
  Start[Start Emergency Response] --> Assess[Assess Incident Type<br>Minor or Major]
  Assess -- Minor Incident --> Minor[Minor Incident<br>(Handled locally)]
  Minor -- No further action --> End[End Emergency Response]
  Assess -- Major Incident --> Meet[Meet Facilities Manager<br>in Front of Reception]
  Meet -- Facilities Manager not available --> Standby[Contact Standby Manager<br>and Initiate UERIMP]
  Standby -- No Crisis Management Team response --> ContactEmergency[Contact Emergency Services<br>and External Bodies]
  ContactEmergency -- No response from Emergency Services --> Alternative[Take Alternative Actions<br>to Safeguard People and Property]
  ContactEmergency -- Emergency Services respond --> Coordinate[Coordinate with Crisis<br>Management Team]
  Coordinate -- End Emergency Response --> End
