# bluetooth_control_example

## Check is Bluetooth enable

dart
import 'package:bluetooth_control/bluetooth_control.dart';

bool isBluetoothEnable = await BluetoothControl.isEnable;

## Enable Bluetooth

dart
import 'package:bluetooth_control/bluetooth_control.dart';

bool isEnableSuccess = await BluetoothControl.turnOn;

