# UAVSLAM-Crazyflie-Firmware
 Firmware for Crazyflie v2.1 compatible with both BigQuad and Flow v2


### Modified the following files:
- config.mk
- bigquad.c
- flowdeck_v1v2.c

<img src="https://github.com/zhuoming34/UAVSLAM-Crazyflie-Firmware/blob/main/pic/bigQ_enable.png" width="800">
<img src="https://github.com/zhuoming34/UAVSLAM-Crazyflie-Firmware/blob/main/pic/flow_enable.png" width="800">

### Instead of "Cut trace and solder patch on Flow deck from IO3 to IO1", do what is shown below:
1. Simply not having flow deck and bigQuad deck connected at IO3
2. Connect I03 to IO1 on flow deck using a "η"-shape pin (or soldering "r" and "l" pins)

(In such a way the flow deck can remain unscathed)

<img src="https://github.com/zhuoming34/UAVSLAM-Crazyflie-Firmware/blob/main/pic/BigQuadwFlowV2.JPG" width="400">👇
<img src="https://github.com/zhuoming34/UAVSLAM-Crazyflie-Firmware/blob/main/pic/BigQuadwFlowV2_explained.JPG" width="800">
