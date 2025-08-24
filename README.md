# AI-Based-Intrusion-Detection-for-Vehicle-CAN-Networks-Securing-Modern-Vehicles
Modern vehicles rely on CAN, which lacks built-in security and is vulnerable to spoofing, replay, and fuzzing attacks.  IDS learns normal CAN traffic patterns and flags or blocks anomalous messages in real time.  It detects attacks like spoofed RPM, brake/speed mismatches, fuzzing floods, and stealthy sensor manipulation.
# CAN Dataset Collection
 both normal and attack data (DoS, Fuzzy, Impersonation).
Preprocessing & Feature Extraction
Parsed CAN messages.
Extracted features: ID, byte values, time delta (∆t),data
Labeled each frame: normal = 0, fuzzy = 1, DoS = 2, impersonation = 3.
Model Training
Used LSTM model for sequence classification.
Input: time-windowed CAN sequences.
Output: one of four classes (multi-class classification).


