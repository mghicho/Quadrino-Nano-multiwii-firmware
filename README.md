# Quadrino Nano MultiWii firmware
Quadrino Nano FCT - Defines
```
#define CONFIG_H_
#define QUADX
#define MINTHROTTLE 1220
#define MAXTHROTTLE 1850
#define MINCOMMAND  1000
#define I2C_SPEED 400000L
#define LOOP_TIME 2800
#define QUADRINO_NANO   
#define MPU6050       
#define MS561101BA
#define AK8975
#define PID_CONTROLLER 1
#define YAW_DIRECTION 1
#define ONLYARMWHENFLAT 
#define ALLOW_ARM_DISARM_VIA_TX_YAW
#define CAM_TIME_HIGH 1000
#define FLAPPERON_EP   1500,1700
#define FLAPPERON_INVERT -1,1
#define YAW_COLL_PRECOMP 10
#define YAW_COLL_PRECOMP_DEADBAND 120
#define COLLECTIVE_PITCH      THROTTLE
#define COLLECTIVE_RANGE 80,0,80
#define YAWMOTOR                 0
#define SERVO_NICK   10,-10,0
#define SERVO_LEFT   10,5,10
#define SERVO_RIGHT  10,5,-10
#define CONTROL_RANGE   100,100
#define PPM_ON_THROTTLE
#define SBUS_MID_OFFSET 988
#define RCAUXPIN12
#define D8BUZZER
#define SERIAL0_COM_SPEED 115200
#define SERIAL1_COM_SPEED 115200
#define SERIAL2_COM_SPEED 115200
#define SERIAL3_COM_SPEED 115200
#define NEUTRALIZE_DELAY 100000
#define GYRO_LPF_98HZ
#define FAILSAFE_DELAY     10
#define FAILSAFE_OFF_DELAY 200
#define FAILSAFE_THROTTLE  (MINTHROTTLE+50)
#define FAILSAFE_DETECT_TRESHOLD  985
#define GPS_SERIAL 2
#define GPS_BAUD   57600
#define VENUS_UPDATE_RATE  40
#define VENUS
#define GPS_LED_INDICATOR
#define USE_MSP_WP
#define NAV_CONTROLS_HEADING       1
#define NAV_TAIL_FIRST             1
#define NAV_SET_TAKEOFF_HEADING    1
#define MAG_DECLINATION  0.00f
#define GPS_LEAD_FILTER               
#define GPS_WP_RADIUS              100
#define SAFE_WP_DISTANCE           500
#define MAX_NAV_ALTITUDE           100
#define NAV_SPEED_MIN              100
#define NAV_SPEED_MAX              400
#define NAV_SLOW_NAV               0
#define CROSSTRACK_GAIN            .4
#define NAV_BANK_MAX 3000
#define RTH_ALTITUDE               15
#define WAIT_FOR_RTH_ALT           1
#define NAV_TAKEOVER_BARO          1
#define IGNORE_THROTTLE            1
#define FENCE_DISTANCE      600
#define LAND_SPEED          100
#define LCD_SERIAL_PORT 0
#define LCD_MENU_PREV 'p'
#define LCD_MENU_NEXT 'n'
#define LCD_VALUE_UP 'u'
#define LCD_VALUE_DOWN 'd'
#define LCD_MENU_SAVE_EXIT 's'
#define LCD_MENU_ABORT 'x'
#define BUZZER
#define RCOPTIONSBEEP         
#define VBAT              
#define VBATSCALE       128
#define VBATNOMINAL     126
#define VBATLEVEL_WARN1 107
#define VBATLEVEL_WARN2  99
#define VBATLEVEL_CRIT   93
#define NO_VBAT          16
#define VBAT_OFFSET       0
#define VBAT_CELLS_NUM 0
#define VBAT_CELLS_PINS A0,A1,A2,A3,A4,A5
#define VBAT_CELLS_OFFSETS 0,50,83,121,149,177
#define VBAT_CELLS_DIVS 75,122,98,18,30,37
#define PSENSORNULL 510
#define PINT2mA 132
#define ALT_HOLD_THROTTLE_NEUTRAL_ZONE    50
#define BOARD_NAME "MultiWii   V-.--"
#define NO_FLASH_CHECK
#define VBAT_PRESCALER 16
#define MIDRC 1500
#define SERVO_RFR_50HZ
#define SERVO_RFR_RATE  50
#define ESC_CALIB_LOW  MINCOMMAND
#define ESC_CALIB_HIGH 2000
#define LCD_TELEMETRY_FREQ 23
#define LCD_TELEMETRY_AUTO_FREQ  967
#define PSENSOR_SMOOTH 16
#define VBAT_SMOOTH 16
#define RSSI_SMOOTH 16
#define DISABLE_POWER_PIN
#define QUADRINO_MODEL      Nano
#define QUADRINO_VERSION    V1
#define QUADRINO_AGGRESSION    0
#define QUADRINO_ANTIWOBBLE    0
#define QUADRINO_ARMLENGTH    450
#define QUADRINO_ARMLENGTH_UNIT    IN
```