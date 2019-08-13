# class Feedback

 **Member values** 

|Member name|Data type|Description|Usage|
|-----------|---------|-----------|-----|
|feedback\_id| [MessageId](MessageId.md#)|MessageId|To set feedback\_id, you simply assign a value directly to a field within feedback\_id. You can also use the parent message's HasField\(\) method to check if a message type field value has been set.|
|status\_flags|int|Status flags|You can manipulate the field status\_flags as if it were a regular field. To clear the value of status\_flags and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|jitter\_comm|int|Jitter from the communication \(in microseconds\)|You can manipulate the field jitter\_comm as if it were a regular field. To clear the value of jitter\_comm and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_acceleration\_x|float|IMU Measured acceleration \(X-Axis\) of the interface module \(in meters per second ^ squared\)|You can manipulate the field imu\_acceleration\_x as if it were a regular field. To clear the value of imu\_acceleration\_x and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_acceleration\_y|float|IMU Measured acceleration \(Y-Axis\) of the interface module \(in meters per second ^ squared\)|You can manipulate the field imu\_acceleration\_y as if it were a regular field. To clear the value of imu\_acceleration\_y and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_acceleration\_z|float|IMU Measured acceleration \(Z-Axis\) of the interface module \(in meters per second ^ squared\)|You can manipulate the field imu\_acceleration\_z as if it were a regular field. To clear the value of imu\_acceleration\_z and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_angular\_velocity\_x|float|IMU Measured angular velocity \(X-Axis\) of the interface module \(in degrees per second\)|You can manipulate the field imu\_angular\_velocity\_x as if it were a regular field. To clear the value of imu\_angular\_velocity\_x and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_angular\_velocity\_y|float|IMU Measured angular velocity \(Y-Axis\) of the interface module \(in degrees per second\)|You can manipulate the field imu\_angular\_velocity\_y as if it were a regular field. To clear the value of imu\_angular\_velocity\_y and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|imu\_angular\_velocity\_z|float|IMU Measured angular velocity \(Z-Axis\) of the interface module \(in degrees per second\)|You can manipulate the field imu\_angular\_velocity\_z as if it were a regular field. To clear the value of imu\_angular\_velocity\_z and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|voltage|float|Voltage of the main board \(in Volt\)|You can manipulate the field voltage as if it were a regular field. To clear the value of voltage and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|temperature\_core|float|Microcontroller temperature \(in degrees Celsius\)|You can manipulate the field temperature\_core as if it were a regular field. To clear the value of temperature\_core and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|fault\_bank\_a|int|Fault bank A \(see InterconnectConfig.SafetyIdentifier\)|You can manipulate the field fault\_bank\_a as if it were a regular field. To clear the value of fault\_bank\_a and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|fault\_bank\_b|int|Fault bank B \(see InterconnectConfig.SafetyIdentifier\)|You can manipulate the field fault\_bank\_b as if it were a regular field. To clear the value of fault\_bank\_b and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|warning\_bank\_a|int|Warning bank A \(see InterconnectConfig.SafetyIdentifier\)|You can manipulate the field warning\_bank\_a as if it were a regular field. To clear the value of warning\_bank\_a and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|warning\_bank\_b|int|Warning bank B \(see InterconnectConfig.SafetyIdentifier\)|You can manipulate the field warning\_bank\_b as if it were a regular field. To clear the value of warning\_bank\_b and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|gripper\_feedback|oneof:tool\_feedback [Feedback](../GripperCyclic/Feedback.md#)|Gripper model tool feedback|You can manipulate the field gripper\_feedback as if it were a regular field. To clear the value of gripper\_feedback and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface. The message class also has a WhichOneof method that lets you find out which field \(if any\) in the oneof has been set.|

**Parent topic:** [InterconnectCyclic \(Python\)](../../summary_pages/InterconnectCyclic.md)
