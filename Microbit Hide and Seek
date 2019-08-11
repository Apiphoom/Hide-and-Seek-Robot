control.onEvent(EventBusSource.MES_DPAD_CONTROLLER_ID, EventBusValue.MICROBIT_EVT_ANY, function () {
    if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_A_DOWN) {
        iBIT.setMotor(ibitMotorCH.M1, ibitMotor.Forward, 100)
        iBIT.setMotor(ibitMotorCH.M2, ibitMotor.Forward, 80)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_A_UP) {
        iBIT.MotorStop()
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_B_DOWN) {
        iBIT.setMotor(ibitMotorCH.M1, ibitMotor.Backward, 100)
        iBIT.setMotor(ibitMotorCH.M2, ibitMotor.Backward, 80)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_B_UP) {
        iBIT.MotorStop()
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_C_DOWN) {
        iBIT.Spin(ibitSpin.Left, 70)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_C_UP) {
        iBIT.MotorStop()
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_D_DOWN) {
        iBIT.Spin(ibitSpin.Right, 70)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_D_UP) {
        iBIT.MotorStop()
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_3_DOWN) {
        iBIT.Servo(ibitServo.SV1, 100)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_3_UP) {
        iBIT.Servo(ibitServo.SV1, 135)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_4_DOWN) {
        iBIT.Servo(ibitServo.SV2, 70)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_4_UP) {
        iBIT.Servo(ibitServo.SV2, 1)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_1_DOWN) {
        iBIT.Motor(ibitMotor.Forward, 30)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_1_UP) {
        iBIT.MotorStop()
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_2_DOWN) {
        iBIT.Servo(ibitServo.SV1, 120)
    } else if (control.eventValue() == EventBusValue.MES_DPAD_BUTTON_2_UP) {
        iBIT.Servo(ibitServo.SV1, 135)
    } else {
    	
    }
})
bluetooth.onBluetoothConnected(function () {
    basic.showIcon(IconNames.Happy)
    basic.showString("Connect")
})
bluetooth.onBluetoothDisconnected(function () {
    basic.showIcon(IconNames.Sad)
    basic.showString("Disconnect")
})
