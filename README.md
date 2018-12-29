# RPLIDAR

Programs of RPLIDAR be used at 2018_buttole_flip_cafe.

Based on rplidar_sdk_v1.6.1(https://github.com/Slamtec).

vc10, win32 only. Opencv-3.3.1 (installed by cmake(for win32))

---we can get more latest version.

# File name: SerchTables

  Searches three tables and send their positions on serial com port. (unit cm)

  If you use this from command-line, you can set up baud-rate of RPLIDAR and serial com port.

  You can set the sampling rate in the same way.

# File name: MovingRobot

  When get table data from com port by SerchTable, view them.

  Type 'R': Red coat

  Type 'B': Blue coat

---ATTENTION---

  It will talk at the same time as starting up.
