# YRoaster 
Flutter application was developed for Android. The application is able of connecting to an Arduino device via Bluetooth and sending temperature-related commands.

Each profile in the app has an associated vector of points, which is used as input for the Arduino program. Using these points, the Arduino implements a temperature control system by comparing the desired temperature values with the real-time readings obtained from a Type K thermocouple through the RTC module. Based on this comparison, the Arduino controls the amount of gas delivered at the output.

Menu
![Screenshot_20240220-182851](https://github.com/yeyomuri/coffee_roaster/assets/34101726/363f1a9b-6c3c-45fb-b42c-b6994593cbce)

Custom s curve
![Screenshot_20240220-183244](https://github.com/yeyomuri/coffee_roaster/assets/34101726/9d95d007-c8a4-4dfe-9a8b-d362eab03f99)

Real-time graph of the S curve
![Screenshot_20240220-182904](https://github.com/yeyomuri/coffee_roaster/assets/34101726/2187ff5d-6647-443d-9798-af7314d540f3)


