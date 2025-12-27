Sample SPL Queries

Detect failed login attempts:
index=* EventCode=4625
| stats count by Account_Name, Source_Network_Address
